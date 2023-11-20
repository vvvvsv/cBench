
## To build

add the following to `/etc/apt/sources.list`
```shell
deb http://ports.ubuntu.com/ubuntu-ports/ xenial main universe
deb-src http://ports.ubuntu.com/ubuntu-ports/ xenial main universe
```
Then
```shell
sudo apt-get update && sudo apt-get install libesd0-dev
```
