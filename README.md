# AuthySSH

curl -O 'https://raw.githubusercontent.com/authy/authy-ssh/master/authy-ssh'
bash authy-ssh install /usr/local/bin
sudo /usr/local/bin/authy-ssh enable `whoami` <your-email> <your-country-code> <your-cellphone>
service ssh restart
sudo authy-ssh enable (Enable by User)
