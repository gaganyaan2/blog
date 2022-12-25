# Linux encryption tools


### cyrfs

- https://www.cryfs.org/


### sirikali (UI tool)

- https://mhogomchungu.github.io/sirikali/

Create volume > cryfs > Vloume path(This is where excerpted data will be stored) > Volume name(eg. test-cryfs) > Password > Key > Create

```bash
df -hT 

#view mount directory. Copy your data to mount directory

[home@home ~]$ df -hT
Filesystem                                Type        Size  Used Avail Use% Mounted on
devtmpfs                                  devtmpfs     32G     0   32G   0% /dev
tmpfs                                     tmpfs        32G  345M   31G   2% /dev/shm
tmpfs                                     tmpfs        13G  2.1M   13G   1% /run
/dev/mapper/fedora_localhost--live-root00 ext4        184G  174G  1.8G  99% /
tmpfs                                     tmpfs        32G   32M   32G   1% /tmp
/dev/nvme0n1p2                            ext4        974M  210M  698M  24% /boot
/dev/nvme0n1p1                            vfat        599M   14M  585M   3% /boot/efi
tmpfs                                     tmpfs       6.3G  188K  6.3G   1% /run/user/1000
cryfs@/home/home/cryfs-test               fuse.cryfs  1.8G   32K  1.8G   1% /home/home/.SiriKali/cryfs-test
```

Options = Select algo for encryption

Onedrive client: https://github.com/abraunegg/onedrive/