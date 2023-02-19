# ectool-builder
Repo for building ectool binaries

git clone https://chromium.googlesource.com/chromiumos/platform/ec/ --depth 1 -b release-R100-14526.B-main
cd ec
BOARD=host make -j$(nproc) utils-host
