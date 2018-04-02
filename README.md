# Dosh-Blockchain-Explorer
Block explorer for Dosh CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon doshd. It should be accessible from the Internet. Run doshd with open port as follows:
```bash
./doshd --enable-cors="*" --enable_blockexplorer --rpc-bind-ip=0.0.0.0 --rpc-bind-port=11898
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.
