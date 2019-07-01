# Packer-DPO
Packer-recipe for bootstrapping a node for Deployment, Provisioning and Orchestration using MaaS and Ansible

## Pre-requisites
- *Packer* to be able to bootstrap. Verified to work with version 1.4.2
- *VirtualBox* to spin up the Virtual Machine. Verified to work with version 5.0.6
- *OS Images* for the Operating Systems to be deployable.

## Technologies used
- *Packer* for Bootstrapping the Virtual Machine.
- *MaaS* for Deployment to Bare-metal and Virtual Environment.
- *Ansible* for Provisioning and Orchestration.

# Usage
Make the pre-requisites available on your workstation. Packer and VirtualBox must be installed. OS Images must be available on designated location. Modify the configuration file to suit your needs, the initial configuration file will only give you a basic infrastructure.
