## Tutorial

```bash
opkg update
opkg install curl

curl -LO "$(curl -s https://api.github.com/repos/friendly-bits/geoip-shell/releases | grep -m1 -o 'https://github.com/friendly-bits/geoip-shell/releases/.*geoip-shell_.*\.ipk')"


opkg install geoip-shell_0.6.5-r1.ipk
geoip-shell configure -i br-lan

```

![Configuração](https://github.com/ramonalvesmodesto2/openwrt/blob/main/imagem.png)

Fonte <https://github.com/friendly-bits/geoip-shell/blob/main/OpenWrt/README.md>
