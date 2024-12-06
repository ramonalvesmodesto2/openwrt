## Tutorial

```bash curl -LO "$(curl -s https://api.github.com/repos/friendly-bits/geoip-shell/releases | grep -m1 -o 'https://github.com/friendly-bits/geoip-shell/releases/.*geoip-shell_.*\.ipk')"


opkg install geoip-shell_0.6.5-r1.ipk
geoip-shell configure

```

![Configuração](https://github.dev/ramonalvesmodesto2/openwrt/tree/main/imagem.png)