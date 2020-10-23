# I have decided to do this project without any pre made library. It can be found [here](https://github.com/AarKiMos/AarKiMos_Bot)

## AarKiMos_Bot 
##### AarKiMos_Bot is a friendly telegram chatbot and a fun little starter project developed in language 'C'.

Library Used: [Telebot by Smartnode](https://github.com/smartnode/telebot)

### Setting up the project:

#### Getting a token from BotFather:
Every telegram bot needs a token from telegram's BotFather bot. Get yourself one [here](https://core.telegram.org/bots#6-botfather)

#### Building the executabe

#####For Linux/MacOS users:
You need to install (if not already) libraries and build tools such as CMake.
On Debian-based Linux distributions you can do it as follows:

```sh
sudo apt-get install libcurl4-openssl-dev libjson-c-dev cmake binutils make
```
On Arch-based Linux Distributions install
```sh
sudo pacman -Syu curl json-c cmake make binutils
```

On Mac OSX, first install macports from [MacPorts](https://www.macports.org/install.php) and in Terminal

```sh
sudo port install cmake json-c curl
```

To build the library and the Bot run following commands:

```sh
cd [your repository]
mkdir -p Build && cd Build
cmake ../
make
```
If the build is succesful, you will find the executable in Build/TheBot


Wish to contribute? Read [CONTRIBUTING.md](./CONTRIBUTING.md)

#### Note to Hacktoberfest Participants:
Any PRs sent without or other than the issue assigned to you will be marked spam/invalid for hacktoberfest. 
There are be plenty of issues available to work upon, so please setup the project and ask for the issue you wish to work upon be assigned to you.



