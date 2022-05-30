# Liquid AOSP #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/Liquid-AOSP/manifest -b limerock

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch liquid_<codename>-userdebug

# Build the code
$ brunch <codename> 
```

### Credits ###

Big thanks to:

#### [• Pixel Experience](https://github.com/PixelExperience)
#### [• ArrowOS](https://github.com/ArrowOS)
#### [• LineageOS](https://github.com/LineageOS)
#### [• The Android Open Source Project (ofc)](https://source.android.com/)