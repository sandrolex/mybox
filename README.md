# mybox

## tools
* nvim / vim
* curl / wget / jq 
* exa / bat / jwt
* docker / dive / skopeo / buildah
* snyk / trivy
* nmap 
* java8 / java11 / maven
* nvm / npm 
* nvim + config
* tmux + config
* gcloud
* awscli

```
sudo apt-get update -y
sudo apt-get install -y vim curl wget jq docker.io nmap bat openjdk-8-jdk openjdk-11-jdk maven golang-go neovim tmux unzip

sudo ln -s /usr/bin/batcat /usr/bin/bat

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash

sudo apt-get install wget apt-transport-https gnupg lsb-release -y
wget -qO - https://aquasecurity.github.io/trivy-repo/deb/public.key | sudo apt-key add -
echo deb https://aquasecurity.github.io/trivy-repo/deb $(lsb_release -sc) main | sudo tee -a /etc/apt/sources.list.d/trivy.list
sudo apt-get update -y
sudo apt-get install trivy -y

npm install -g snyk

wget https://github.com/wagoodman/dive/releases/download/v0.9.2/dive_0.9.2_linux_amd64.deb
sudo apt install ./dive_0.9.2_linux_amd64.deb
rm dive_0.9.2_linux_amd64.deb

curl -fsSL https://raw.githubusercontent.com/fishworks/gofish/main/scripts/install.sh | bash
gofish init
gofish install jwt-cli

curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
unzip awscliv2.zip
sudo ./aws/install
rm -rf aws*





```
