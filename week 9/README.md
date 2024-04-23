

`Tugas ini merupakan tugas mata kuliah Konsep Jaringan yang dibimbing oleh Bpk. Dr. Ferry Astika Saputra,ST, M.Sc`

## Table of Contents
- [NTP Client](#installing-ntp-client)
- [Apache-FM](#install-apache-fm)
- [PHP 8.2](#install-php-8.2)
- [MariaDB](#install-mariadb)
- [Email System](#email-system)
- [Dovecot Server](#install-dovecot-server)
- [Final Check](#last-check)





# Installing NTP Client

Lakukan instalasi paket layanan sinkronisasi waktu

![](../assets/week5-1.png)

Pastikan konfigurasi timezone ke Asia/Jakarta

![](../assets/week5-2.png)

Melakukan konfigurasi Real Time Clock (RTC) untuk merefer ke UTC (Coordinated Universal Time)


![](../assets/week5-3.png)

Mengaktifkan NTP Client untuk sinkronisasi waktu

![](../assets/week5-4.png)

Menyunting file timesyncd.conf untuk mengarah ke NTP server terdekat untuk mendapatkan waktu 
delay terpendek. Biasanya setiap organisasi atau negara mempunyai NTP Server sendiri

![](../assets/week5-6.png)

![](../assets/week5-5.png)

Restart layanan sinkronisasi waktu dan pastikan layanan berjalan dengan benar

![](../assets/week5-7.png)


# Install Apache-FM

Installing Apache2

![](../assets/week5-8.png)

Konfigurasi Apache2

`nano /etc/apache2/conf-enabled/security.conf`

`line 12 : change`

`ServerTokens Prod`

<br>

`nano vi /etc/apache2/mods-enabled/dir.conf`

`add file name that it can access only with directory's name`

`DirectoryIndex index.html index.htm`

<br>

`nano /etc/apache2/apache2.conf`

`line 70 : add to specify server name`

`ServerName www.kelompok3.com`

<br>

`nano /etc/apache2/sites-enabled/000-default.conf`

`line 11 : change to webmaster's email`

`ServerAdmin webmaster@kelompok3.com`

`systemctl reload apache2`

![](../assets/week5-9.png)

Test ke web browser

![](../assets/week5-10.png)


# Install PHP 8.2

![](../assets/week5-11.png)

![](../assets/week5-12.png)

![](../assets/week5-13.png)

# Install PHP-FM

![](../assets/week5-14.png)

![](../assets/week5-15.png)

![](../assets/week5-16.png)

# Install MariaDB

![](../assets/week5-17.png)

![](../assets/week5-18.png)

# Email System

![](../assets/week5-19.png)

![](../assets/week5-20.png)

![](../assets/week5-21.png)

# Install Dovecot Server

![](../assets/week5-22.png)

![](../assets/week5-23.png)

## Last Check

![](../assets/week5-24.png)

![](../assets/week5-25.png)
