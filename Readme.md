Ethereum

Google Cloud Engine

20GB
Ubuntu 14.04 (with Debian it didn´t work by default )
Do not delete disk when VM is deactivated
Http and Https traffic enabled
n1-highcpu-4 (4 vCPUs, 3,6 GB de memoria)
IP static
Forward activated

https://ethereum.gitbooks.io/frontier-guide/content/installing_linux.html

sudo apt-get install software-properties-common
sudo add-apt-repository -y ppa:ethereum/ethereum
## sudo add-apt-repository -y ppa:ethereum/ethereum-dev
sudo apt-get update
sudo apt-get install ethereum

geth account new
geth

