# firewalltask4
ufw on kali linux
objective- configure adn test basic firewall rules to allow or block traffic uding UFW on kali linux
Steps Performed
1.  Installed UFW- sudo apt update
   sudo apt install ufw -y
 
 Enabled UFW- sudo ufw enable

sudo ufw status numbered- for firewall status

sudo ufw deny 23 - block inbounded traffic on port 23

sudo ufw allow 22 - ssh port allow on port 22

sudo ufw status verbose - verfiy rules were applied

sudo ufw delete deny 23 -  Removed block rule to restore original state

sudo ufw disable - for disable ufw
