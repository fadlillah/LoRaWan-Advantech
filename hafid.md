---
title: WarisAlHafidz | WEB Scratch
description: Rapid Web Development dengan Yii2 - Overview
disableTableOfContents: true
---

Di coretan kali ini dan beberapa coretan lain kedepannya saya akan mencoba untuk menuangkan apa yang sudah saya dapat dari hasil belajar saya tentang framework Yii2. Berikut hasil ahir dari apa yand sudah saya pelajari tentang framework yang satu ini:

1. [Instalasi Yii-2](https://www.yiiframework.com/doc/guide/2.0/en/start-installation#installing-from-composer): Instaasi Yii2 basic-app dengan composer *[[PART 1]](yii2-rapid-development-part-1.md)*

   - [Basic Setup Gii](https://www.yiiframework.com/doc/guide/2.0/en/start-gii): Seting IP yang diizinkan dan ENV
   - Uji coba Gii dengan basic tamplate
   
2. [Instalasi AdminLTE](https://github.com/dmstr/yii2-adminlte-asset): Instalasi Template AdminLTE dan Setup Layout

    - [Setup Layout](https://github.com/dmstr/yii2-adminlte-asset#quick-start): Setup dengan `web.php` atau dengan overwrite file langsung
    - [Setup Gii Template](https://github.com/dmstr/yii2-adminlte-asset#template-for-gii-crud-generator): Setup AdminLTE untuk Gii
    - Uji coba Gii dengan AdminLTE Template
    
3. [Instalasi Ajax CRUD](https://github.com/johnitvn/yii2-ajaxcrud): Ajax CRUD Gii untuk tampilan DataTable lebih baik

   - [Setup Ajax CRUD](https://github.com/johnitvn/yii2-ajaxcrud#usage): Setup Gii untuk load module ajax crud
   - Uji coba Gii degnan Ajax Crud
   
4. [Instalasi yii2-admin](https://github.com/mdmsoft/yii2-admin): GUI Manager untuk RBAC (Role Base Access Control)

   - [Setup RBAC](https://github.com/mdmsoft/yii2-admin/blob/master/docs/guide/configuration.md#basic-configuration): Setup RBAC, Menu Migration, URL yang diizinkan, dll
   - Integrasi RBAC menu dengan AdminLTE Template

## Screenshoot Hasil Akhir

Dari 4 hal diatas, berikut hasil ahir yang saya dapatkan dan juga bisa teman-teman dapatkan:

- Halaman Login

![Halaman Login](img/login-page.png)

- Halaman Utama

![Halaman Utama](img/main-page.png)

- Ajax CRUD

![Ajax CRUD](img/ajax-crud.png)

- RBAC Route, Menu, Permission, Assignment, etc

![Route](img/rbac-route.png)

![Menu](img/rbac-menu.png)

![Permission](img/rbac-permission.png)

![Assigment](img/rbac-assignment.png)

## Requirements

Sebelum melanjutkan ke Part1, pastikan temen-temen sudah menyiapkan beberapa kebutuhan berikut

- Web Server (bisa pakai Nginx atau Apache)
- PHP >7.1
- Database Server (bebas, disini saya pakai mariadb10)

Jika kebutuhan diatas sudah disiapkan semua, temen-temen bisa lanjut ke coretan saya berikutnya di [Instalasi Yii-2 [ PART 1 ]](yii2-rapid-development-part-1.md)

**Semoga Bermanfaat :)**
