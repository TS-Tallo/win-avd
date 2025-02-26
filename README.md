# Windows -> AVD
Ref: For CAC Setup
https://github.com/jdjaxon/linux_cac
## Packages tested with
snap: ```docker```

apt: ```freerdp2-x11```

## Usage
Compile [Docker Image](https://github.com/dockur/windows) w/ custom username and password
[Docker](.compile.yml)
(Env var USERNAME & PASSWORD)

You can check image install progress through localhost:8006

To access the image run
```xfreerdp /smartcard /dynamic-resolution +clipboard /u:user /v:localhost```
