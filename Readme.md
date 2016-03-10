#Ethereum

Describe how to setup an Ethereum Frontier node

## Amazon
Use GPU instances
user is ubuntu, not ec2-user

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

sudo apt-get install git
git clone https://github.com/cubedro/eth-net-intelligence-api
cd eth-net-intelligence-api
sudo apt-get install npm
npm install
sudo npm install -g pm2
sudo apt-get install node 
specify the secret on app.json (from the title of the Skype group)
pm2 start app.json

sudo nohup geth  > ethertraces.log 2>&1 &
jobs -l shows all the process running with nohup




### Homestead

https://ethereum-homestead.readthedocs.org/en/latest/

https://gavofyork.gitbooks.io/turboethereum/content/chapter1.html

sudo add-apt-repository ppa:ethereum/ethereum-qt
sudo add-apt-repository ppa:ethereum/ethereum
sudo apt-get update
sudo apt-get install cpp-ethereum

## Other documentation

https://github.com/ethereum/wiki/wiki

## Detect GPU type: NVIDIA

sudo lshw -C video

## Detect x86 or ppc
cat /proc/cpuinfo

sEtup GPU
https://forum.ethereum.org/discussion/comment/8889/#Comment_8889
https://developer.nvidia.com/cuda-downloads


