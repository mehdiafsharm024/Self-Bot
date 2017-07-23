[#!/]help | just send help in your group and get the commands |

**You can use "#", "!", or "/" to begin all commands

# Self-Bot
based on new tg
#Installation

Tested on Ubuntu 14.04

sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev
cd $HOME
git clone https://github.com/mehdiafsharm024/Self-Bot.git -b supergroups
cd Self-Bot
chmod +x launch.sh
./launch.sh install
cd .luarocks/bin
./luarocks-5.2 install luafilesystem
./luarocks-5.2 install lub
./luarocks-5.2 install luaexpat
./luarocks-5.2 install serpent
./luarocks-5.2 install feedparser
./luarocks-5.2 install redis-lua
./luarocks-5.2 install fakeredis
cd ../..
./launch.sh 

 بعد از زدن این دستور از شما شماره و کد تایید میخواد
 
Then Enter Your Phone number And Confirmation Code

Open ./data/config.lua and add your ID to the "sudo_users" section in the following format:

  sudo_users = {
    169890304,
    YourID
  }
  بعد از ان دوباره ربات خود رو لانچ کنید.
  #autolaunch
  cd Self-Bot
  screen ./launch.sh
  
