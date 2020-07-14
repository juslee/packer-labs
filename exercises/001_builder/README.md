# First Packer Image

Try automatically install the following image Photon OS:

- iso: https://vmware.bintray.com/photon/3.0/Rev2/iso/Update1/photon-minimal-3.0-a0f216d.iso
- iso sha1 checksum: 090f5c98b6b8406dbc3ad856aa1ed23bad1ce5b0
- boot command: "<esc><wait>vmlinuz initrd=initrd.img root=/dev/ram0 ks=http://{{ .HTTPIP }}:{{ .HTTPPort }}/kickstart.json photon.media=cdrom<enter>"
- kickstart script: http/kickstart.json and http/photon-minimum.json
- root password: photon
