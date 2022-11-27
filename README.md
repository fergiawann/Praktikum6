# Praktikum6
## Fergiawan Satrio Bagaskoro
### Latihan 1
di latihan 1 ini kita akan membuat daftar kontak menggunakan dictionary. pertama kita input terlebih dahulu
datanya, saya akan menginput 2 daftar kontak yaitu ari dan dina
```
a = {}
a = {'Ari': '081267888', 'Dina': '087677776'}
```

![Gambar1](ss_praktikum6/ss1.png)

#### Menampilkan Daftar Kontak
Untuk menampilkan kontak dari ari kita hanya perlu memanggil variabel dictionary dari ari dengan code seperti dibawah
```
print ('Kontak Ari Adalah : ', a['Ari'])
```

![Gambar2](ss_praktikum6/ss2.png)

#### Menambah kontak Baru
Disini kita akan menambahkan satu daftar kontak lagi yaitu riko dengan cara seperti dibawah
```
a['Riko'] = '087654544'
print (a)
```

![Gambar3](ss_praktikum6/ss3.png)

#### Merubah Nomor Kontak
kita juga bisa merubah nomor kontak yang lama dengan nomor yang baru, disini saya akan merubah nomor kontak dari
dina dengan nomor kontak yang baru dengan cara seperti dibawah
```
print('Nomor Kontak Dina Saat Ini : ', a['Dina'])
a['Dina'] = '088999776'
print (a)
```

![Gambar4](ss_praktikum6/ss4.png)
#### Menampilkan Semua Nama
disini kita akan menampilkan hanya nama dari semua daftar kontak yang ada dengan cara dibawah
```
print ('Daftar Nama Kontak')
print (a.keys())
```

![Gambar5](ss_praktikum6/ss5.png)
#### Menampilkan Semua Nomor Kontak
selanjutnya kita hanya akan menampilkan semua nomor kontak yang ada dengan cara seperti dibawah
```
print ('Daftar Nomor Kontak')
print (a.values())
```

![Gambar6](ss_praktikum6/ss6.png)
#### Menampilkan Daftar Nama Dan Nomor Kontak 
lalu sekarang kita akan menampilkan keduanya yaitu nama dan nomor kontak dengan cara
```
print ('Daftar Semua Kontak')
print (a.items())
```

![Gambar7](ss_praktikum6/ss7.png)

#### Menghapus Daftar Kontak
kita juga bisa menghapus salah satu dari daftar kontak yang ada. disini saya akan menghapus daftar kontak dari dina
dengan cara seperti dibawah
```
print (a.items())
del a['Dina']
print (a.items())
```

![Gambar8](ss_praktikum6/ss8.png)

### Modul Praktikum
Di modul praktikum ini kita akan membuat daftar nilai mahasiswa dan menu tampilan pilihan berupa : (Lihat Data, Tambah Data, Ubah Data, Hapus Data, Cari Data, dan Keluar)
Jika kita tidak menginput data apapun maka tampilannya akan seperti ini

![Gambar9](ss_praktikum6/ss9.png)

Maka kita akan menambahkan data mahasiswanya dengan mengetik huruf 'T' seperti dibawah

![Gambar10](ss_praktikum6/ss10.png)

kita juga bisa menghapus data yang telah kita input dengan mengetik huruf 'H' seperti dibawah

![Gambar11](ss_praktikum6/ss11.png)

setelah selesai maka kita akan memilih opsi Keluar dengan mengitik huruf 'K' untuk menghentikan programnya

![Gambar12](ss_praktikum6/ss12.png)

### Flowchart
![Gambar13](ss_praktikum6/ss13.png)

**Deskripsi**
1. Saat run program akan menampilkan tampilan menu pilihan
2. Pilih menu
3. Jika memilih menu (L)ihat maka output akan menampilkan tidak ada data karena belum menginput data atau menampilkan
    data mahasiswa jika sudah menginput data mahasiswa
3. Jika memilih menu (T)AMBAH DATA maka input data mahasiswa
4. Jika memilih menu (U)BAH DATA maka akan menginput NIM, Tugas, UTS, UAS untuk merubah data yang sebelumnya telah di input
5. Jika memilih menu (H)APUS DATA maka input NIM data yang ingin di hapus
6. Jika memilih menu (C)ARI DATA maka input NIM untuk mencari data mahasiswa yang ingin dicari
7. Jika memilih menu (K)eluar maka program akan berhenti (BREAK)
8. Selesai


