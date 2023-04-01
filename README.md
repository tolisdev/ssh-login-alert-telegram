
# SSH Telegram Alerts

A simple script that will alert you on Telegram that somebody has logged in to your system, with his IP address and a handy link to see information about the IP.

![Example](msg.png)




## Installation

### Requirements
- git
- a telegram bot created using [@botfather](https://t.me/BotFather)
- and a server to run the script :)

### Install
1) Clone the project files and navigate to the folder
```bash
cd /opt/ && git clone https://github.com/MyTheValentinus/ssh-login-alert-telegram && cd ssh-login-alert-telegram
```

2) Add your credentials to the configuration file
```bash
nano credentials.config
```
There you will see 2 fields to add your information. Replace ```
 USERIDn CHANNELIDn ``` with your Channel ID. You can find it using [this handy guide.](https://www.alphr.com/find-chat-id-telegram/) Also, replace ```none``` with your bot ID that you got from the bot creation.

3) Deploy the script
- Give deploy.sh executable permissions: ```chmod +x deploy.sh```
- Run the deploy.sh file: ```deploy.sh```

4) Test that the script works!
- Run ```exit``` to log out.
- Login back to your server!




    
## Authors

- [@vdeville](https://github.com/vdeville/): Wrote the script
- [@tolisdev](https://github.com/tolisdev): Wrote the README


## License

[GNU General Public License v3.0](https://github.com/vdeville/ssh-login-alert-telegram/blob/master/LICENSE)


## Support

For support you may create an issue in the github repo :)

