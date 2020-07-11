# install-nodejs12-on-ubuntu18
install-nodejs12-on-ubuntu18

### 1. Update system
```
sudo apt update
sudo apt -y upgrade
```

### 2. Add nodejs to APT Repository
```
sudo apt update
sudo apt -y install curl dirmngr apt-transport-https lsb-release ca-certificates
curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
```
### 3. Install nodejs 12 
```
sudo apt -y install nodejs

node --version
v12.10.0

npm --version
6.10.3
```

### Done.
