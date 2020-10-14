# Desabilitar o secure boot na bios

# rodar:

sudo apt-get install aptitude && 
sudo aptitude update && 
sudo aptitude upgrade && 
sudo aptitude remove virtualbox && 
sudo aptitude install virtualbox && 
sudo aptitude install linux-headers-3.5.0-17-generic && 
sudo aptitude remove virtualbox-dkms && 
sudo aptitude install virtualbox-dkms && 
sudo /etc/init.d/virtualbox start && 
sudo usermod -aG vboxuser youruser &&
sudo reboot
