# Kitty Terminal Configuration 
kitty is a free and open-source GPU-accelerated terminal emulator focused on performance and features. kitty is written in a mix of C and Python programming languages, and it is one of few terminal emulators with GPU support along with Alacritty. Some says that kitty is faster than iTerm2 on macOS. kitty shares its name with another program — KiTTY —
Lets move on the topic 
This is a simple configuration for the kitty terminal , 
you will find two files dracula.conf and kitty.conf 
here, dracula.conf is the color scheme for the kitty terminal . 
and kitty.conf is the configuration file for the kitty terminal . 
you need to put 
* include "dracula.conf" 
at the first line of the kitty.conf file for using dracula color scheme on kitty terminal 
## Installation 
Clone the repository 
* git clone https://github.com/TheLinuxGuy001/kitty_terminal_conf.git
* cd kitty_terminal_conf
* cp *.conf ~/.config/kitty/
* create the kitty directory inside the .config directory if not exists .
* And then restart the kitty terminal and enjoy ... 
You can change any things in the kitty terminal i have use fish as the default shell you can change it in kitty.conf file 
for changing default shell on kitty terminal : 
* open the kitty.conf in your desire text editor 
* search for term "shell"
* replace /usr/bin/fish /usr/bin/zsh or /usr/bin/bash or any shell that you want to use as default on kitty terminal 

### Kitty terminal installation 
Visit this link 
* https://sw.kovidgoyal.net/kitty/binary/
### Documentation is here for more customization : 
* https://sw.kovidgoyal.net/kitty/overview/
