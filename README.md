# Custom Kernel Manifest

Manifest for building kernel with custom toolchain and CLO prebuilts.

## Components
- **Kernel Source**: `papel-palyground/android_Kernel_xiaomi_sm8450` (Branch: `lineage-23`)
- **App Clang**: AOSP `r584948` (Custom revision)
- **Build Tools**: CLO (Tag: `KERNEL.PLATFORM.1.0.r1-19500-kernel.0` / Misc revisions)

## How to Build

### 1. Initialize Repo
```bash
repo init -u https://github.com/papel-palyground/Kernel_manifest.git -b lineage-23 
```

### 2. Sync Source
```bash
repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```
