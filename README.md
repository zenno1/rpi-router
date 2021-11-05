# Raspberry PI Router
This repository has essential information to set Raspberry pi as a router.

We need:
* Rasberry pi
* Linux distro installed e.g. raspbian
* Two ethernet ports
* Switch or router
* At least one computer in computer network

![rpi_network](https://user-images.githubusercontent.com/92365329/140471482-a4a105ec-bb71-427e-8319-4f610117c9cf.png)

## Get updated packages and upgrade
```
sudo apt-get update
sudo apt-get upgrade
```

## Install bridge utils
```
sudo apt-get install bridge-utils
```

# Edit rc.local
```
sudo nano /etc/rc.local
```

# Restart 
```
sudo reboot now
```
