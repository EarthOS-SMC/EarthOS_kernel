# EarthOS-kernel
EarthOS kernel source code.
This is a part of EarthOS; the build system uses this repository to build the kernel.

## Building from source

Clone this repository using this command:

`git clone https://github.com/EarthOS-SMC/EarthOS-kernel`

Then, go to the source code directory:

`cd EarthOS-kernel`

Before the build process, you need to clone the PowerSlash compiler too:

`chmod +x sync.sh && ./sync.sh`

To build the kernel,

`./build.sh`


The binary will be saved in the `image` file.
