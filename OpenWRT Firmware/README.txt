Use the LuCI Pre-Install for ease of setup. So use all the "Firmware OpenWrt Install" and don't use the SNAPSHOT Version.
Note older SSH require an extra command.
ssh root@192.168.8.1 -o HostKeyAlgorithms=+ssh-rsa -o PubkeyAcceptedAlgorithms=+ssh-rsa

MESH setup installation tutorial:
https://www.youtube.com/watch?v=fl1TXlQakxg
Use command below to install "relayd" & "luci-proto-relay"
opkg install luci-proto-relay

Firmware OpenWrt Install / Upgrade URL → comes with GUI / LuCI pre-installed, ready to go
Firmware OpenWrt snapshot Install / Upgrade URL → :!: No GUI / LuCI pre-installed; LuCI needs to be installed manually :!: