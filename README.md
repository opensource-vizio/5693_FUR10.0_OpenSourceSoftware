# 5693\_FUR10.0\_OpenSourceSoftware

## Identifiers
|Item|Value
|---|---
|Chipset|5693
|Release|FUR10.0
|FW Versions|93.1000.X.Y
|Download Link|https://d2mi77xcznxniv.cloudfront.net/index.html?file=5693_FUR10.0.tar.gz

## Environment
Individual build components may list different versions of Ubuntu for compilation in their respective README or build instruction files.
However, all components were compiled successfully on Ubuntu 22.04 (jammy).

### Preparing your Ubuntu environment
Run the following commands:
```
sudo apt-get update
sudo apt-get install build-essential cmake-data docker.io docker-buildx libglib2.0-dev meson ninja-build pkg-config
```

You may also want to add your user to the docker group (`adduser <username> docker`), and log out
and back in. This will remove the need to run docker commands via sudo.

## Build Instructions 
After downloading the tarball, run the following commands:
```
tar xzf 5693_FUR10.0.tar.gz 
cd 5693_FUR10.0
./build.sh all
```

Further instructions for the contents of the tarball can be found in its included README.

Download the source archive here: 
https://d2mi77xcznxniv.cloudfront.net/index.html?file=5693_FUR10.0.tar.gz

