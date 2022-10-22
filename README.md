# tugas python pertemuan ke 5

Repository ini digunakan untuk memenuhi Tugas Bahasa Pemrograman Pertemuan-5<br><br>
Nama : SUWANDA WIJAYA<br>
NIM : 312210028<br>
Kelas : TI.22.B1<br>

### DAFTAR ISI <br>
| No | Description | Link |
| ----- | ----- | ---- |
| 1 | Install Python| [Click Here](#Install-Python)|
| 2 | latihan 1 | [Click Here](#Latihan-1) |
| 3 | latihan 2 | [Click Here](#Latihan-2) |
| 4 | latihan 3 | [Click Here](#Latihan-3) |

## Install Python
1. download python pada web *python.org*

![download python](Screenshot/SS%201.png)

2. buka lalu centang bagian *add python to PATH* lalu klik install now
![install python](Screenshot/SS%202.png)
![install python2](Screenshot/SS%203.png)


3. Instalasi Selesai, klik close

![install success](Screenshot/SS%204.png)


## Latihan 1
* buat file latihan1.py

![buat file latihan1](Screenshot//SS%205.png)

* tulis kode seperti contoh

![sc latihan1](Screenshot/SS%206.png)
```python
#menampilkan tulisan 'Hello' di layar
print("Hello")
#menampilkan tulisan 'Saya sedang belajar python' 
print("Saya sedang belajar python")
```
* klik tombol run

![run python](Screenshot/SS%2012.png)

* maka akan muncul program yang dijalankan

![output latihan1](Screenshot/SS%209.png)
```
Hello
Saya sedang belajar python
```


## Latihan 2
* buat file latihan2.py

![buat file latihan2](Screenshot/SS%2013.png)

* tulis kode seperti contoh

![sc latihan2](Screenshot/SS%207.png)
``` python
# menjumlahkan dua bilangan menggunakan variabel a & b
a = 8
b = 6
print("Variabel a =",a)
print("Variabel b =",b)
print("hasil penjumlahan a + b =", a+b)
```


* klik tombol run

![run python](Screenshot/SS%2012.png)

* maka akan muncul program yang dijalankan

![output latihan2](Screenshot//SS%2010.png)

```
Variabel a = 8
Variabel b = 6
hasil penjumlahan a + b = 14
```


## Latihan 3
* buat file latihan3.py

![buat file latihan3](Screenshot/SS%2014.png)

* tulis kode seperti contoh

![sc latihan3](Screenshot/SS%208.png)

```python
#input nilai variabel
a = input("masukan nilai pertama: ")
b = input("masukan nilai kedua: ")
#cetak nilai variabel
print("variabel a = ", a)
print("variabel b = ", b)
#cetak hasil kedua operasi variabel dengan string format
print("Hasil Penggabungan {1} & {0} = ".format(a,b) + str(a)+str(b))
#konversi nilai variabel 
a = int(a);
b = int(b);
print("Hasil penjumlahan {1} + {0} = %d".format(a,b) %(a+b))
print("Hasil pembagian {1} / {0} = %d".format(a,b) %(a/b))
```
* klik tombol run

![run python](Screenshot/SS%2012.png)

* maka akan muncul program yang dijalankan, jangan lupa masukan angka

![output latihan3](Screenshot/SS%2011.png)
```
masukan nilai pertama: 6
masukan nilai kedua: 8
variabel a =  6
variabel b =  8
Hasil Penggabungan 8 & 6 = 68
Hasil penjumlahan 8 + 6 = 14
Hasil pembagian 8 / 6 = 0
```

TERIMAKASIH