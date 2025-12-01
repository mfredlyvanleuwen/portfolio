---
title: "Monitoring & Instalasi Network Infrastruktur Universitas Bumi Persada"
description: "Project Based, Merupakan project yang bekerja sama langsung dengan Rektor Universitas Bumi Persada meliputi instalasi, monitoring, notifikasi perangkat, dan vpn di ketiga gedung"
dateString: Lhokseumawe, Des 2024
draft: false
tags: ["Project Team"]
showToc: false
weight: 201
cover:
    image: "projects/network-unbp/unbp_cover.png"
--- 


### Deskripsi
Infrastruktur jaringan yang handal dan efisien sangat penting untuk mendukung aktivitas akademik dan administrasi Universitas Bumi Persada. Namun, saat ini terdapat beberapa kendala seperti tiga gedung yang belum terhubung, melihat persentase penggunaan bandwidth harian, serta tidak adanya sistem pemantauan jaringan dan notifikasi otomatis. Oleh karena itu, penelitian ini bertujuan untuk mengukur penggunaan bandwidth secara real-time, mengkonfigurasi Zabbix agar dapat mengirimkan notifikasi status perangkat ke Telegram

## 🤝😎 Our Team
<div align="center">

<table>
  <tr>
    <td align="center" width="200">
      <img src="/projects/network-unbp/fred.jpeg" alt="Foto 1" width="120" style="border-radius:50%;">
      <br><br>
      <b>M. Fredly Vanleuwen</b><br>
      <i>Teknologi Rekayasa Komputer Jaringan</i>
    </td>
    <td align="center" width="200">
      <img src="/projects/network-unbp/jar.jpeg" alt="Foto 2" width="120" style="border-radius:50%;">
      <br><br>
      <b>Fajar Permadi</b><br>
      <i>Teknologi Rekayasa Jaringan Telekomunikasi</i>
    </td>
  </tr>
</table>

</div>

### ⛏️ Alat dan Bahan
- Laptop
- Mikrotik RB750Gr3
- Kabel UTP
- Crimping
- Switch manageable
- Dedicated Internet(Ip statis)
- Zabbix
- Server
- TP Link
- Tang Gunting
- open vpn

### 📐 Rancangan Topologi
![](/projects/network-unbp/rancangan.png)
Pada gambar ini, diperlihatkan topologi jaringan yang terdiri dari tiga gedung (Gedung A, B, dan C) yang masing-masing terhubung melalui perangkat jaringan sectoral dan VPN. Setiap gedung memiliki Router dan perangkat jaringan lain yang akan dipantau menggunakan Zabbix. Server Zabbix ditempatkan di Gedung A dan berfungsi sebagai pusat pemantauan untuk seluruh jaringan yang ada di ketiga gedung.

### 🏢 3 Gedung yang akan di instalasi dan monitoring
***
#### Gedung A
![](/projects/network-unbp/gedungA.png)
***
#### Gedung B
![](/projects/network-unbp/gedungB.png)
***
#### Gedung C 
![](/projects/network-unbp/gedungC.png)



## 📡 Implementasi VPN (site-to-site)
Implementasi VPN Site-to-Site dirancang untuk menyatukan jaringan dari tiga gedung utama Universitas Bumi Persada ke dalam satu sistem yang aman dan terenkripsi menggunakan protokol L2TP/IPSec. Dalam sistem ini, Gedung A berperan sebagai server VPN dengan IP Publik statis. Sementara itu, Gedung B dan Gedung C sebagai klien VPN yang akan terhubung ke Gedung A melalui koneksi L2TP/IPSec.
<p align="center">
  <img src="/projects/network-unbp/vpn.PNG" alt="Gambar 3.1" width="350">
</p>

<p align="center"><em>Mikrotik integrasi dengan openvpn</em></p>

## 📊 Implementasi Zabbix
Zabbix sebagai sistem monitoring untuk infrastruktur jaringan antar gedung di Universitas Bumi Persada. zabbix dapat memonitoring CPU, Uptime, downtime, latency, ping dan banyak lagi.


## 📷︎ Dokumentasi
![](/projects/videotron/1.png) 
![](/projects/videotron/3.jpg)
![](/projects/videotron/4.jpg)
