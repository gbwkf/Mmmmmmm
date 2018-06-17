
d.sh install
./beyond.sh # Enter a phone number & confirmation code.
```
### One command
To install everything in one command, use:
```sh
cd $HOME && git clone https://github.com/BeyondTeam/BDSelf.git && cd BDSelf && chmod +x beyond.sh && ./beyond.sh install && ./beyond.sh
```

* * *

### Sudo And Bot

Open ./bot/bot.lua and add your ID to the "sudo_users" section in the following format:
```
    sudo_users = {157059515, YourID}
```
add your ID at line 131 in bot.lua
Then restart Bot.

* * *
