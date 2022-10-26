<h1 align="center">OpenWrt Time Sync 👋</h1>
Cara sinkronisasi waktu dan tanggal pada OpenWrt.

### Download Script

```sh
wget -O /usr/bin/waktu https://raw.githubusercontent.com/abmujib/waktu/master/waktu.sh && chmod +x /usr/bin/waktu
```

### Edit Script

```sh
nano /usr/bin/waktu
```

Silahkan rubah `bug/website` dengan bug/websites yang dapat anda akses dengan gratis.

### Reboot

```sh
reboot root /usr/bin/waktu
```
