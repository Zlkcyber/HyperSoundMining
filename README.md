# HyperSound Miner

- OFFICIAL WEBSITE ([https://hypers.money/](https://hypers.money/))

## Overview
This repository provides a minimal setup to begin mining $HYPERS tokens.

## Prerequisites
Before you start, ensure you have the following installed on your system: 

```Node.js``` and ```npm```  ([guide](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm))

## Install PM2 
install pm2 to run in background
- ```npm install -g pm2```
- ```pm2 --version```
## Get started
Follow these steps to set up and run the miner:
1. Download or clone this repository
- `git clone https://github.com/Zlkcyber/HyperSoundMining.git`
- `cd HyperSoundMining`
- `nano config.js`
2. Add the private key of your miner wallet in ```config.js```. For security reasons, it’s recommended to create a new wallet address specifically for mining. Only transfer the funds you wish to use for mining to this address.
3. Adjust the ```MINE_TX_PER_MINUTE``` parameter in ```config.js``` to control the number of mining transactions per minute. Increasing this number improves your chances of being selected as the winner and receiving the miner reward once the block is validated.
4. Run ```npm install``` to install the dependencies
5. Run ```pm2 mine.js``` to launch the miner bot in the background
6. run ```pm2 save``` to save the miner bot
7. run ```pm2 logs mine``` to see live mine logs

Please note: This example is very basic and will need to be improved to remain competitive over a long period of time.

## License

This project is licensed under the MIT License.
