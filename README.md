# Compilation

## Rocky Linux 9.4 (tested)

### How To
```
dnf install bzip2-devel bzip2-libs
cd /tmp
git clone https://github.com/NonneTrapuE/bsdiff.git
make
```

## Download
If you wish only download pre-build binaries, you can in Releases section.

# Using bsdiff & bspatch
You can use bsdiff and bspatch to create delta between older and newer binary file. Patch older binary with delta file can optimize thin storage.
Tested with binary file and tar file without encryption.

## Test with OpenTofu binary
```
cd /tmp
wget https://github.com/opentofu/opentofu/releases/download/v1.6.0/tofu_1.6.0_linux_amd64.zip
unzip tofu_1.6.0_linux_amd64.zip -d tofu_1.6.0/
wget https://github.com/opentofu/opentofu/releases/download/v1.7.2/tofu_1.7.2_linux_amd64.zip
unzip tofu_1.7.2_linux_amd64.zip -d tofu_1.7.2/
```
<not finished>




## Test with tar archive







