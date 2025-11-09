```bash
repo init -u https://github.com/Evolution-X/manifest -b bka --git-lfs
```
```bash
git clone -b EvolutionX-A16 https://github.com/skyres17/android_manifests .repo/local_manifests
```
```bash
git clone https://github.com/Android-Unofficial/android_vendor_lineage-priv_keys.git vendor/lineage-priv/keys
```
```bash
repo sync -c --force-sync --no-clone-bundle --no-tags -j$(nproc --all)
```
