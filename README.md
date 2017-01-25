# docker-keras-theano
[![](https://images.microbadger.com/badges/image/smizy/keras-theano.svg)](https://microbadger.com/images/smizy/keras-theano "Get your own image badge on microbadger.com") 
[![](https://images.microbadger.com/badges/version/smizy/keras-theano.svg)](https://microbadger.com/images/smizy/keras-theano "Get your own version badge on microbadger.com")
[![CircleCI](https://circleci.com/gh/smizy/docker-keras.svg?style=svg&circle-token=0142f1f1188bf3bd4407cd860c1e8280f7315f60)](https://circleci.com/gh/smizy/docker-keras-theano)

Python3 Theano backended Keras with Jupyter docker image based on alpine 

* numpy, scipy, pandas, scikit-learn, seaborn, theano, keras installed via pip. See ` pip list --format=columns` for detail.
* CPU only

## Usage
```
docker run -it --rm -v $(pwd):/data -w /data -p 8888:8888 smizy/keras-theano:1.2.1-cpu-alpine
```