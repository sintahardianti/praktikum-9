# Praktikum 9

## Nama : Sinta Hardianti Wijaya

## NIM : 312210342

## Kelas : TI. 22. A3

# Contoh dan Penjelasan Modul Praktikum 13

### 1. Berikut adalah fungsi yang mengubah suhu dari derajat derajat Kelvin menjadi derajat Fahrenheit. Karena nol derajat derajat Kelvin sedingin yang didapat, fungsi tersebut ditebus jika melihat suhu negatif.

![exception](https://user-images.githubusercontent.com/115516473/208232159-2b286b13-53a9-4d40-b83e-efa40f909c42.png)

### Ketika kode di atas dijalankan, muncul Exception yang bernama Traceback... ```AssertionError``` artinya terjadi error pada pernyataan assert.

### 2. Contoh ini untuk membuka file, menulis konten di file dan keluar dengan lancar karena tidak ada masalah sama sekali.

![prak 9](https://user-images.githubusercontent.com/115516473/208232774-4146e137-d051-47c8-8432-8e1f8936e12a.png)

### Hasilnya :

```Written content in the file successfully```

Hasilnya seperti ini karena else akan dijalankan ketika try adalah True

### 3. Contoh ini mencoba membuka file di mana Anda tidak memiliki izin menulis, sehingga menimbulkan pengecualian.

![prak 9-2](https://user-images.githubusercontent.com/115516473/208233322-41ef7a58-a485-4632-99a5-29a10950fae6.png)

### Mengapa hasilnya error? 

### r adalah read - Membuka file untuk membaca, error jika file tidak ada. Disini ingin membaca file bukan menulis maka dibawahnya ```fh = open("testfile", "r")``` tambahkan ```print(fh.readline())``` dan fh.write dihapus. Setelah dijalankan, try dan else ditampilkan.

### 4. 
