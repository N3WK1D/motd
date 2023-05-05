# MOTD
A simple script that prints out the weather, time & date, and system info & load, that can be run at login or system startup.

## Usage
There are any number of uses for the script, but it is most helpful when launching a terminal emulator or at TTY login prompt.
It is in no way necessary, but it is pretty and somewhat useful.

## Requirements
- ncurses or ncurses-utils
- curl
- util-linux
- ifconfig
- df
- free
- cat
- grep
- expr
- (Optional) toilet or figlet

## Install
The script will install into `/usr/local/bin` for easy launching, without touching `$PATH`.
```
git clone https://github.com/N3WK1D/motd.git
cd motd
sudo make install
```
