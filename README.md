# How to build

If you haven’t already, clone the BitBake repository:
```
git clone https://git.openembedded.org/bitbake
```

Using bitbake tool
```
./bitbake/bin/bitbake-setup --setting default registry \
'git://github.com/AdrienCorvasier/mima-yocto;protocol=https;branch=wrynose;rev=wrynose' \
init --non-interactive default mima distro/poky machine/raspberrypi4-64
```
