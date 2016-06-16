### Vagrant Box with CentOS 7
This repository is building CentOS 7 base image with some packages already installed. Auto-update wil run every time you build new image.


#### Build
To build image run:  
`packer build packer.json`

#### Build only one provider (virtualbox or parallels)
Available options are:  
  - parallels-iso  
  - virtualbox-iso  

`packer build -only=parallels-iso packer.json`

#### Push
To push to atlas:  
`packer push -name name/centos7 packer.json`
