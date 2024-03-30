# Ansible for Win 10 VM

This automation accompanies [this blog on the source](https://source.redhat.com/groups/public/sal_elrahal/my_blog/windows_10_vm_with_virtio_on_fedora).

First install pre-reqs with `ansible-galaxy collection install community.libvirt`.

Then, run the playbook with `ansible-playbook -K playbook.yaml`.
