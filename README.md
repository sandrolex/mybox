# mybox

## tools
* nvim / vim
* curl / wget 
* exa / bat
* docker / dive / skopeo / buildah
* snyk / trivy
* nmap 
* java8 / java11 / maven
* nvm / npm 

```
sudo apt-get update -y
sudo apt-get install -y vim curl wget docker.io nmap bat openjdk-8-jdk openjdk-11-jdk maven golang-go

sudo ln -s /usr/bin/batcat /usr/bin/bat

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash

sudo apt-get install wget apt-transport-https gnupg lsb-release -y
wget -qO - https://aquasecurity.github.io/trivy-repo/deb/public.key | sudo apt-key add -
echo deb https://aquasecurity.github.io/trivy-repo/deb $(lsb_release -sc) main | sudo tee -a /etc/apt/sources.list.d/trivy.list
sudo apt-get update -y
sudo apt-get install trivy -y



```
