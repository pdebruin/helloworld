# Hello world in react

Note: For languages with lots of dependencies, I prefer to use disposable environments like a virtual machine, GitHub codespaces, or windows subsystem for linux. This helps when you want to clean your system, or use a different version.

## prerequisites
install instructions ubuntu 22.04

Credits: https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-22-04
```
sudo apt update
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.2/install.sh | bash 
```
github.com/nvm-sh/nvm/releases
```
source .bashrc
nvm list-remote
nvm install v16.18.0 Latest LTS
node -v 
```
Node must be 14+ for npx

## creating the app
```
npx create-react-app my-app
cd my-app
npm start
```