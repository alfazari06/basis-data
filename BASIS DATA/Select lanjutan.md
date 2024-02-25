# Tabel desc_mobil

# Select And

## Struktur Query
```mysql
select nama_kolom,nama_kolom from nama_tabel where nama_kolom="nilai_kolom 1" and nama_kolom='nilai_kolom 2'
```
## Contoh
```mysql
select warna,pemilik from mobil where warna="HITAM" and pemilik='Ibrahim'
```
### Hasil
**setelah kamu mengetikkan query diatas selanjutnya klik enter  maka akan muncul tampilan seperti yang di bawah ini yang berarti kamu telah berhasil:**

![alt text](https://github.com/alfazari06/basis-data/blob/main/ASETBASISDATA/h.select%20and.png?raw=true)

### Analisis
Perintah SQL di atas merupakan sebuah query yang digunakan untuk mengambil data dari tabel 'mobil'. Query tersebut memiliki dua kondisi pencarian, yaitu warna mobil yang harus sama dengan "HITAM" dan pemilik mobil yang harus sama dengan "Ibrahim". Dalam query tersebut, dipilih dua kolom yaitu 'warna' dan 'pemilik'. Jadi, hasil dari query tersebut akan menampilkan semua mobil dengan warna hitam yang dimiliki oleh seseorang dengan nama Ibrahim.
### Kesimpulan
Perintah SQL di atas merupakan sebuah query yang digunakan untuk mengambil data dari tabel 'mobil'. Query tersebut memiliki dua kondisi pencarian, yaitu warna mobil yang harus sama dengan "HITAM" dan pemilik mobil yang harus sama dengan "Ibrahim". Dalam query tersebut, dipilih dua kolom yaitu 'warna' dan 'pemilik'. Jadi, hasil dari query tersebut akan menampilkan semua mobil dengan warna hitam yang dimiliki oleh seseorang dengan nama Ibrahim.
# Select OR

## Struktur Query
```mysql
select nama_kolom,nama_kolom from nama_tabel where warna='nilai_kolom 1' or nama_kolom='nilai_kolom 2';
```
## Contoh
```mysql
select warna,pemilik from mobil where warna='HITAM' or pemilik='ibrahim';
```
### Hasil
**setelah kamu mengetikkan query diatas selanjutnya klik enter  maka akan muncul tampilan seperti yang di bawah ini yang berarti kamu telah berhasil:**

![alt text](https://github.com/alfazari06/basis-data/blob/main/ASETBASISDATA/h.select%20OR.png?raw=true)

### Analisis
1. Mengambil data mobil dengan warna "HITAM".
2. Mengambil data mobil yang dimiliki oleh seseorang dengan nama "Ibrahim". 

    Ketika salah satu kondisi atau kedua kondisi tersebut terpenuhi, data akan dipilih. Setelah itu, query tersebut memilih dua kolom, yaitu 'warna' dan 'pemilik', dari tabel 'mobil'. Jadi, hasil dari query tersebut akan menampilkan semua mobil dengan warna hitam dan semua mobil yang dimiliki oleh seseorang dengan nama "Ibrahim".
### Kesimpulan
Query MySQL di atas mengambil data dari tabel 'mobil' dengan dua kondisi pencarian:

1. Mobil dengan warna "HITAM".
2. Mobil yang dimiliki oleh seseorang dengan nama "Ibrahim".

    Kondisi-kondisi tersebut dipisahkan dengan operator OR, yang berarti data akan dipilih jika salah satu atau kedua kondisi terpenuhi. Setelah itu, query memilih dua kolom, yaitu 'warna' dan 'pemilik', dari tabel 'mobil'. Kesimpulannya, hasil dari query tersebut akan menampilkan semua mobil dengan warna hitam dan semua mobil yang dimiliki oleh seseorang dengan nama "Ibrahim".


# Select Between

## Struktur Query
```mysql
select * from nama_tabel where nama_kolom between Nilai_kolom 1 and nilai_kolom 2;
```
## Contoh
```mysql
select * from mobil where harga_rental between 100000 and 200000;
```
### Hasil
**setelah kamu mengetikkan query diatas selanjutnya klik enter  maka akan muncul tampilan seperti yang di bawah ini yang berarti kamu telah berhasil:**

![alt text](https://github.com/alfazari06/basis-data/blob/main/ASETBASISDATA/h.select%20between.png?raw=true)

### Analisis
Query MySQL di atas digunakan untuk mengambil data dari tabel 'mobil' dengan kondisi pencarian menggunakan klausa BETWEEN untuk kolom 'harga_rental'. Klausa BETWEEN digunakan untuk menentukan rentang nilai yang akan dicari.

1. SELECT *: Mengambil semua kolom dari tabel 'mobil'.
2. FROM mobil: Menentukan tabel yang akan diambil datanya, yaitu 'mobil'.
3. WHERE harga_rental BETWEEN 100000 AND 200000: Menentukan kondisi pencarian dimana harga_rental harus berada dalam rentang antara 100,000 dan 200,000.

Jadi, hasil dari query ini akan menampilkan semua data mobil yang memiliki harga rental di antara 100,000 dan 200,000.
### Kesimpulan
Query MySQL di atas mengambil semua data dari tabel 'mobil' dimana harga rental mobil berada dalam rentang antara 100,000 dan 200,000. Ini berarti query tersebut akan menghasilkan daftar semua mobil yang memiliki harga rental antara 100,000 dan 200,000.
# Select Not Between

## Struktur Query
```mysql
select * from nama_tabel where nama_kolom Not Between Nilai_kolom 1 and nilai_kolom 2;

```
## Contoh
```mysql
select * from mobil where harga_rental not between 100000 and 200000;
```
### Hasil
**setelah kamu mengetikkan query diatas selanjutnya klik enter  maka akan muncul tampilan seperti yang di bawah ini yang berarti kamu telah berhasil:**

![alt text](https://github.com/alfazari06/basis-data/blob/main/ASETBASISDATA/h.select%20not%20between.png?raw=true)

### Analisis
Query MySQL di atas digunakan untuk mengambil data dari tabel 'mobil' dengan kondisi pencarian menggunakan klausa NOT BETWEEN untuk kolom 'harga_rental'. Klausa NOT BETWEEN digunakan untuk mengecualikan rentang nilai yang akan dicari.

Analisis:

1. SELECT *: Mengambil semua kolom dari tabel 'mobil'.
2. FROM mobil: Menentukan tabel yang akan diambil datanya, yaitu 'mobil'.
3. WHERE harga_rental NOT BETWEEN 100000 AND 200000: Menentukan kondisi pencarian dimana harga_rental tidak berada dalam rentang antara 100,000 dan 200,000.

Jadi, hasil dari query ini akan menampilkan semua data mobil yang memiliki harga rental diluar rentang antara 100,000 dan 200,000.
### Kesimpulan
Query MySQL di atas digunakan untuk mengambil semua data dari tabel 'mobil' dimana harga rental mobil tidak berada dalam rentang antara 100,000 dan 200,000. Dengan kata lain, query tersebut akan menampilkan semua mobil yang memiliki harga rental di luar rentang tersebut.
# Select <=

## Struktur Query
```mysql
select * from nama_tabel where nama_kolom <=nilai_kolom 1;
```
## Contoh
```mysql
select * from mobil where harga_rental <=50000;
```
### Hasil
**setelah kamu mengetikkan query diatas selanjutnya klik enter  maka akan muncul tampilan seperti yang di bawah ini yang berarti kamu telah berhasil:**

![alt text](https://github.com/alfazari06/basis-data/blob/main/ASETBASISDATA/h.select%20lebih%20kecil.png?raw=true)

### Analisis
Query MySQL di atas digunakan untuk mengambil data dari tabel 'mobil' dengan kondisi pencarian dimana harga rental mobil kurang dari atau sama dengan 50,000.

Analisis:

1. SELECT *: Mengambil semua kolom dari tabel 'mobil'.
2. FROM mobil: Menentukan tabel yang akan diambil datanya, yaitu 'mobil'.
3. WHERE harga_rental <= 50000: Menentukan kondisi pencarian dimana harga_rental mobil harus kurang dari atau sama dengan 50,000.

Jadi, hasil dari query ini akan menampilkan semua data mobil yang memiliki harga rental kurang dari atau sama dengan 50,000.
### Kesimpulan
Query MySQL di atas digunakan untuk mengambil semua data dari tabel 'mobil' dimana harga rental mobil kurang dari atau sama dengan 50,000. Ini berarti query tersebut akan menghasilkan daftar semua mobil yang memiliki harga rental kurang dari atau sama dengan 50,000.

# Select >=

## Struktur Query
```mysql
select * from nama_tabel where nama_kolom >=nilai_kolom 1;
```
## Contoh
```mysql
select * from mobil where harga_rental >=50000;
```
### Hasil
**setelah kamu mengetikkan query diatas selanjutnya klik enter  maka akan muncul tampilan seperti yang di bawah ini yang berarti kamu telah berhasil:**

![alt text](https://github.com/alfazari06/basis-data/blob/main/ASETBASISDATA/h.select%20lebih%20besar.png?raw=true)

### Analisis
Query MySQL di atas digunakan untuk mengambil data dari tabel 'mobil' dengan kondisi pencarian dimana harga rental mobil lebih besar dari atau sama dengan 50,000.

Analisis:

1. SELECT *: Mengambil semua kolom dari tabel 'mobil'.
2. FROM mobil: Menentukan tabel yang akan diambil datanya, yaitu 'mobil'.
3. WHERE harga_rental >= 50000: Menentukan kondisi pencarian dimana harga_rental mobil harus lebih besar dari atau sama dengan 50,000.

Jadi, hasil dari query ini akan menampilkan semua data mobil yang memiliki harga rental lebih besar dari atau sama dengan 50,000.
### Kesimpulan
Query MySQL di atas digunakan untuk mengambil semua data dari tabel 'mobil' dimana harga rental mobil lebih besar dari atau sama dengan 50,000. Ini berarti query tersebut akan menghasilkan daftar semua mobil yang memiliki harga rental lebih besar dari atau sama dengan 50,000.

# Select <> atau !=
## Struktur Query
```mysql
select * from nama_tabel where nama_kolom <>nilai_kolom 1;
```
## Contoh 
```mysql
select * from mobil where harga_rental <>50000;
```

### Hasil
**setelah kamu mengetikkan query diatas selanjutnya klik enter  maka akan muncul tampilan seperti yang di bawah ini yang berarti kamu telah berhasil:**

![alt text](https://github.com/alfazari06/basis-data/blob/main/ASETBASISDATA/h.select%20lebih%20besar-kecil.png?raw=true)

### Analisis
Query MySQL di atas digunakan untuk mengambil data dari tabel 'mobil' dengan kondisi pencarian dimana harga rental mobil tidak sama dengan 50,000.

Analisis:

1. SELECT *: Mengambil semua kolom dari tabel 'mobil'.
2. FROM mobil: Menentukan tabel yang akan diambil datanya, yaitu 'mobil'.
3. WHERE harga_rental <> 50000: Menentukan kondisi pencarian dimana harga_rental mobil tidak sama dengan 50,000.

Jadi, hasil dari query ini akan menampilkan semua data mobil yang memiliki harga rental yang tidak sama dengan 50,000.
### Kesimpulan
Query MySQL di atas digunakan untuk mengambil semua data dari tabel 'mobil' dimana harga rental mobil tidak sama dengan 50,000. Ini berarti query tersebut akan menghasilkan daftar semua mobil yang memiliki harga rental yang berbeda dari 50,000.
 
# Select  IN
## Struktur Query
```mysql
 select * from nama_tabel where nama_kolom in ('nilai_kolom 2','nilai_kolom 1');
```
## Contoh
```mysql
 select * from mobil where warna in ('silver','merah');
```
### Hasil
**setelah kamu mengetikkan query diatas selanjutnya klik enter  maka akan muncul tampilan seperti yang di bawah ini yang berarti kamu telah berhasil:**

![alt text](https://github.com/alfazari06/basis-data/blob/main/ASETBASISDATA/h.select%20in.png?raw=true)

### Analisis
Query MySQL di atas digunakan untuk mengambil data dari tabel 'mobil' dengan kondisi pencarian dimana warna mobil adalah 'silver' atau 'merah'.

Analisis:

1. SELECT *: Mengambil semua kolom dari tabel 'mobil'.
2. FROM mobil: Menentukan tabel yang akan diambil datanya, yaitu 'mobil'.
3. WHERE warna IN ('silver', 'merah'): Menentukan kondisi pencarian dimana warna mobil harus 'silver' atau 'merah'.

Jadi, hasil dari query ini akan menampilkan semua data mobil yang memiliki warna 'silver' atau 'merah'.
### Kesimpulan
Query MySQL di atas digunakan untuk mengambil semua data dari tabel 'mobil' dimana warna mobil adalah 'silver' atau 'merah'. Ini berarti query tersebut akan menghasilkan daftar semua mobil yang memiliki warna 'silver' atau 'merah'.
# Select IN+AND

## Struktur Query
```mysql 
 select * from nama_tabel
     where nama_kolom in ('nilai_kolom 1', 'nilai_kolom 2')
     and nama_kolom =nilai_kolom;
```
## Contoh 
```mysql
 select * from mobil
     where warna in ('HIAM', 'SILVER')
     and harga_rental =50000;
```
### Hasil
**setelah kamu mengetikkan query diatas selanjutnya klik enter  maka akan muncul tampilan seperti yang di bawah ini yang berarti kamu telah berhasil:**

![alt text](https://github.com/alfazari06/basis-data/blob/main/ASETBASISDATA/h.select%20IN%2BAND.png?raw=true)

### Analisis
Query MySQL di atas digunakan untuk mengambil data dari tabel 'mobil' dengan dua kondisi pencarian:

1. Warna mobil harus 'HITAM' atau 'SILVER'.
2. Harga rental mobil harus sama dengan 50,000.

Analisis:

1. SELECT *: Mengambil semua kolom dari tabel 'mobil'.
2. FROM mobil: Menentukan tabel yang akan diambil datanya, yaitu 'mobil'.
3. WHERE warna IN ('HITAM', 'SILVER'): Menentukan kondisi pencarian dimana warna mobil harus 'HITAM' atau 'SILVER'.
4. AND harga_rental = 50000: Menentukan kondisi pencarian dimana harga rental mobil harus sama dengan 50,000.

Jadi, hasil dari query ini akan menampilkan semua data mobil yang memiliki warna 'HITAM' atau 'SILVER', dan harga rental mobil adalah 50,000.
### Kesimpulan
Query MySQL di atas digunakan untuk mengambil semua data dari tabel 'mobil' dimana warna mobil adalah 'HITAM' atau 'SILVER', dan harga rental mobil adalah 50,000. Ini berarti query tersebut akan menghasilkan daftar semua mobil yang memiliki warna 'HITAM' atau 'SILVER', dan harga rental mobil adalah 50,000.

# Select IN+OR
## Struktur Query
```mysql
 select * from nama_tabel
     where nama_kolom in ('nilai_kolom 1', 'nilai_kolom 2')
     or nama_kolom =nilai_kolom;
```
## Contoh 
```mysql
 select * from mobil
    where warna in ('HIAM', 'SILVER')
    or harga_rental =50000;
```
### Hasil
**setelah kamu mengetikkan query diatas selanjutnya klik enter  maka akan muncul tampilan seperti yang di bawah ini yang berarti kamu telah berhasil:**

![alt text](https://github.com/alfazari06/basis-data/blob/main/ASETBASISDATA/h.select%20IN%2BOR.png?raw=true)

### Analisis
Query MySQL di atas digunakan untuk mengambil data dari tabel 'mobil' dengan dua kondisi pencarian:

1. Warna mobil harus 'HITAM' atau 'SILVER'.
2. Harga rental mobil harus sama dengan 50,000.

Analisis:

1. SELECT *: Mengambil semua kolom dari tabel 'mobil'.
2. FROM mobil: Menentukan tabel yang akan diambil datanya, yaitu 'mobil'.
3. WHERE warna IN ('HITAM', 'SILVER'): Menentukan kondisi pencarian dimana warna mobil harus 'HITAM' atau 'SILVER'.
4. OR harga_rental = 50000: Menentukan kondisi pencarian dimana harga rental mobil harus sama dengan 50,000.

Jadi, hasil dari query ini akan menampilkan semua data mobil yang memiliki warna 'HITAM' atau 'SILVER', serta semua mobil yang memiliki harga rental 50,000.
### Kesimpulan
Query MySQL di atas digunakan untuk mengambil semua data dari tabel 'mobil' dimana warna mobil adalah 'HITAM' atau 'SILVER', atau harga rental mobil adalah 50,000. Ini berarti query tersebut akan menghasilkan daftar semua mobil yang memiliki warna 'HITAM' atau 'SILVER', serta semua mobil yang memiliki harga rental 50,000.
# Select IN+AND+OPERATOR
## Struktur Query
```mysql
select * from mobil
     where warna in ('hitam','silver')
     AND harga_rental > 50000;
```

```mysql
select * from mobil
     where warna in ('hitam','silver')
     AND harga_rental <100000;
```
## Contoh
1. 
```mysql
select * from mobil
     where warna in ('hitam','silver')
     AND harga_rental > 50000;
```

```mysql
select * from mobil
     where warna in ('hitam','silver')
     AND harga_rental <100000;
```

## Hasil
setelah kamu mengetikkan query diatas selanjutnya klik enter  maka akan muncul tampilan seperti yang di bawah ini yang berarti kamu telah berhasil:
contoh 1

![alt text](https://github.com/alfazari06/basis-data/blob/main/ASETBASISDATA/h.select%20in%2Band%2Boperator.png?raw=true)

contoh 2

![alt text](https://github.com/alfazari06/basis-data/blob/main/ASETBASISDATA/h.select%20in%2Band%2Boperator.2.png?raw=true)

## Analisis
Query MySQL pertama digunakan untuk mengambil data dari tabel 'mobil' dengan dua kondisi pencarian:

1. Warna mobil harus 'HITAM' atau 'SILVER'.
2. Harga rental mobil harus kurang dari 100,000.

Analisis:

1. SELECT *: Mengambil semua kolom dari tabel 'mobil'.
2. FROM mobil: Menentukan tabel yang akan diambil datanya, yaitu 'mobil'.
3. WHERE warna IN ('hitam', 'silver'): Menentukan kondisi pencarian dimana warna mobil harus 'hitam' atau 'silver'.
4. AND harga_rental < 100000: Menentukan kondisi pencarian dimana harga rental mobil harus kurang dari 100,000.

Jadi, hasil dari query ini akan menampilkan semua data mobil yang memiliki warna 'hitam' atau 'silver', dan harga rental mobil kurang dari 100,000.

Query MySQL kedua juga digunakan untuk mengambil data dari tabel 'mobil' dengan dua kondisi pencarian:

1. Warna mobil harus 'HITAM' atau 'SILVER'.
2. Harga rental mobil harus lebih besar dari 50,000.

Analisis:

1. SELECT *: Mengambil semua kolom dari tabel 'mobil'.
2. FROM mobil: Menentukan tabel yang akan diambil datanya, yaitu 'mobil'.
3. WHERE warna IN ('hitam', 'silver'): Menentukan kondisi pencarian dimana warna mobil harus 'hitam' atau 'silver'.
4. AND harga_rental > 50000: Menentukan kondisi pencarian dimana harga rental mobil harus lebih besar dari 50,000.

Jadi, hasil dari query ini akan menampilkan semua data mobil yang memiliki warna 'hitam' atau 'silver', dan harga rental mobil lebih besar dari 50,000.
## Kesimpulan
 Query MySQL pertama mengambil data mobil dengan warna 'hitam' atau 'silver' dan harga rental kurang dari 100,000. Query kedua mengambil data mobil dengan warna 'hitam' atau 'silver' dan harga rental lebih besar dari 50,000. 

Kesimpulannya, query pertama akan menghasilkan daftar mobil 'hitam' atau 'silver' dengan harga rental di bawah 100,000, sedangkan query kedua akan menghasilkan daftar mobil 'hitam' atau 'silver' dengan harga rental di atas 50,000.

