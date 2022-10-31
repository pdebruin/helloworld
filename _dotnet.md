# Hello world prerequisite: DotNet

## install instructions ubuntu 22.04

Credits: https://learn.microsoft.com/en-us/dotnet/core/install/linux
```
sudo apt update
curl -sSL https://dot.net/v1/dotnet-install.sh | bash
echo 'export DOTNET_ROOT=$HOME/.dotnet' >> ~/.bashrc
echo 'export PATH=$PATH:$DOTNET_ROOT:$DOTNET_ROOT/tools' >> ~/.bashrc
```
