# docker-android-emulator

Dockerfile for android emulators

## Usage

Grab from docker cloud with: `docker pull narfman0/docker-android-emulator`

### Building locally

To build locally, use:

`docker build . -t narfman0/docker-android-emulator`

### Notes

* I am using this in conjunction with a jenkins node. I use
`adb connect <hostname>` before each job, so the node doesn't have to
know much about the emulator.

## License

Copyright 2018 Jon Robison

See LICENSE for details
