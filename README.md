# <i>cerner-Bot</i>
رباتی با پشتیبانی از دو زبان فارسی و انگلیسی

اوپن شده و نوشته شده توسط 

[mr.amirbagheri](https://telegram.me/amir_cli_api)

یکم اسکی از
TeleSeed !


**لیست **
- [install](#install)


#install 

```sh
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev
```
```sh
git clone https://github.com/telecerner/cernerfull -b supergroups
cd cernerfull
./launch.sh install 
./launch.sh # add phone
```
#Run by anti crash

<code>
bash start.sh
</code>


##Run Api Telegram bot 

```sh
cd cernerfull
chmod +x apilaunch.sh
cd 
rm -rf .telegram-cli
./apilaunch.sh # add token hash
