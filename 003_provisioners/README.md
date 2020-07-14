# 001_builder

The code below doesn't work:

```
      "iso_url": "http://releases.ubuntu.com/20.04/ubuntu-20.04-live-server-amd64.iso",
      "iso_checksum": "file:http://releases.ubuntu.com/20.04/MD5SUMS",
      "boot_command": [
        "<enter><enter><f6><esc><wait> ",
        "autoinstall ds=nocloud-net;s=http://{{ .HTTPIP }}:{{ .HTTPPort }}/",
        "<enter>"
      ]
```
