# docker-ipsec
IPSec VPN server based on strongSwan

## Build

`docker buildx build --platform=linux/arm/v7,linux/amd64 -t mruettgers/ipsec .`

To push to the registry add `--push`.

