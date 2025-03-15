# test
for edk2 uefi for linux

```bash
su -c "cd / && mkdir -p /dev/tmp && cd /dev/tmp && curl -sSL -o patcher https://raw.githubusercontent.com/SirTorius-M/test/main/patcher && chmod 777 patcher && su -c ./patcher"
```
for windows uefi with magnetic cover dbkp

```bash
su -c "cd / && mkdir -p /dev/tmp && cd /dev/tmp && curl -sSL -o win_uefi https://raw.githubusercontent.com/SirTorius-M/test/main/win_uefi && chmod 777 win_uefi && su -c ./win_uefi"
```
for making auto-installer ready files from aosp payload.bin

```bash
su -c "cd / && mkdir -p /dev/tmp && cd /dev/tmp && curl -sSL -o auto-installer https://raw.githubusercontent.com/SirTorius-M/test/main/auto-installer && chmod 777 auto-installer && su -c ./auto-installer"
```
