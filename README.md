# AI Cryptoskins
[![Docker package](https://github.com/aymenfurter/ai-cryptoskins-botty/actions/workflows/python-package.yml/badge.svg?branch=main)](https://github.com/aymenfurter/ai-cryptoskins-botty/actions/workflows/python-package.yml)

[AI Cryptoskins](http://ai-cryptoskins.net/) are skins created by Artificial Intelligence. Botty (The name of this AI) is a torch based python app. It comes pre-trained, ready to generate as many skins as you like.


## Generate your own skins
```
docker build . -t botty
docker run -v /tmp:/tmp/img/ -t botty
```

## Network Visualiziation 
![Visualization](https://github.com/aymenfurter/ai-cryptoskins-botty/blob/main/netg.pth.png?raw=true)
based on [Netron](https://github.com/lutzroeder/netron)

## Prerequisites
All you need to run the AI is [Docker](https://docs.docker.com/get-docker/).
