![Cherish](cherish.png)
# <b> <i> CherishOS | Built with </i>💖

 ### <b> <i> Getting Started: ###
To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).
---
<br>

### <b> Install the build packages : ###
### <b> Install JDK 8: ###

```bash
 sudo apt install openjdk-8-jdk
```

### <b> Tested on Ubuntu 16.04,16.10,17.04,18.04,18.10,19.04,21.04: ###

```bash
 sudo apt install bc bison build-essential ccache curl flex g++-multilib gcc-multilib git gnupg gperf imagemagick lib32ncurses5-dev lib32readline-dev lib32z1-dev liblz4-tool libncurses5-dev libsdl1.2-dev libssl-dev libwxgtk3.0-dev libxml2 libxml2-utils lzop pngcrush rsync schedtool squashfs-tools xsltproc zip zlib1g-dev
```
### <b> Tested on Ubuntu 20.04 ###
```bash 
     sudo apt install bc bison build-essential ccache curl flex g++-multilib gcc-multilib git gnupg gperf imagemagick lib32ncurses5-dev lib32readline-dev lib32z1-dev liblz4-tool libncurses5-dev libsdl1.2-dev libssl-dev libwxgtk3.0-gtk3-dev libxml2 libxml2-utils lzop pngcrush rsync schedtool squashfs-tools xsltproc zip zlib1g-dev
```

### <b> Sync our source ###
```bash
    repo init -u https://github.com/CherishOS/android_manifest.git -b twelve 
```
```bash
    repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### <b> Start build ###
```bash
        . build/envsetup.sh
        lunch cherish_$devicecodename-userdebug
        brunch cherish_$devicecodename-userdebug
```

### <b> Apply for Official Maintainership ###
---
You can apply for officialy maintaining the ROM for your device.

https://forms.gle/BWg1mPxHNv2W8eK79

---
</i>