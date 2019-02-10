# my note

```bash
cd /tmp
git clone https://github.com/Scratch3Lab/thonny
cd /tmp/thonny/packaging/mac
# read https://github.com/Scratch3Lab/thonny/blob/master/packaging/mac/readme_build.txt
# download python 3.7.2: https://www.python.org/downloads/release/python-372/  macOS 64-bit installer
bash create_base_bundle.sh
# run create_dist_bundle.sh comment codesign
bash create_dist_bundle.sh
# ok
```

