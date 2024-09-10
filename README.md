# vagrant-setup-multiple-serverUbuntu
Vagrantfile to set up four Ubuntu servers using Vagrant. Configures each server with VirtualBox provider and networking options. For Ubuntu 18.04 LTS (bionic64), can be adapted for 20.04 LTS (focal64). Includes a sample configuration for server1 with public network setup.

```
 #server1.vm.network "private_network", ip: "192.168.56.101"
 server1.vm.network "public_network", bridge: "wlp2s0"
```
wlp2s0 is my laptop network adapter.
