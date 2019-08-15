# casinocoind docker setup
Install docker and run the following docker command in the project folder named ```testnet```:

```docker build . -t casinocoind```

Start casinicoind by running the following command:

```docker run -p 0.0.0.0:4443:4443/tcp -p 0.0.0.0:5005:5005/tcp -p 0.0.0.0:6006:6006/tcp -p 0.0.0.0:7777:7777/udp -d casinocoind:latest```
