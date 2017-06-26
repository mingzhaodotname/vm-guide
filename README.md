# concepts
* virsh works with QEMU/KVM and with libvirt. 
* libvirtd is for KVM, and its data is in /var/lib/libvirt

# virt-manager
sudo virt-manager -c qemu:///system

Images are in /var/lib/libvirt/images/

# virsh

domain is the virtual machine instances.
* virsh uri
  * qemu:///system
* virsh list
* virsh 

# move KVM

https://serverfault.com/questions/434064/correct-way-to-move-kvm-vm

# networking, bridge

* http://goyalankit.com/blog/linux-bridge
* Anatomy of a Linux bridge: https://wiki.aalto.fi/download/attachments/70789083/linux_bridging_final.pdf
* bridge vs switch - basically the same, different words in different times.
* http://ebtables.netfilter.org/br_fw_ia/br_fw_ia.html
