# Automated Provisioning of OpenShift 4.3 on VMware

This repository contains a set of playbooks to help facilitate the deployment of OpenShift 4.3 on VMware.

## Specific Automations

* Creation of all SRV, A and PTR records in IdM
* Deployment of an httpd server to host installation artifacts
* Deployment of HAProxy and applicable configuration
* Deployment of dhcpd and applicable fixed host entries (static assignment)
* Uploading RHCOS OVA template
* Deployment and configuration of RHCOS VMs on VMware
* Ordered starting (i.e. installation) of VMs