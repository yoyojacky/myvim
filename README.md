# myvim
This is my vim plugin, it can auto complete my typing.
## How to install
1. unzip vim.zip file to your home directory.
for example: my raspberry pi home directory	is /home/pi	
just unzip the archive package into this folder.
2. grant permisson to the vim folder:
```bash
sudo cp -Rvf /home/pi/myvim/vim/vim/.vim* /home/pi/
sudo chmod 777 -R /home/pi/.vim* 
```
# If you have error: ctaglist plugin not work properly.
Typing this command in you terminal:
```bash
sudo apt-get update 
sudo apt-get -y install exuberant-ctags
```
and then log off and log in again. or just execute `bash`
