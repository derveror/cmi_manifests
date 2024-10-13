# Initializing files
```
git clone https://github.com/derveror/local_manifest.git -b sm8250-devs .repo/local_manifests
```
# Sync up
```
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
