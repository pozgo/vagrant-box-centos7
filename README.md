### Vagrant Box with CentOS 7
This repository is building CentOS 7 base image with some packages already installed. Auto-update wil run every time you build new image.


#### Build
To build image run:  
`packer build packer.json`


#### Push
To push to atlas:  
`packer push -name name/centos7 packer.json`
