# Praktikum 1: Install dan Berkenalan dengan GNU/Linux

![linux](img/linux.png)

## Outline

- [Install GNU/Linux (Dual Boot).](##Install GNU/Linux (Dual Boot))
- [Berkenalan dengan GNU/Linux.](##Berkenalan dengan GNU/Linux)
- [Challenge.](##Challenge)

## Install GNU/Linux (Dual Boot)

#### Persiapan

Persiapkan terlebih dahulu bahan-bahan berikut:

1. Rufus: https://rufus.ie/
2. Ubuntu 18.04: https://ubuntu.com/download/desktop
3. Flashdisk minimal 4GB.

#### Panduan Instalasi

Panduan lengkap Dual Boot Linux dan Windows dapat dilihat di sini:

1. Linuxsec: https://www.linuxsec.org/2018/05/tutorial-dual-boot-windows-10-dan.html
2. Itsfoss: https://itsfoss.com/install-ubuntu-1404-dual-boot-mode-windows-8-81-uefi/

#### Tahapan Instalasi

1. Buat bootable ubuntu di flashdisk menggunakan Rufus.
2. Booting laptop melalui flashdisk.
3. Install Linux.
4. Buat 2 partisi: `root` dan `swap`.
   1. Ukuran `swap` sesuai dengan RAM.
   2. Ukuran `root` semuanya atau sisanya.
5. Selesai.

## Berkenalan dengan GNU/Linux

#### Teori

1. Apa itu Linux?
2. Apa itu Distro atau Distribusi?
3. Apa perbedaan `su` dan `sudo`?
4. Apa perbedaan `GUI` (Graphic User Interface) dan `CLI` (Command Line Interface)?

#### Praktikum

**1. Login dan Logout via GUI (Graphic User Interface).**

1. Login via GUI.
   1. Masukan `username` dan `password`.
2. Logout via GUI
   1. Klik `Logout`.

**2. Login dan Logout via CLI (Command Line Interface).**

1. Login via CLI.
   1. tekan `ctrl + alt + f1` - `ctrl + alt + f6`
   2. masukan `username` dan `password`.
2. Logout via CLI.
   1. Tulis `exit`.
   2. tekan `ctrl + alt + f7`.

**3. Perintah Dasar Terminal.**

1. Membuka terminal.
   1. tekan tombol `ctrl + alt + t`.
2. Berubah dari user biasa ke root.
   1. `sudo su`
3. Mengubah password user.
   1. `sudo passwd nama-user`
4. Mematikan laptop atau perangkat.
   1. `sudo poweroff`
   2. `sudo shutdown -h now`
5. Merestart laptop atau perangkat.
   1. `sudo reboot`
   2. `sudo shutdown -r now`

## Challenge

1. Apa itu Linux? Apa perbedaan dengan Ubuntu?
2. Tuliskan perintah untuk shutdown laptop pukul 12:00.
3. Tuliskan perintah untuk mengubah password user.
4. Apa itu partisi SWAP? Mengapa harus ada Partisi SWAP?
5. Apa evaluasi praktikum pertama? apa masukan dan saran?