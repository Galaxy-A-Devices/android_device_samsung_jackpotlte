# OrangeFox Recovery Project for the Samsung Galaxy A8

### How to build ###

```bash
# Create dirs
$ mkdir ofox; cd ofox

# Init repo
$ repo init --depth=1 -u https://gitlab.com/OrangeFox/Manifest.git -b fox_9.0

# Clone jackpot2lte repo
$ git clone https://github.com/Galaxy-A-Devices/android_device_samsung_jackpotlte -b fox-9.0 device/samsung/jackpotlte

# Sync
$ repo sync --no-repo-verify -c --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune -j`nproc`

# Build
$ chmod +x build_ofox.sh ; ./build_ofox.sh
```

## Credits
* Astrako: For build_ofox.sh file
* DevKingsTeam: For the tree
