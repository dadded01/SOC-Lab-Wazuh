
### Installation

First of all, make sure you don’t have any pending updates, so:
`sudo apt update && sudo apt upgrade -y`

Then I installed curl:
`sudo apt install curl`

Install the latest java jdk:
`sudo apt install default-jdk -y`

I installed Wazuh on the Ubuntu machine:
`curl -sO https://packages.wazuh.com/4.14/wazuh-install.sh`
`bash wazuh-install.sh -a`


Important to save:

- A backup of the internal users has been saved in the `/etc/wazuh-indexer/internalusers-backup` folder
- User: `admin`
  Password: `nqLglTl8Q0Hawj4DzrL0kJIspM1Qx77.`








