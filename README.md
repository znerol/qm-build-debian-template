# Debian VM template generator for Proxmox VE

## Examples

```
qm-build-debian-template --release buster \
    --vmname buster-test \
    --vmid 9001 \
    --vmstorage local-lvm \
    --debootstrap-url http://deb.debian.org/debian \
    --sources.list-mirror http://deb.debian.org/debian \
    --extra-packages qemu-guest-agent,bash-completion \
    --login bob
```

## See also

* man build-openstack-debian-image
* https://pve.proxmox.com/pve-docs/pve-admin-guide.html#qm_cloud_init

## License

Released under the MIT License
