# LineageOS 21 (Android 14) Local Manifest for Motorola `amogus` (SM6125)

Unified device tree for:
- `rav` (Moto G8 / Moto G Fast 2020)
- `sofia` (Moto G Power 2020)
- `sofiap` (Moto G Stylus / G Pro 2020)
- `sofiar` (Moto G8 Power)

## Usage

```bash
repo init -u https://github.com/LineageOS/android.git -b lineage-21.0 --git-lfs
git clone https://github.com/los-SM6125/local_manifests.git -b lineage-21 .repo/local_manifests
repo sync -c -j$(nproc)
source build/envsetup.sh
lunch lineage_amogus-userdebug
mka bacon
```
