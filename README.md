
<a href="https://www.wappalyzer.com/?utm_source=readme&utm_medium=github&utm_campaign=wappalyzer"><img src="https://www.wappalyzer.com/images/logo/icon_192.png" height="72" alt="Wappalyzer" align="left" /></a>

# Wappalyzer4Docker

<br>

## Description
The Dockerfile in the original repository [here](https://github.com/AliasIO/wappalyzer/tree/master/src/drivers/npm/) is broken,
and as I use an older version of nodejs
![2022-03-02_14-41-12](https://user-images.githubusercontent.com/84577967/156373340-2c4058d5-d8eb-40c4-92ef-c159f575f64d.png)

I couldn't also install it using this small command line `npm i -g wappalyzer`

![2022-03-02_14-51-14](https://user-images.githubusercontent.com/84577967/156374462-51657c83-6e37-430b-94dc-0688667f3cba.png)


so I had to fix the Dockerfile and then save it here in my own repository.

## Notes

1. Before you use this try first to check your nodejs version if its =< 14 then you can easily install it using npm.
2. Also check if my repository isn't outdated, in that case try to check original repo and update the necessary files [here](https://github.com/AliasIO/wappalyzer/tree/master/src)

## Installation

```bash
git clone https://github.com/ab2pentest/Wappalyzer4Docker
cd Wappalyzer4Docker/
docker build . -t wappalyzer
```

![2022-03-02_14-55-49](https://user-images.githubusercontent.com/84577967/156375738-591143f2-3496-4390-8d16-d9915214dbbf.png)


## Usage

```bash
docker run --rm -it wappalyzer
```

![2022-03-02_14-59-21](https://user-images.githubusercontent.com/84577967/156375804-c89e93ee-a4be-4654-b193-dbee72f7a46b.png)

## Example

```bash
docker run --rm -it https://github.com | gofx
```

![2022-03-02_15-00-41](https://user-images.githubusercontent.com/84577967/156376073-a28cd969-8b24-429c-9ec4-ff898420a1f8.png)

And here where you can find [gofx](https://github.com/antonmedv/gofx).

