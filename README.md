# **Old Shouko.dev's Rejoin Utility**
**Download File:**
```. <(curl https://raw.githubusercontent.com/nganneconfig/rejoinshouko/refs/heads/main/OldShouko.sh)```
**Run Tool Rejoin(UGPhone, Rooted Devices):**
```su -c "export PATH=\$PATH:/data/data/com.termux/files/usr/bin && export TERM=xterm-256color && cd /sdcard/Download && python Shouko_update.py"```
**For Termux Boot:**
```mkdir -p ~/.termux/boot
echo '#!/bin/bash
su -c "export PATH=\$PATH:/data/data/com.termux/files/usr/bin && export TERM=xterm-256color && cd /storage/emulated/0/Download && python ./Shouko_update.py" <<EOF
2
14
id game or private server here

1
time to kill tab
EOF' > ~/.termux/boot/abcd.sh```
**Termux:**
```https://f-droid.org/repo/com.termux_1022.apk```
**Termux Boot:**
```https://f-droid.org/repo/com.termux.boot_1000.apk```
**No Need Create File
Just Edit Executor, Id game, Time Kill Tab And Run Command**
