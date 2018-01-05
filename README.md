# Playground for Vagrant + Hyper-V

## Insights

** Vagrant is available in Chocolatey, but I don't like that it automatically creates root folder
** Default credentials for VMs are `vagrant/vagrant`
** Hyper-V's *private* network interfaces are not visible to host, but are visible for VMs running at the same host. For host<->VM communication (including SSH) better use *internal*.
** CentOS does not have `ifconfig` :)