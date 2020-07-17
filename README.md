[![Docker Hub](http://dockeri.co/image/javydekoning/hashcat)](https://hub.docker.com/r/javydekoning/hashcat/)

[![Docker Hub](https://images.microbadger.com/badges/version/javydekoning/hashcat.svg)](https://microbadger.com/images/javydekoning/hashcat)

[![Docker Hub](https://images.microbadger.com/badges/image/javydekoning/hashcat.svg)](https://microbadger.com/images/javydekoning/hashcat)

[Hashcat](https://hashcat.net/hashcat/) with hashcat utils on Ubuntu 18.04 OpenCL for Nvidia GPUs (`:latest`).

## cuda

```
nvidia-docker run javydekoning/hashcat:cuda hashcat -b
```

## opencl

```
nvidia-docker run javydekoning/hashcat:opencl hashcat -b
```
