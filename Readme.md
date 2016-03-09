#Ethereum

Describe how to setup an Ethereum Frontier node

## Google Cloud Engine

### VM instance
20GB
Ubuntu 14.04 (with Debian it didn´t work by default )
Do not delete disk when VM is deactivated
Http and Https traffic enabled
n1-highcpu-4 (4 vCPUs, 3,6 GB de memoria)
IP static
Forward activated

### Frontier setup (09/03/2016)

As described in:
https://ethereum.gitbooks.io/frontier-guide/content/installing_linux.html

sudo apt-get install software-properties-common
sudo add-apt-repository -y ppa:ethereum/ethereum
Not: sudo add-apt-repository -y ppa:ethereum/ethereum-dev
sudo apt-get update
sudo apt-get install ethereum

geth account new
geth

### Console
https://github.com/ethereum/go-ethereum/wiki/JavaScript-Console#adminminerstart

https://ethereum.gitbooks.io/frontier-guide/content/netstats.html

git clone https://github.com/cubedro/eth-net-intelligence-api
cd eth-net-intelligence-api
npm install
sudo npm install -g pm2
sudo apt-get install node 

pm2 start app.json




### Homestead

https://ethereum-homestead.readthedocs.org/en/latest/

https://gavofyork.gitbooks.io/turboethereum/content/chapter1.html

sudo add-apt-repository ppa:ethereum/ethereum-qt
sudo add-apt-repository ppa:ethereum/ethereum
sudo apt-get update
sudo apt-get install cpp-ethereum

## Other documentation

https://github.com/ethereum/wiki/wiki




