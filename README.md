# letsencrypt-postfix-dovecot-installer
# WARNING: THIS SCRIPT DOES NOT WORK YET AT ALL
Goal: To make a Lua script that installs and configures both Postfix and dovecot with a Let's Encrypt Certbot certificate

## Requirements
1. A Ubuntu 16.04 system

2. This requires that you have a registered domain, sub or otherwise, 
this can be obtained for free from multiple sources including https://noip.com 
A valid certificate can't be issued unless you have a domain.

3. That certbot has been installed and has been verified,
for more information, please visit this site: https://certbot.eff.org/

## Install instruction
The individual lines can be copy pasted in to a terminal:

```
sudo apt-get update 
sudo apt-get install -y lua5.2 git 
git clone https://github.com/LarsHLunde/letsencrypt-postfix-dovecot-installer.git 
cd letsencrypt-postfix-dovecot-installer 
sudo lua installer.lua
```
or this huge line may be copy pasted in to the terminal:
```
sudo apt-get update && sudo apt-get install -y lua5.2 git && git clone https://github.com/LarsHLunde/letsencrypt-postfix-dovecot-installer.git && cd letsencrypt-postfix-dovecot-installer && sudo lua installer.lua
```

## Changelog
Date | Description | Version | State
--- | --- | --- | ---
16.11.2017 | Initial commit | v0.1 | None functional
