---
title: "Automatic Fan"
description: "Lebih simpel dan otomatis menyala!"
dateString: Dec 2021
draft: false
tags: ["Embedded System", "GitHub Actions"]
showToc: false
weight: 202
cover:
    image: "projects/automatic-fan/cover.jpg"
--- 
### 🔗 [GitHub](https://github.com/mfredlyvanleuwen/automatic-fan)

## Pendahuluan
Dalam kehidupan sehari-hari, kipas angin merupakan benda yang sangat umum digunakan, pada saat siang hari maupun malam hari, apalagi ketika cuaca yang sangat panas dan juga digunakan untuk beberapa keperluan lainnya. Seperti yang kita ketahui dengan berkembangnya teknologi saat ini maka kami ingin membuat kipas angin otomatis yang memudahkan pengguna tanpa harus membawa kipas yang pada umumnya besar dan ribet. 

{{< youtube id="G5txWpZQpME" autoplay="true" >}}



## Skema
![](/projects/automatic-fan/mckup.png)
- Sensor ultrasonik untuk mengukur jarak suatu benda yang berada di hadapan sensor tersebut. 
- WeMos D1 merupakan papan induk dari semua proses yang dilakukan.  
- Dht22 adalah mengecek suhu keadaan sekitar 
- Relay adalah sebagai pemutus atau penghubung aliran listrik pada rangkaian dengan kontrol berupa tegangan.
