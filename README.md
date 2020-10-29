# Red-Blockchain-Explorer
Block explorer for redstone.

#### Installation

1) It takes data from daemon redstone-node. It should be accessible from the Internet. Run redstone-node with open port as follows:
```bash
./redstone-node --enable-cors="*" --enable-blockexplorer --rpc-bind-ip=0.0.0.0 --rpc-bind-port=44402
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.


### Development
Devs:
    @devopsralf
Adapted to redstone:
    @leocornelius

Donate: 
### Note

A lot of this code is from the great Karbovanets/Karbowanec-Blockchain-Explorer
