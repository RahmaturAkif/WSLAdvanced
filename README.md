https://rair.dev/wireguard-windows-multiple-simultaneous-tunnels/
https://gist.github.com/AdroitAdorKhan/9a8765ece290fef55e3eac446dd5996f


REG ADD HKEY_LOCAL_MACHINE\SOFTWARE\Wireguard  /v "MultipleSimultaneousTunnels" /t REG_DWORD /d 1

# WSLAdvanced
wireguard /installtunnelservice "C:\Program Files\Wireguard\Data\Configurations\us4-wg-finevpn.conf.dpapi
