# Hello world prerequisite: Node

## install instructions ubuntu 22.04

Credits: https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-22-04
```
sudo apt update
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.2/install.sh | bash 
```
github.com/nvm-sh/nvm/releases
```
source .bashrc
nvm list-remote
nvm install v16.18.0 # Latest LTS
node -v 
```
Node must be 14+ for npx
