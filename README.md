# Packer CentOS 7

Customised version of [https://github.com/russmckendrick/packer-centos7](https://github.com/russmckendrick/packer-centos7) 
because it is easier to copy someone else's work than to start from scratch. Thanks Russ!

The created CentOS 7 VMWare virtual machine is customised towards my personal needs. I have no ambition of 

Differences to the upstream repository are:
* I don't use VirtualBox so I dropped it.
* Added a script to install Docker and Docker-Compose.
* Simpler partitioning scheme. 

```
packer build CentOS_7.json
```

Markus Juenemann, June 2020
