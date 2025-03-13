使用前请自行拉取内核源码

```shell
repo init -u https://github.com/OnePlusOSS/kernel_manifest.git -b refs/heads/oneplus/sm8650 -m oneplus_ace3_pro_v.xml --depth=1 --repo-rev=v2.16
repo --trace sync -c -j$(nproc --all) --no-tags --fail-fast
```
