# Jarkom-Modul-4-A16-2021
Lapres Praktikum Jarkom Modul 4
kelompok A16 : Deka Julian Arrizki  

## **Konten**
* [**Cara Pengerjaan**](#cara-pengerjaan)
* [**Hasil Akhir**](#hasil-akhir)
* [**Kendala**](#kendala)


## Cara Pengerjaan
### VLSM

| Simbol | Host | Jumlah | Netmask |
| ------------- | ------------- | ------------- | ------------- |
| A1 | BLUENO | 1001 | /22 |
| A2 | WATER7-FOOSHA | 2 | /30 |
| A3 | CIPHER | 701 | /22 |
| A4 | PUCCI-WATER7 | 2 | /30 |
| A5 | JIPANGU | 101 | /25 |
| A6 | CC | 2021 | /21 |
| A7 | GUANHAO-FOOSHA | 2 | /30 |
| A8 | JABRA | 521 | /22 |
| A9 | MAINGATE | 502 | /23 |
| A10 | JORGE | 13 | /28 |
| A11 | OIMO-GUANHAO | 2 | /30 |
| A12 | ENIESLOBBY | 252 | /24 |
| A13 | ELENA | 721 | /22 |
| A14 | DORIKI | 2 | /30 |
| A15 | FUKUROU | 2 | /30 |

* Pembagian IP
![vlsm](https://user-images.githubusercontent.com/55046884/143475930-6f3c7ec9-f14b-408e-9210-7c3f538775a1.png)
* Topology
![image](https://user-images.githubusercontent.com/55046884/143476263-19835ea5-9585-4676-89dc-475ff6a315af.png)
* Konfigurasi Routing  

Foosha  
```
10.7.16.0/22 via 10.7.27.150
10.7.27.0/25 via 10.7.27.150
10.7.0.0/21 via 10.7.27.150
10.7.20.0/22 via 10.7.27.154
10.7.24.0/23 via 10.7.27.154
10.7.27.128/28 via 10.7.27.154
10.7.26.0/24 via 10.7.27.154
10.7.12.0/22 via 10.7.27.154
10.7.27.164/30 via 10.7.27.154
10.7.27.156/30 via 10.7.27.154
10.7.27.144/30 via 10.7.27.150
```
Water7
```
0.0.0.0/0 via 10.7.27.149
10.7.27.0/25 via 10.7.27.146
10.7.0.0/21 via 10.7.27.146
```
Pucci
```
0.0.0.0/0 via 10.7.27.145
```
Guanhao
```
0.0.0.0/0 via 10.7.27.153
10.7.27.128/28 via 10.7.24.3
10.7.26.0/24 via 10.7.27.158
10.7.12.0/22 via 10.7.27.158
10.7.27.164/30 via 10.7.27.158
```
Oimo
```
0.0.0.0/0 via 10.7.27.157
10.7.12.0/22 via 10.7.26.3
```
Alabasta
```
0.0.0.0/0 via 10.7.24.1
```
Seastone
```
0.0.0.0/0 via 10.7.26.1
```
### CIDR
Soon
