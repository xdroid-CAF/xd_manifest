![XD](https://github.com/xyz-prjkt/xyz_assets/raw/main/xd_manifest.png)
# xdroidCAF | rev1.5 RedWhite
a android based on CAF with Minimalist UI Design.

### Requirements
- Around 500GB disk space.
- Around 18GB RAM running Linux.

### Sync our source ###
```bash
        repo init -u https://github.com/xdroid-CAF/xd_manifest -b eleven
```
```bash
        repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build our source ###
```bash
        . build/envsetup.sh
        lunch xdroid_$devicecodename-userdebug
        make xd -j$(nproc --all)
```

### Credits ###
 * [**CAF**](https://source.codeaurora.org)
 * [**ConquerOS**](https://github.com/ConquerOS)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**DotOS**](https://github.com/DotOS)
 * [**Project404**](https://github.com/P-404)
 * [**POSP**](https://github.com/PotatoProject)
