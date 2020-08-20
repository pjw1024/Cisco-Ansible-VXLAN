# Cisco-Ansible-VXLAN
Sample Ansible files and results for Cisco VXLAN EVPN

This project contains my 2019 revisions (hacks) to Ansible playbook code I found online at:

https://github.com/datacenter/Ansible-NXOS

and 

https://github.com/mtarking/cisco-nxos-ansible-vxlan-evpn

This project is to share my working versions of the Ansible templates. 

The sample_results folder contains a sample leaf and a sample spine that the templates built. 
(I was running with a single Nexus 9000 virtual switch on a Mac -- and the other leaf or spine 
configurations should be very similar.)

For comparison / validation, the MS-VXLAN-Final folder contains copies of configurations built in dCloud 
by DCNM for VXLAN EVPN Multi-site. The dCloud project goal was rather simplistic (hey, demo!) so the configs
are rather limited as to features. 

