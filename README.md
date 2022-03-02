# Wappalyzer4Docker

## Description
The Dockerfile in the original repository [here](https://github.com/AliasIO/wappalyzer/tree/master/src/drivers/npm/) is broken,
and as I use an older version of nodejs I couldn't also easily install it using this small command line `npm i -g wappalyzer`,
so I had to fix it and then save it in my own repository.

## Installation

```bash
git clone https://github.com/ab2pentest/Wappalyzer4Docker
cd Wappalyzer4Docker/
docker build . -t wappalyzer
```

## Usage

```bash
docker run -rm -it wappalyzer
```

