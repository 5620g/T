# <b>cerner-Bot</b>

[mr.amirbagheri](https://telegram.me/mrcliapi)



راهنما
- [install](#install)


#install 

```sh
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev
```
```sh
git clone https://github.com/amir-cli/cernerbot
cd cernerbot
./launch.sh install 
./launch.sh # add phone
```


install bot api
##Run Api Telegram bot 

```sh
cd cernerbot
chmod +x apilaunch.sh
cd 
rm -rf .telegram-cli
./apilaunch.sh # add token hash
