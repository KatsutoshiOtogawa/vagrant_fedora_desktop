# vagrant_fedora_desktop
opensuse Destop in vagrant envrionment. if you need suse development environment, you use this.

now this fedora version is 31

## How to use

You install Windows Remote Desktop Client in advance.

You execute below commands.

```
$ git clone https://github.com/KatsutoshiOtogawa/vagrant_fedora_desktop.git
$ cd vagrant_fedora_desktop
$ vagrant up
```

After Vagrant get box,and you wait 40,50 minitues, vagrant install this Desktop environment.

After installed, execute below command.

```
$ vagrant rdp
```

You launching Windows Remote Desktop client,and you type [password is vagrant user].
You will access fedora via Remote Desktop!
