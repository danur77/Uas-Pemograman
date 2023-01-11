# Uas-Pemograman
# UAS
## Nama  : Danang Nurcahyo
## NIM   : 312210004
## Kelas : TI.22.A1
### Package dan module

![Screenshot (718)](https://user-images.githubusercontent.com/115686359/210766307-7c0963ba-ea6b-4a3c-8e6c-36b0a571366c.png)

Sudah dibuat Package dan Module seperti diatas

![Screenshot (705)](https://user-images.githubusercontent.com/115686359/210766516-ec0a6c72-4384-4cc1-ac3a-e1c6393f7aa9.png)

```daftar_nilai.py``` Berisi Modul Untuk:

*tambah_data

*ubah_data

*hapus_data

*cari_data

```view_nilai.py``` Berisi Modul Untuk:

*cetak_daftar_nilai

*cetak_hasil_pencarian

```input_nilai.py``` Berisi Modul Untuk:

*input_data(yang meminta pengguna masukkan data)

```main.py``` Berisi Program Utama

*Memanggil semua menu yang yang ada

1. Kemudian saya tlah menyamtukan syntax yang nanti akan menghasilkan semua modul dari ```daftar_nilai``` yang diantaranya adalah (tambah data,ubah data,lihat data,hapus data,dan cari data)

```

from view.input_nilai import *
data={}
class daftarnilai():
    def tambah_data(self):
        tambah_nama = nama()
        tambah_nim = nim()
        tambah_tugas = tugas()
        tambah_uts = uts()
        tambah_uas = uas()
        tambah_akhir = akhir()
        data[tambah_nama]= tambah_nim,tambah_tugas,tambah_uts,tambah_uas,tambah_akhir

    def ubah_data(self):
        ubah_nama = nama()
        if ubah_nama in data.keys():
           
            tambah_nim = nim()
            tambah_tugas = tugas()
            tambah_uts = uts()
            tambah_uas = uas()
            tambah_akhir = akhir()
            data[ubah_nama]= tambah_nim,tambah_tugas,tambah_uts,tambah_uas,tambah_akhir
        else:
            print('data tidak ditemukan !!!')

    def hapus_data(self):
        hapus_nama = nama()
        if hapus_nama in data.keys():
            del data[hapus_nama]
            print('data berhasil di hapus')
        else:
            print('data tidak ditemukan !!!')

    def keluar(self):
    
```     

### Output Tambah_data:

![Screenshot 2023-01-11 145910](https://user-images.githubusercontent.com/115677839/211757242-4778b733-26a5-41a8-9831-bd857d30ee7b.png)


### Output Daftar_nilai:
![Screenshot 2023-01-11 145946](https://user-images.githubusercontent.com/115677839/211757390-8a64d809-b058-4751-8279-fce3ee5deb5e.png)

### Output Ubah_data:

![Screenshot 2023-01-11 150304](https://user-images.githubusercontent.com/115677839/211757499-60205a5b-4066-4ced-a569-81a7ddb85e80.png)


### Output Cari_data:
![Screenshot 2023-01-11 150337](https://user-images.githubusercontent.com/115677839/211757601-3a1f299c-0c1d-45ae-8482-4abb3f872b28.png)


### Output Hapus_data:
![image](https://user-images.githubusercontent.com/115677839/211757813-ec24a3a7-b828-4765-b3ca-11088233d5b1.png)



## finished

