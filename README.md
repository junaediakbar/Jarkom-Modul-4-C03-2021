# Jarkom-Modul-4-C03-2021

Dibuat dengan sepenuh hati demi memenuhi Praktikum Jaringan Komputer Modul 4 Tahun 2021

.  
Junaedi Akbar. (05111940000041)  
Zydhan Linnar Putra (05111940000118)  
M.Fajri Davyza Chaniago (05111940000180)  
.

## Praktikum Modul 4 (📅 21 - 23 November 2021)

## Topologi Soal

![Topologi Soal](pict%201.jpg)

## 💻 VLSM (Variable Length Subnet Masking)

![VLSM](pict%202.jpg)

### Jumlah Alamat IP

Subnet, jumlah IP untuk mendapatkan netmask dari tiap subnet ditunjukkan oleh tabel berikut
| Subnet | Jumlah IP | Netmask |
| :--- | :---: | ---: |
| ------------- | ------------- | ------------- |
| A1 | 721 | /22 |
| A2 | 252 | /24 |
| A3 | 13 | /28 |
| A4 | 502 | /23 |
| A5 | 521 | /22 |
| A6 | 2 | /30 |
| A7 | 2 | /30 |
| A8 | 2 | /30 |
| A9 | 701 | /22 |
| A10 | 2 | /30 |
| A11 | 2021 | /21 |
| A12 | 101 | /25 |
| A13 | 1001 | /22 |
| Total | 5841 | /19 |

### Pengaturan Konfigurasi IP

#### Pada Foosha

1. Mengarah Cloud  
   192.185.72.13 subnet 255.255.255.252
2. Mengarah Blueno  
   192.185.16.1 subnet 255.255.252.0
3. Mengarah Server Doriki  
   192.185.0.33 subnet 255.255.255.240
4. Mengarah Guanhao  
   192.185.0.5 subnet 255.255.255.252
5. Mengarah Water7  
   192.186.0.9 subnet 255.255.255.252

#### Pada Water7

1. Mengarah Foosha  
   192.185.0.10 subnet 255.255.255.252
2. Mengarah Cipher  
   192.185.12.1 subnet 255.255.255.0
3. Mengarah Pucci  
   192.185.0.13 subnet 255.255.255.252

#### Pada Pucci

1. Mengarah Water7  
   192.185.0.14 subnet 255.255.255.252
2. Mengarah Jipangu  
   192.185.0.129 subnet 255.255.255.128
3. Mengarah Courtyard dan Calmbelt  
   192.185.24.1 subnet 255.255.248.0

#### Pada Guanhao

1. Mengarah Foosha  
   192.185.0.6 subnet 255.255.255.252
2. Mengarah Jabra  
   192.185.8.1 subnet 255.255.252.0
3. Mengarah Alabasta  
   192.185.2.1 subnet 255.255.254.0
4. Mengarah OIMO  
   192.185.0.1 subnet 255.255.255.252

#### Pada Alabasta

1. Mengarah Guanhao  
   192.185.2.2 subnet 255.255.254.0
2. Mengarah Jorge  
   192.185.0.17 subnet 255.255.255.240

#### Pada OIMO

1. Mengarah Guanhao  
   192.185.0.2 subnet 255.255.255.252
2. Mengarah Server Fukurou  
   192.185.0.49 subnet 255.255.255.240
3. Mengarah Seastone  
   192.185.1.1 subnet 255.255.255.0

#### Pada Seastone

1. Mengarah OIMO  
   192.185.1.2 subnet 255.255.255.0
2. Mengarah Elena  
   192.185.4.1 subnet 255.255.252.0
