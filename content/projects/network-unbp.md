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


## Deskripsi
Infrastruktur jaringan yang handal dan efisien sangat penting untuk mendukung aktivitas akademik dan administrasi Universitas Bumi Persada. Namun, saat ini terdapat beberapa kendala seperti tiga gedung yang belum terhubung, melihat persentase penggunaan bandwidth harian, serta tidak adanya sistem pemantauan jaringan dan notifikasi otomatis. Oleh karena itu, penelitian ini bertujuan untuk mengukur penggunaan bandwidth secara real-time, mengkonfigurasi Zabbix agar dapat mengirimkan notifikasi status perangkat ke Telegram

## ⛏️ Alat dan Bahan
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

## 📐 Rangkaian
![](/projects/network-unbp/rancangan.jpg)
Pada gambar ini, diperlihatkan topologi jaringan yang terdiri dari tiga gedung (Gedung A, B, dan C) yang masing-masing terhubung melalui perangkat jaringan sectoral dan VPN. Setiap gedung memiliki Router dan perangkat jaringan lain yang akan dipantau menggunakan Zabbix. Server Zabbix ditempatkan di Gedung A dan berfungsi sebagai pusat pemantauan untuk seluruh jaringan yang ada di ketiga gedung.

## 📷︎ Dokumentasi
![](/projects/videotron/1.png) 
![](/projects/videotron/3.jpg)
![](/projects/videotron/4.jpg)
