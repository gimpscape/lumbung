---
title: "Gitlab Runner With K8s Oleh M Rifki Affandi"
date: 2023-01-06T09:26:15+07:00
categories: "General"
creator: 
  name: "M. Rifki Affandi"
  gitlink: "https://www.linkedin.com/in/rifkiiaz"
tags: ["ILC 2022", "Slides"]
thumbnails: [assets/thumbnail.png]
images: [general/gitlab-runner-with-k8s-oleh-m-rifki-affandi/assets/thumbnail.png]
downloadfile: "assets/r507_17_rifki.pdf"
license: "CC BY-NC-ND 4.0"
---
Materi ini akan menjelaskan tentang memanfaatkan environment kubernetes sebagai gitlab runner. Karena Gitlab Runner yang disediakan oleh Gitlab (Shared) dibatasi 400 menit per bulan. ini akan menyusahkan jika memiliki banyak job dan memiilki banyak project.

Solusinya adalah menggunakan private shared runner atau private runner, dan salah satunya adalah gitlab.

pada topik kali ini akan membahas tentang cara integrasi antara k8s dan gitlab yang runner nya diinstall dengan memanfaatkan helm sebagai sumber nya.