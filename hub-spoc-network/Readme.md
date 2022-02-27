# Network Peering Demo 

Deploy Two SPOC and One Hub Network, where Network#1 has Windows Server VM and Network#2 Has Ubuntu Server VM. This template would just deploy the Network, Storage and VMs. You still need to setup Peering between Hub and Spoc.

> Objective of this template is to reduce time taken by demo, much of the steps you need to do manually.

## The Resources deployed by this template:

Resource  | Name | Type | Description
----------|------|------|------------
1 | `Generated Name`  | Storage Account | Storage for Both the VM Disk and diagnostic
2 | MyHub | Virtual Network | The `Hub` Virtual Network with an extra subnet for `Azure Bastion`.
3 | MyVNet1 | Virtual Network | The `SPOC` Virtual Network with one subnet and One Windows VM.
4 | MyVNet2 | Virtial Network | The `SPOC` Virtual Network with one subnet and One Ubuntu VM.




