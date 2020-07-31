---
title: Vagrant and VirtualBox
author: Cumulus Networks
weight: 20
---
This section describes how to install and set up Cumulus VX within Vagrant and VirtualBox to create the two leaf and one spine topology shown below.

{{% vx/intro %}}

These steps were tested with VirtualBox version 6.1.12 and Vagrant version 2.2.9 on macOS version 10.14.6.

## Create and Configure the VMs

The following procedure creates leaf01, leaf02, and spine01 and the network connections between them. This section assumes a basic level of Vagrant, VirtualBox, and Linux experience.

### Download and Install the Software

1. Download and install {{<exlink url="https://www.virtualbox.org/wiki/Downloads" text="VirtualBox">}}.

2. Download and install {{<exlink url="https://www.vagrantup.com/downloads.html" text="Vagrant">}}.

### Create VMs and Network Connections

{{% vx/vagrant-setup %}}

## Log into the Switches

{{% vx/login-vagrant %}}

## Basic Switch Configuration

{{% vx/basic-config-vagrant %}}

## Verify Configuration

{{% vx/verify-config %}}

## Next Steps

{{% vx/next-steps %}}