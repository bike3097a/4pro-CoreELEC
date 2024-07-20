# Build CoreELEC for Tencent 4Pro
CoreELEC is a 'Just enough OS' Linux distribution for running the award-winning [Kodi](https://kodi.tv) software on popular low-cost hardware. CoreELEC is a minor fork of [LibreELEC](https://libreelec.tv), it's built by the community for the community. [CoreELEC website](http://coreelec.org).  

## Remote keymap files
The remote keymap files has been packed into the image file. Unfortunately the numeric keys are not working with the virtual keyboard.

## Build instructions
1. Install the necessary packages (E.g Ubuntu 20.04 LTS user)
```yaml
sudo apt-get update -y
sudo apt-get install -y make gcc git texinfo gzip squashfs-tools
```

2. Clone the repository to the local. `git clone https://github.com/KryptonLee/e900v22c-CoreELEC.git`

3. Enter the `~/e900v22c-CoreELEC` root directory and run: `./build` to build CoreELEC.
