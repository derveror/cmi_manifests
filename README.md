# Initializing files
```
git clone https://github.com/derveror/cmi_manifests.git -b Luffitys .repo/local_manifests
```
# Sync up
```
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
