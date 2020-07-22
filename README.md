# mtk-watch #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/mtk-watch/manifest -b t-alps-q0.mp1-V9.107

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

$ python vendor/mediatek/proprietary/scripts/releasetools/split_build_helper.py full_k39tv1_64_bsp

```
