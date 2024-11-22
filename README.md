solidrun-imx6-yocto
===================
```bash
wget https://solid-run-images.sos-de-fra-1.exo.io/IMX6/meta-solidrun-arm-imx6/2024-07-05_ab67695/core-image-weston-sdk-imx6qdlcubox.wic.gz
gzip -dc core-image-weston-sdk-imx6qdlcubox.wic.gz | dd of=/dev/sdX bs=4M conv=fsync
```

[Documentation/imx6/debian-12_sr1.md at bsp · SolidRun/Documentation](https://github.com/SolidRun/Documentation/blob/bsp/imx6/debian-12_sr1.md)
