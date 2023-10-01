# prometheus_demo
#### Prerequisite Instalation 

 - install docker on ubuntu
 - install nodejs on ubuntu
 
## 1.1 Install Docker

Docker instalation:

```
sudo apt-get update
```
```
sudo apt-get install \
    ca-certificates \
    curl \
    gnupg \
    lsb-release
```
```
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg
```
```
echo \
  "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu \
  $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
```
```
sudo apt-get update
```
```
sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose-plugin
```

## 1.2 Install nodeJs

```
sudo apt install nodejs
```
```
sudo apt install npm
```
Next: you can use each file in repo which has name that indicate what is it doing and go with its steps on 
