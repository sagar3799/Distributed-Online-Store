
# Webserver code
https://github.com/adhikansh1999/ds_webserver/tree/work

# Accessing web servers
webserver - http://13.59.136.130:5000/<br />
bacup_webserver - http://18.219.37.235:5000/


# Fault tolerant messages
node 'x' with 'ip' just died

# setup git on server via ssh
ssh-keygen -t ed25519 -C "your_email@example.com"
eval "$(ssh-agent -s)"
ssh-add /home/ubuntu/.ssh/id_ed25519

# copy key to clipboard
cat /home/ubuntu/.ssh/id_ed25519.pub

Instructions for Database servers
sudo apt update
sudo apt install mysql-server
sudo mysql_secure_installation
sudo mysql
 >CREATE USER 'user'@'localhost' IDENTIFIED BY 'password';
 >GRANT ALL PRIVILEGES ON *.* TO 'user'@'localhost' WITH GRANT OPTION;
 >FLUSH PRIVILEGES;
 >CREATE SCHEMA DSTRY; (To make one)
 >exit

mysql -u user -p
 >password
 >CREATE SCHEMA DSTRY; (To make one)
 >DROP SCHEMA DSTRY; (To delete one)

sudo apt install python3-pip
pip3 install -r requirements.txt
tmux
tmx attach-session -t server
tmux new -s server
About
Database Server part of our whole DS project

Resources
 Readme
Stars
 1 star
Watchers
 1 watching
Forks
 0 forks
Releases
No releases published
Packages
No packages published
Contributors 4
@ankit-bagde
ankit-bagde Ankit Bagde
@sanketRmeshram
sanketRmeshram Sanket Meshram
@berserker1
berserker1 Aaryan Bhagat
@adhikansh1999
adhikansh1999
Languages
Python
100.0%
Footer
© 2022 GitHub, Inc.
Footer navigation
Terms
