# Initializing files
```
git clone https://github.com/derveror/cmi_manifests.git -b xiaomi-sm8250-devs-vic-qpr2 .repo/local_manifests
```
# Sync up
```
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
