#  Kernel Manifest

Manifest for building kernel with custom toolchain and CLO prebuilts.

### 1. Initialize Repo
```bash
repo init -u https://github.com/papel-palyground/Kernel_manifest.git -b lineage-23.2 
```

### 2. Sync Source
```bash
repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```
