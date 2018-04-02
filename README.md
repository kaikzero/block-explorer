# Dosh-Blockchain-Explorer
Block explorer for Dosh CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon doshcoind. It should be accessible from the Internet. Run doshcoind with open port as follows:
```bash
./Doshd --enable-cors="*" --enable_blockexplorer --rpc-bind-ip=0.0.0.0 --rpc-bind-port=11898
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.


### Development
Devs:
    @devopsralf

Donate: [TRTL] TRTLv2RCPuD7AaaVpQkRPF59MMLx5WW3qFxwJz4Doy7dHhNA6UuQjEpLL3rpUQS4RXdQn8fb4P1XC3K62GeJjGgG8DP9LNaTrNL

### Note

A lot of this code is from the great Karbovanets/Dosh-Blockchain-Explorer
