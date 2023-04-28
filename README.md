### Evolinx - Workflows

---

#### This repository includes following workflows

* Live ISO: amd64 + cli only

#### To be remembered

##### What does this distro use to boot the system ( bios / efi )
* ( EFI ): For efi we use systemd-boot with separate image that is flashed to the iso
* ( BIOS ): for bios we use syslinux
* Why no grub? Mainly because "Martin Valba" dosent like grub at all, though it exists in the repo for grub lovers out there.

##### User credentials in the iso for login?

* root : toor
* evolinx : evolinx
