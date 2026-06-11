```bash
repo init --no-repo-verify --git-lfs -u https://github.com/ProjectInfinity-X/manifest -b 16 -g default,-mips,-darwin,-notdefault
```

```bash
repo sync -c --force-sync --no-clone-bundle --no-tags -j$(nproc --all)
```
