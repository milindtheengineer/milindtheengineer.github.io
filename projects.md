---
layout: default
title: Milind's Projects
---

## Target Tech
### Grove

Grove is a custom virtualization service written to power Target's PaaS Target Application Platform, [TAP](https://www.youtube.com/watch?v=cnHfK4MZA2Y). Grove is used to run application containers embedded into a virtual machine image along with sidecars. A mini linux based distribution is specifically built to run these containers with less overhead, more performance and a much higher security. Currently this system replaced kubernetes on Target's datacenters running hundreds of clusters and is on route to replace on 1800+ edge clusters.

### VMaaS

This is a vertical scaling virtualization service that uses vmware's vsphere and ovirt. ManageIQ, an opensource upstream product of Redhat's cloudforms is used to build the orchestration layer with Target specific scripts embedded into it.

Grove and VMaaS together is resposible for more than 90 percent of workloads that get deployed on Target's private cloud
