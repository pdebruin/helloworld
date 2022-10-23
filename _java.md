# Hello world prerequisite: Java

## install instructions ubuntu 22.04

Credits: https://learn.microsoft.com/en-us/java/openjdk/install
```
sudo apt update
ubuntu_release=`lsb_release -rs`
wget https://packages.microsoft.com/config/ubuntu/${ubuntu_release}/packages-microsoft-prod.deb -O packages-microsoft-prod.deb
sudo dpkg -i packages-microsoft-prod.deb
sudo apt-get install apt-transport-https
sudo apt-get update
sudo apt-get install msopenjdk-17

export JAVA_HOME=/usr/lib/jvm/msopenjdk-17-amd64

java -version

# download maven
https://dlcdn.apache.org/maven/maven-3/3.8.6/binaries/apache-maven-3.8.6-bin.tar.gz

# extract
tar xzvf apache-maven-3.8.6-bin.tar.gz

export PATH=/usr/lib/jvm/apache-maven-3.8.6/bin:$PATH


```
