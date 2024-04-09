# Sublime Text Debian 12

- ````sudo apt update && sudo apt upgrade -y````
- ````sudo apt install -y wget git````
- ````wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/sublimehq-archive.gpg > /dev/null````
- ````echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list````
- ````sudo apt update && sudo apt install -y sublime-text````
