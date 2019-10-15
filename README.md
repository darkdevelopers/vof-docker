# vof-docker
Here we create a new Shop!
## TODO
### Install
#### Get Started
##### Overview
##### Installation
##### Configuration
Create ssh key 
Create config file:

```vim ~/.ssh/config```

and fill it with this content:

```
Host bitbucket.org-vof
  HostName bitbucket.org
  User git
  AddKeysToAgent yes
  #UseKeychain yes
  IdentityFile ~/.ssh/bitbucket.org
``` 
### SSH Key generate
```
ssh-keygen -t rsa -b 4096 -C "marco.schauer@darkdevelopers.de"
```
know send teh Content form the *.pub file to marco.schauer@darkdevelopers.de
###Laravl Packages
https://www.youtube.com/watch?v=H-euNqEKACA
### Debugbar 
https://github.com/barryvdh/laravel-debugbar
### DEPLOYROBOT
https://deploybot.com
### LARAVEL + eCommerce
https://github.com/aimeos/aimeos-laravel
### NAGIOS
Installation in docker or Host?
### Docker swarm...
### Documentation
https://laravel-news.com/larecipe-documentation-package
