# CasinoCoin daemon containers
Create a CasinoCoin node in just minutes using docker. This project contains two docker 
files for creating a basic and secured node images. This does not mean it is a relay node, 
but it has the requirements for operating a relay node.

## Basic node
The basic node runs a plain text websocket. 
For instructions [view the README.md](basic/README.md)


## Secured node
The relay node runs a websocket secured by your pre-generated SSL certificate. 
For instructions [view the README.md](secured/README.md)

## Testnet node
The testnet node runs a plain text websocket and unsecured admin version against the test network. 
For instructions [view the README.md](testnet/README.md)