# MasqueCoin-Blockchain-Explorer
Block explorer for MasqueCoin CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon masquecoind. It should be accessible from the Internet. Run masqued with open port as follows:
```bash
./masquecoind --restricted-rpc --enable-cors=* --enable-blockchain-indexes --rpc-bind-ip=0.0.0.0 --rpc-bind-port=32348
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.
