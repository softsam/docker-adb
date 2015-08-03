# docker-adb
Docker image for ADB

## Built with
- latest debian
- openjdk 7
- Android SDK 24.3.3

## Running the adb devices command
    docker run --privileged -v /dev/bus/usb:/dev/bus/usb softsam/adb adb devices

