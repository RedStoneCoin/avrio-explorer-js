# Red-Blockchain-Explorer
Block explorer for Redstone.

#### Installation

1) It takes data from daemon redstone-node. It should be accessible from the Internet. Run redstone-node with open port as follows:
```bash
./redstone-node --enable-cors="*" --enable-blockexplorer --rpc-bind-ip=0.0.0.0 --rpc-bind-port=9999
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.


### Development
Devs:
    @devopsralf
Adapted to RedStone:
    @leocornelius @redstoneco

Donate: RvXpchczNDWTMNvQLnzWWvGPpAqBbS6oDEdcDHMi94qphsY1pZ7adgwC4dCevmoEA35GK58dyvG7ziKBV9b8Cfr41YAQGBkQS
### Note

A lot of this code is from the great Karbovanets/Karbowanec-Blockchain-Explorer
