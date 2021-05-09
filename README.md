![logo](http://ai-cryptoskins.net/wp-content/uploads/2021/05/cropped-cropped-cropped-logo-1.png)
# AI Crypto Skins - Botty
[![Docker package](https://github.com/aymenfurter/ai-cryptoskins-botty/actions/workflows/python-package.yml/badge.svg)](https://github.com/aymenfurter/ai-cryptoskins-botty/actions/workflows/python-package.yml)
[AI Cryptoskins](http://ai-cryptoskins.net/) are skins created by Artificial Intelligence. Botty (The name of the AI) is a torch based python app. It comes pre-trained, ready to generate as many skins as you like.


## Generate your own skins
```
docker build . -t generate
docker run -v /tmp:/tmp/img/ -t generate
```

## Prerequisites
All you need to run the AI is [Docker](https://docs.docker.com/get-docker/).
