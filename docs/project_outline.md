# Project

This project seeks to create a repository of tools necessary for building scale-able open-balena systems locally and in the cloud.

## Outline

### OpenBalena


### Packer

#### Vagrant Box

note: the open balena project is currently using vagrant as part of their development so first look at maintaining compatibility with that Vagrantfile.

Using the packer templates create open-balena host images for vagrant on Docker

#### Amazon Machine Image

Using the packer templates create open-balena host images for vagrant on Virtualbox

#### Kubernetes deployment

Stretch goal, create a kube centric deployment of open-balena

#### etc....

additional areas of exploration in the service mesh paradigm

### Terraform

#### AWS account

Using Terraform create the aws infrastructure for the packer CICD build pipeline.