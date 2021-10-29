![Cherish](assets/cherish.png)
## <b> CherishOS | Built with </i>💖

### <b> <i> Getting Started: </i> ###
---
#### <b> To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).
---

### <b> <i> Install the build packages : </i>###
### <b> <i>Install JDK 8: </i> ###

```bash
 sudo apt install openjdk-8-jdk
```

### <b> <i>Tested on Ubuntu 16.04,16.10,17.04,18.04,18.10,19.04,21.04: </i>###

```bash
 sudo apt install bc bison build-essential ccache curl flex g++-multilib gcc-multilib git gnupg gperf imagemagick lib32ncurses5-dev lib32readline-dev lib32z1-dev liblz4-tool libncurses5-dev libsdl1.2-dev libssl-dev libwxgtk3.0-dev libxml2 libxml2-utils lzop pngcrush rsync schedtool squashfs-tools xsltproc zip zlib1g-dev
```
### <b> <i>Tested on Ubuntu 20.04 </i>###
```bash 
     sudo apt install bc bison build-essential ccache curl flex g++-multilib gcc-multilib git gnupg gperf imagemagick lib32ncurses5-dev lib32readline-dev lib32z1-dev liblz4-tool libncurses5-dev libsdl1.2-dev libssl-dev libwxgtk3.0-gtk3-dev libxml2 libxml2-utils lzop pngcrush rsync schedtool squashfs-tools xsltproc zip zlib1g-dev
```
![Sync](assets/source.png)
### <b> <i>Sync our source </i> ###
```bash
    repo init -u https://github.com/CherishOS/android_manifest.git -b twelve 
```
```bash
    repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### <i><b> Start build </i> ###
```bash
        . build/envsetup.sh
        lunch cherish_$devicecodename-userdebug
        brunch cherish_$devicecodename-userdebug
```
![credit](assets/credits.png)
 * <b><i>[**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**Nitrogen-Project**](https://github.com/nitrogen-project)
 * [**DotOS**](https://github.com/DotOS)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**ABC Rom**](https://github.com/ezio84)
 * [**Descendant**](https://github.com/Descendant-XI)</i>

### <b> <i>Apply for Official Maintainership </i> ###
---
<i>You can apply for officialy maintaining the ROM for your device.</i>

https://forms.gle/BWg1mPxHNv2W8eK79

---
</i>