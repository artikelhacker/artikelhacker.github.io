---
layout: post
title: "2. Target Hacking Pertama!"
date: 2022-11-05 20:02:07 +0700
author: devishtank
is_series: true
series_title: "RedTeam"
---

Siapa yg sudah tdk sabar untuk melakukan hacking pertama kali!!!!!

Sabar dulu! Kalo target hacking nya ada di dunia internet, kemungkinan kita dapat dituntut karena melakukan perusakan. Karena hacking yg tdk merusak pun dapat dituduh sebagai perusakan. Contohnya hacker yg pernah menjadi Most Wanted Hacker di Amerika yaitu Kevin D. Mitnick. Karena setelah sebuah sistem diretas, yg punya sistem punya pekerjaan rumah yg sangat banyak untuk kembali mengamankan sistemnya. Daripada merusak sistem kepunyaan org lain, bukankah lebih baik meretas sistem sendiri?

Ini menjadi problematis karena sistem kita akan sengaja dibuat tdk aman lagi karena kita ingin berlatih untuk melakukan hacking. Apa ada cara yg lebih aman dari itu? Di sinilah kita diperkenalkan dengan virtualisasi. Pekerjaan network engineer dan DevOps jg menggunakan virtualisasi ini. Apa itu virtualisasi?

Virtualisasi adalah memindahkan mesin dgn segala kerumitannya untuk compile, install, deploy, maintenance, dll ke sebuah file. File tersebut dapat dibaca oleh software tertentu, sehingga dalam beberapa klik mouse, kita bisa memiliki sistem yg tdk aman di atas sistem yg relatif aman. Sebenarnya banyak yg terjadi di belakang layar agar virtualisasi ini dapat bekerja, tapi secara sederhananya seperti memindahkan mesin menjadi suatu file.

Ada beberapa produk virtualisasi ini, seperti Hyper-V, VMWare, VirtualBox, Docker, Kubernetes, dll. Dan seperti sejarah yg selalu terulang lagi, akhirnya merk2 ini sepakat untuk membuat standar file yg dibuat oleh developer menjadi Open Virtualization Format. Bahkan yg terbaru yaitu docker, kubernetes hanya berupa kumpulan file teks yg kemudian di deploy, tapi ini kelihatannya hanya berlaku untuk sistem operasi linux.

Berikut ini adalah contoh produk2 virtualisasi yg ada di pasaran :
- [VMWare](https://www.vmware.com)
- [VirtualBox](https://www.virtualbox.org)
- [Docker](https://www.docker.com)
- [Kubernetes](https://kubernetes.io)

Sesuaikan dgn yg dibutuhkan yah. Tapi mesin yg bisa diretas di mana? Ini adalah salah satunya :
- [VulnHub](https://www.vulnhub.com)

Kalo yg langsung dari web bisa diretas sebagai bahan latihan ada tdk? Tentu saja ada. Ikutilah CTF. Kebanyakan CTF menyediakan web di internet untuk bisa langsung diretas oleh banyak orang. Tapi kalau anda merasa sebagai pemula dan CTF terlalu sulit buat anda, bisa dicoba [HackTheBox](https://www.hackthebox.com). Silakan pilih target hacking pertama anda!!!!