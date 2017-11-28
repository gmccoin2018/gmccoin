apt install aptitude
aptitude install  miniupnpc libminiupnpc-dev

apt-get install qt5-default qt5-qmake qtbase5-dev-tools qttools5-dev-tools build-essential libboost-dev libboost-system-dev libboost-filesystem-dev libboost-program-options-dev libboost-thread-dev libssl-dev libdb++-dev
cd /home/oanhle/eclipse-workspace/gmccoin
cd src
make -f makefile.unix
chmod -R 777 /home/oanhle/eclipse-workspace/gmccoin/src


touch .gmccoin/gmccoin.conf
vim .gmccoin/gmccoin.conf
added rpcuser & rpcpassword
start wallet
 ./gmccoind --daemon -txindex
// check processing
 pidof gmccoind
//





