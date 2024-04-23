

`Tugas ini merupakan tugas mata kuliah Konsep Jaringan yang dibimbing oleh Bpk. Dr. Ferry Astika Saputra,ST, M.Sc`

## Table of Contents
- [DNS Setup](#dns-setup)
- [Sending Email](#sending-email)



# DNS Setup Kelompok 3

`path: /etc/bind/...`

## named.conf
![](../assets/week9-1.png)

## named.conf.local
![](../assets/week9-2.png)

## named.conf.options
![](../assets/week9-3.png)

![](../assets/week9-4.png)

<hr>

`path: /var/lib/bind/...`

## db.kelompok3.local
![](../assets/week9-5.png)

## db.kelompok3.local.inv
![](../assets/week9-6.png)

<hr>

`path: /etc/...`

## resolv.conf
![](../assets/week9-7.png) 

## Setting connection profile

![](../assets/week9-8.png) 

# Sending Email

## To ourselves

1. Open _Evolution_ in the Menu.
2. Create a new account with the address is your ip. (192.168.3.10)
3. Setting your profile. (Full name, email, etc)
4. Open cmd and type `sudo telnet mail.kelompok3.local 25`
5. Send an email to yourself in the Evolution app.
6. Done.