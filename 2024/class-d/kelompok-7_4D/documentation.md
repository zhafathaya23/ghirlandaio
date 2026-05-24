# CONNECT WIFI

```bash
iwctl
```
---
```bash
device list
```
#### Catatan : Untuk cek driver wifi setiap laptop
---
```bash
station (driver wifi) get-network
```
#### Catatan : untuk melihat jaringan yang tersedia
---
```bash
station (driver wifi) scan
```
#### Catatan : Untuk memindai jaringan yang ada
---
```bash
station {device wifi} connect "{nama wifi}"
```
```
exit
```
#### Catatan : Untuk menghubungkan ke jaringan yang sudah ditentukan
