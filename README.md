# Raspberry Pi imager Built for Nvidea Jetson Xavier NX (ARM64)

This was built for the Nvidea Jetson Xavier NX directly from the [source](https://github.com/raspberrypi/rpi-imager) with no changes at all, the reason for the build is because I use this as my SD card/Drive imager all the time and wanted it on my Xavier NX so I built it from source and tested it to ensure it works as intended

To install 
```bash
wget https://github.com/CAProjects/rpi-imager-jetson-xavier-nx/releases/download/1.5/rpi-imager_1.5_xavier-nx_arm64.deb
sudo apt install ./rpi-imager*.deb
rm ./rpi-imager*.deb
```

Disable Telemetry (Optional)  
`rpi-imager --disable-telemetry`  
more information on telemetry can be found [here](https://github.com/raspberrypi/rpi-imager#telemetry)
