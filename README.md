# Ubuntu Core Workshop

Creating a self-healing Flask application

## Getting started

Download the virtual machine for your hypervisor of choice:

* VirtualBox: https://cloud.ilabt.imec.be/index.php/s/4AYaQSJeYDEdYxL
* VMWare: https://cloud.ilabt.imec.be/index.php/s/BS4n37bsJTsGERi

Run the VM and check if you have network connectivity. If you do, run the following commands in a termninal.

```bash
git pull https://github.com/idlab-discover/flaska.git
code flaska
```

This will open Visual Studio Code in the project assigment repository. Now you're ready to get started!

## Contents

* [Build your first IoT snap](./first-snap.md)
* [Publish your first snap to the Snap Store](./publish-snap.md)
* [Install Ubuntu Core and manage snaps and Docker containers](./install-ubuntu-core.md)

## Extra

When moving Ubuntu Core into production, you will want to create your own Ubuntu Core image, with your own snaps and configuration pre-loaded. To get started, see [Build your own Ubuntu Core image](https://ubuntu.com/core/docs/build-an-image).
