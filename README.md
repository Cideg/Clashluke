# Clashluke
sudo apt-get install libgtest-dev && cd /usr/src/gtest && sudo cmake . && sudo make && sudo mv libg* /usr/lib/

#### Requirements
* Coin daemon(s) (find the coin's repo and build latest version from source)
  * [List of Cryptonote coins](https://github.com/dvandal/cryptonote-nodejs-pool/wiki/Cryptonote-Coins)
* [Node.js](http://nodejs.org/) v4.0+
  * For Ubuntu: 
 ```
  curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash
  sudo apt-get install -y nodejs
```
* [Redis](http://redis.io/) key-value store v2.6+ 
  * For Ubuntu: 
```
sudo add-apt-repository ppa:chris-lea/redis-server
sudo apt-get update
sudo apt-get install redis-server
 ```
* libssl required for the node-multi-hashing module
  * For Ubuntu: `sudo apt-get install libssl-dev`

* Boost is required for the cryptoforknote-util module
  * For Ubuntu: `sudo apt-get install libboost-all-dev`
