 
# menggunakan xampp
1. Buka Xampp
2. klik start di mysql

![alt text](https://github.com/alfazari06/basis-data/blob/main/ASETBASISDATA/r.p.png?raw=true)


3. klik shell

![alt text](https://github.com/alfazari06/basis-data/blob/main/ASETBASISDATA/rpl.png?raw=true)

  4. ketik mysql -u root -p

  ![alt text](https://github.com/alfazari06/basis-data/blob/main/ASETBASISDATA/rehan.png?raw=true)  


  5. baru enter lalu nantinya akan muncul seperti ini klik lagi enter

   ![alt text](https://github.com/alfazari06/basis-data/blob/main/ASETBASISDATA/frhan.png?raw=true)


# Referensi video youtube
<[https://youtu.be/rT93qlWBhoQ?si=icUNByWK57GIuo0v](https://youtu.be/rT93qlWBhoQ?si=icUNByWK57GIuo0v "https://youtu.be/rT93qlWBhoQ?si=icUNByWK57GIuo0v")>

# Penggunaan awal mysql

## **Query mysql -u root -p**
Query dalam konteks basis data mengacu pada perintah atau instruksi yang digunakan untuk mengambil, menyimpan, memperbarui, atau menghapus data dari sebuah basis data. 

Perintah mysql -u root -p sendiri bukanlah sebuah query MySQL, melainkan cara untuk mengakses server MySQL menggunakan klien baris perintah (CLI) dan login sebagai pengguna "root" dengan meminta kata sandi.
## Hasil

![alt text](https://github.com/alfazari06/basis-data/blob/main/ASETBASISDATA/contoh.jpg?raw=true)

# Analisis
Perintah mysql -u root -p adalah cara untuk mengakses server MySQL menggunakan klien baris perintah (CLI) dan login sebagai pengguna "root" dengan meminta kata sandi. Ini memiliki beberapa implikasi dan aspek yang perlu dianalisis:
## Mysql
Keamanan: Menggunakan akun "root" memiliki kekuatan penuh atas server MySQL. Ini berarti Anda memiliki kemampuan untuk melakukan hampir semua tugas administratif, termasuk membuat, menghapus, dan memodifikasi basis data dan pengguna. Namun, dengan kekuatan ini juga datang tanggung jawab besar untuk memastikan keamanan server MySQL Anda. Penggunaan akun "root" harus dibatasi hanya untuk tugas-tugas yang membutuhkan hak akses tertinggi.

##  -u root
Otentikasi Pengguna: Melalui penggunaan opsi -u root, perintah ini secara eksplisit menentukan pengguna yang akan digunakan untuk otentikasi. Ini memungkinkan Anda untuk menggunakan pengguna tertentu saat terhubung ke server MySQL

## -p
Ketergantungan pada Kata Sandi: Argumen -p menandakan bahwa perintah ini akan meminta Anda untuk memasukkan kata sandi setelah dijalankan. Hal ini meningkatkan keamanan karena tidak menyimpan kata sandi di dalam perintah itu sendiri, tetapi juga berarti Anda harus memasukkan kata sandi setiap kali Anda ingin terhubung ke server

# Kesimpulan

- mysql: Ini adalah perintah untuk memulai klien MySQL Command Line Interface (CLI), yang memungkinkan Anda berinteraksi dengan server MySQL dari baris perintah

- -u root: Argumen ini menentukan pengguna yang ingin Anda gunakan untuk terhubung ke server. Di sini, "root" adalah nama pengguna MySQL yang akan digunakan. Dalam banyak instalasi MySQL, pengguna "root" memiliki hak akses penuh ke server dan basis data.

- -p: Argumen ini memberi tahu klien MySQL bahwa Anda ingin memasukkan kata sandi setelah menjalankan perintah ini untuk otentikasi. Setelah Anda mengetikkan perintah dan menekan Enter, sistem akan meminta Anda untuk memasukkan kata sandi.

Jadi, secara keseluruhan, perintah mysql -u root -p digunakan untuk memulai klien MySQL CLI, terhubung ke server MySQL sebagai pengguna "root", dan meminta Anda untuk memasukkan kata sandi untuk otentikasi. Setelah otentikasi berhasil, Anda dapat mulai menjalankan perintah SQL untuk mengelola basis data dan tabel.

# Database
## Buat Database
-  Di sini, nama_database adalah nama yang Anda inginkan untuk basis data baru yang akan Anda buat. Misalnya, jika Anda ingin membuat basis data dengan nama "tokobuku", Anda akan menulis:
## Tampilkan Database
- Untuk menampilkan daftar basis data yang ada di server MySQL beserta informasi tambahan seperti pemilik basis data, karakter set, dan kolasi, Anda dapat menggunakan perintah SHOW DATABASES;. Ini akan menampilkan daftar nama basis data yang tersedia di server MySQL.
## Hapus Database
- Untuk menghapus sebuah basis data (database) di MySQL, Anda dapat menggunakan perintah SQL DROP DATABASE. Namun, perlu diingat bahwa penghapusan sebuah basis data akan menghapus semua tabel, indeks, dan data yang terkait dengannya, sehingga pastikan untuk melakukan tindakan ini dengan hati-hati dan hanya jika benar-benar diperlukan.
## Gunakan Database
- Untuk menggunakan sebuah basis data (database) di MySQL, Anda perlu terlebih dahulu memilih basis data tersebut menggunakan perintah USE. Setelah itu, semua operasi query yang Anda lakukan akan berlaku pada basis data yang telah Anda pilih.
# query
- CREATE DATABASE nama_database;
- SHOW DATABASES; 
- DROP DATABASE  nama_database;
- USE DATABASE nama_database:

# analisis
## Buat database
- Di sini, nama_database adalah nama yang Anda inginkan untuk basis data baru yang akan Anda buat. Misalnya, jika Anda ingin membuat basis data dengan nama "tokobuku", Anda akan menulis: CREATE DATABASE;
## Tampilkan databases
- Perintah ini akan menghasilkan output yang berisi daftar semua basis data yang ada di server MySQL. Untuk menampilkan informasi lebih lanjut tentang sebuah basis data tertentu, Anda dapat menggunakan perintah SHOW  DATABASES nama_database;. Ini akan menampilkan pernyataan SQL yang digunakan untuk membuat basis data tersebut, termasuk karakter set dan kolasi yang digunakan
## Hapus database
- Di sini, x1_ adalah nama basis data yang ingin Anda hapus. Misalnya, jika Anda ingin menghapus basis data dengan nama "tokobuku", Anda akan menulis: DROP DATABASE;
## Gunakan databases
- Di sini, nama_database adalah nama basis data yang ingin Anda gunakan. Misalnya, jika Anda ingin menggunakan basis data dengan nama "tokobuku", Anda akan menulis: USE DATABASE;
# Kesimpulan
## Buat database
kesimpulan dari proses membuat database berserta format di MySQL adalah bahwa ini adalah langkah penting dalam mempersiapkan lingkungan pengembangan data yang sesuai dan merupakan fondasi untuk pengembangan aplikasi yang sukses.
## Tampilkan databases
perintah SHOW DATABASES; adalah alat yang penting dalam administrasi dan pengelolaan basis data di MySQL karena memberikan daftar semua basis data yang tersedia, memudahkan navigasi di antara basis data, dan membantu dalam pengambilan keputusan terkait struktur data.
## Hapus database
kesimpulan dari proses menghapus database berserta format di MySQL adalah bahwa ini adalah tindakan serius yang memerlukan pertimbangan dan persiapan yang matang untuk memastikan bahwa data tidak hilang secara tidak sengaja dan bahwa dampaknya dipahami dengan baik

## Gunakan database
Kesimpulannya, penggunaan basis data di MySQL berserta formatnya melibatkan pemahaman tentang desain data, penggunaan SQL, keamanan, dan kinerja. Pemahaman ini diperlukan untuk memastikan pengelolaan data yang efektif dan aplikasi yang dapat diandalkan.

# Hasil Dari Database
##  Hasil dari Create database

![alt text](https://github.com/alfazari06/basis-data/blob/main/ASETBASISDATA/hcd.png?raw=true)

## Hasil dari show databases
![alt text](https://github.com/alfazari06/basis-data/blob/main/ASETBASISDATA/hsd.png?raw=true)

## Hasil dari Drod database

![alt text](https://github.com/alfazari06/basis-data/blob/main/ASETBASISDATA/hdd.png?raw=true)

## Hasil dari Use

![alt text](https://github.com/alfazari06/basis-data/blob/main/ASETBASISDATA/hud.png?raw=true)

# Tipe Data
## Angka
Tipe data angka dalam MySQL digunakan untuk menyimpan nilai numerik. Berikut adalah definisi untuk beberapa tipe data angka umum dalam MySQL:

INT atau INTEGER: Tipe data ini digunakan untuk menyimpan bilangan bulat tanpa koma dengan panjang standar 4 byte. Contohnya, INT(10).

TINYINT: Tipe data ini digunakan untuk menyimpan bilangan bulat kecil dengan panjang 1 byte. Contohnya, TINYINT(3).

SMALLINT: Digunakan untuk menyimpan bilangan bulat dengan panjang 2 byte. Contohnya, SMALLINT(5).

MEDIUMINT: Tipe data ini digunakan untuk menyimpan bilangan bulat dengan panjang 3 byte. Contohnya, MEDIUMINT(8).

BIGINT: Tipe data ini digunakan untuk menyimpan bilangan bulat yang sangat besar dengan panjang 8 byte. Contohnya, BIGINT(20).

DECIMAL atau NUMERIC: Tipe data desimal yang menyimpan angka berkoma dengan presisi dan skala yang dapat diatur. Contohnya, DECIMAL(10,2) untuk menyimpan angka dengan 10 digit, 2 di antaranya di belakang koma.

FLOAT: Digunakan untuk menyimpan angka berkoma dengan presisi ganda. Contohnya, FLOAT(7,4).

DOUBLE: Tipe data ini mirip dengan FLOAT, namun dengan presisi yang lebih tinggi. Contohnya, DOUBLE(15,8).

BIT: Tipe data boolean yang dapat menyimpan nilai 0 atau 1, atau NULL. Contohnya, BIT(1).

Definisi tipe data ini mencakup panjang (length), presisi, dan skala yang memberikan kontrol lebih lanjut terhadap cara data angka disimpan
## Teks
Teks
Dalam MySQL, terdapat beberapa tipe data teks yang digunakan untuk menyimpan data karakter atau string. Berikut adalah beberapa tipe data teks yang umum digunakan:

CHAR(n): Menyimpan string karakter tetap (fixed-length) dengan panjang n. Jika panjang string kurang dari n, maka akan diisi dengan spasi. Misalnya, CHAR(10) akan menyimpan string dengan panjang tepat 10 karakter.

VARCHAR(n): Menyimpan string karakter dengan panjang variabel (variable-length) maksimal n. Jika panjang string yang disimpan kurang dari n, maka hanya akan menggunakan ruang yang diperlukan. VARCHAR lebih efisien dalam penggunaan ruang dibandingkan CHAR.

TEXT: Menyimpan string karakter dengan panjang variabel yang sangat besar (hingga 65,535 karakter).

TINYTEXT, MEDIUMTEXT, LONGTEXT: Variasi dari tipe data TEXT dengan batasan panjang yang berbeda. TINYTEXT dapat menyimpan hingga 255 karakter, MEDIUMTEXT hingga 16,777,215 karakter, dan LONGTEXT hingga 4,294,967,295 karakter.
- Char: Tipe data yang digunakan untuk menyimpan satu karakter. Char diwakili oleh tanda kutip tunggal (''). Contoh: 'a', 'b', atau '1'.

## Tanggal/waktu
Dalam MySQL, terdapat beberapa tipe data yang digunakan untuk menangani tanggal dan waktu. Berikut adalah beberapa tipe data tanggal yang umum digunakan:

DATE: Menyimpan tanggal dengan format "YYYY-MM-DD". Tipe data ini tidak menyimpan informasi waktu, hanya tanggal.

Contoh: '2024-01-30'

TIME: Menyimpan informasi waktu dengan format "HH:MM:SS". Tipe data ini tidak menyimpan tanggal, hanya waktu.
Contoh: '20:45:00'

DATETIME: Kombinasi dari DATE dan TIME. Menyimpan tanggal dan waktu dengan format "YYYY-MM-DD HH:MM:SS". Contoh: '2024-01-3 25 20:45:00'

TIMESTAMP: Mirip dengan DATETIME, tetapi dengan perbedaan utama dalam cara nilai-nilai default dan nilai saat direkam diperlakukan. Nilai TIMESTAMP secara otomatis diperbarui setiap kali baris diubah.

Contoh: '2024-02-25 20:45:00'

YEAR: Menyimpan nilai tahun dengan format empat digit "YYYY". Digunakan terutama untuk menyimpan tahun.

Contoh: '2024'
- Datetime (Tanggal dan Waktu): Tipe data yang digunakan untuk merepresentasikan tanggal dan waktu. Selain tahun, bulan, dan hari, tipe data ini juga menyertakan informasi waktu seperti jam, menit, dan detik. Contoh: 2024-01-27 15:30:00.
## Boolean
Dalam MySQL, tipe data boolean umumnya diwakili oleh TINYINT(1), di mana nilai 0 menunjukkan "false" dan nilai selain 0 (biasanya 1) menunjukkan "true". Meskipun tipe data boolean tidak secara resmi didukung di MySQL sebelum versi 5.0.3, banyak aplikasi dan pengembang MySQL telah mengadopsi penggunaan TINYINT(1) untuk menyimpan nilai boolean.

Berikut adalah beberapa poin yang dapat membantu menjelaskan tipe data boolean dalam MySQL:

TINYINT(1): Pada dasarnya, MySQL tidak memiliki tipe data boolean yang jelas. Sebagai gantinya, konvensi umum adalah menggunakan kolom TINYINT(1) untuk menyimpan nilai boolean. Ukuran 1 di sini menunjukkan panjang kolom, dan karena itu, nilai yang diizinkan hanya 0 atau 1. Contoh: CREATE TABLE contoh_boolean ( status TINYINT(1) );

0 dan 1: Secara tradisional, nilai 0 sering diartikan sebagai "false" dan nilai 1 diartikan sebagai "true". Namun, beberapa aplikasi atau kasus penggunaan mungkin menggunakan nilai lain sebagai representasi boolean.

NULL: Nilai NULL juga dapat diizinkan untuk kolom TINYINT(1), yang berarti bahwa kolom tersebut tidak memiliki nilai boolean yang ditetapkan. Contoh: INSERT INTO contoh_boolean (status) VALUES (NULL);

Boolean Functions: MySQL menyediakan beberapa fungsi untuk bekerja dengan nilai boolean atau TINYINT(1), seperti IF(), CASE, dan fungsi-fungsi logika seperti AND, OR, dan NOT. Contoh: SELECT IF(status = 1, 'Aktif', 'Tidak Aktif') AS status_text FROM contoh_boolean;

Penanganan Tipe Data Boolean di Aplikasi: Saat menggunakan MySQL dengan bahasa pemrograman tertentu, aplikasi dapat menangani nilai boolean ini dengan lebih mudah, memberikan abstraksi tingkat tinggi untuk representasi boolean.

Perlu dicatat bahwa sejak MySQL versi 8.0.1, MySQL memperkenalkan tipe data BOOLEAN yang sebenarnya, tetapi di bawahnya, sebenarnya masih diimplementasikan sebagai TINYINT(1) untuk kompatibilitas mundur. Namun, dengan menggunakan BOOLEAN, kita dapat menambahkan keterangan semantik dan meningkatkan kejelasan dalam skema basis data
# Tipe data pilihan
## ENUM
Tipe data ENUM pilihan dalam MySQL memungkinkan Anda untuk menentukan set nilai-nilai yang valid yang dapat dimiliki oleh suatu kolom. Ketika Anda mendefinisikan kolom dengan tipe data ENUM, Anda menyediakan daftar nilai-nilai yang diperbolehkan, dan kolom tersebut hanya dapat mengambil salah satu dari nilai-nilai tersebut.

Keuntungan menggunakan tipe data ENUM pilihan adalah:

1. *Keterbatasan Nilai*: Anda dapat membatasi nilai yang dapat dimasukkan ke dalam kolom, memastikan bahwa hanya nilai-nilai tertentu yang diterima.
2. *Keterbacaan*: Enumerasi nilai-nilai yang diperbolehkan membuat struktur data menjadi lebih mudah dipahami bagi pengguna dan pengembang.
3. *Optimasi Ruang*: Dalam beberapa kasus, tipe data ENUM dapat menghemat ruang penyimpanan karena nilainya disimpan sebagai angka, bukan string.

Namun, ada beberapa pertimbangan yang perlu diperhatikan:

1. *Perubahan Nilai*: Menambah atau menghapus nilai ENUM dapat menyebabkan perubahan skema tabel yang memerlukan perhatian khusus saat berinteraksi dengan database.
2. *Tidak Fleksibel*: Tipe data ENUM cenderung kurang fleksibel dibandingkan dengan tabel referensi terpisah, di mana nilai-nilai referensi dapat dimodifikasi tanpa mengubah struktur tabel induk.
## SET
Di MySQL, tipe data SET memungkinkan Anda untuk menyimpan kumpulan nilai-nilai yang dapat dipilih dalam satu kolom. Sama seperti ENUM, SET juga membatasi nilai-nilai yang dapat dimasukkan ke dalam kolom, namun dengan perbedaan bahwa SET memungkinkan lebih dari satu nilai yang dipilih pada saat yang sama.

Berikut adalah beberapa karakteristik tipe data SET dalam MySQL:

1. *Nilai Berganda*: Dalam kolom dengan tipe data SET, Anda dapat memilih lebih dari satu nilai dari kumpulan nilai yang telah ditentukan.

2. *Daftar Nilai*: Nilai-nilai yang diperbolehkan harus didefinisikan saat membuat tabel, dan setiap nilai harus dipisahkan oleh koma.

3. *Urutan Nilai*: Urutan nilai dalam SET tidak penting. Nilai-nilai yang dipilih akan disimpan dalam urutan yang tidak ditentukan.

4. *Optimasi Ruang*: Tipe data SET dapat menghemat ruang penyimpanan karena nilai-nilai disimpan sebagai sebuah bilangan bulat yang menunjukkan kombinasi bit dari nilai-nilai yang dipilih.

Berikut adalah contoh cara mendefinisikan kolom dengan tipe data SET dalam MySQL:

```mysql
CREATE TABLE example_table (
    id INT AUTO_INCREMENT PRIMARY KEY,
    options SET('option1', 'option2', 'option3', 'option4')
);
```

Dalam contoh ini, kolom options dapat memiliki satu atau beberapa kombinasi nilai dari 'option1', 'option2', 'option3', dan 'option4'. Misalnya, nilai kolom tersebut bisa 'option1,option3' atau 'option2,option4', dan seterusnya.

# Q & A
 >[!faq] Mengapa hanya kolom id_pelanggan yang menggunakan constraint PRIMARY KEY
 >Kolom ID pelanggan seringkali menggunakan constraint PRIMARY KEY karena ID pelanggan adalah atribut yang unik dan dapat digunakan sebagai identifikasi utama untuk setiap entri dalam tabel pelanggan. Dengan membuat kolom ID pelanggan sebagai PRIMARY KEY, kita memastikan bahwa setiap nilai di kolom tersebut adalah unik dan tidak ada yang duplikat. Ini memungkinkan untuk efisiensi pencarian dan pengindeksan data, serta memastikan integritas referensial di dalam basis data. Selain itu, PRIMARY KEY juga dapat digunakan sebagai acuan untuk membuat relasi dengan tabel lain dalam skema basis data.
 
>[!faq] Mengapa pada kolom no_telp yang menggunakan tipe data char bukan varchar
>Tipe data CHAR lebih efisien digunakan untuk kolom yang memiliki nilai tetap atau panjang yang konsisten, seperti ID pelanggan yang biasanya memiliki panjang yang sama untuk setiap entri. Penggunaan tipe data CHAR dapat mengoptimalkan penyimpanan dan kinerja database. Sedangkan tipe data VARCHAR lebih fleksibel dan cocok untuk kolom yang memiliki nilai yang bervariasi dalam panjangnya, seperti teks atau deskripsi. Jadi, jika ID pelanggan memiliki panjang yang tetap, penggunaan tipe data CHAR bisa menjadi pilihan yang lebih efisien.


> [!faq] Menngapa hanya kolom no_telp yang menggunakan constraint UNIQUE?
> Kolom nomor telepon (no_telp) seringkali menggunakan constraint UNIQUE karena nomor telepon harus unik untuk setiap entri dalam tabel. Dengan membuat kolom no_telp sebagai UNIQUE, kita memastikan bahwa tidak ada nomor telepon yang sama yang diizinkan untuk dimasukkan ke dalam basis data. Ini penting untuk mencegah duplikasi nomor telepon, yang dapat mengakibatkan kesulitan dalam mengidentifikasi atau menghubungi pelanggan, serta memastikan integritas data yang lebih baik. Selain itu, menggunakan constraint UNIQUE pada kolom no_telp juga memungkinkan pencarian dan pengindeksan yang lebih efisien.
> 


>[!faq] Mengapa kolom no_telp tidak memakai constraint NOT NULL, sementara kolom lainnya menggunakan constraint tersebut?
>Kolom nomor telepon (no_telp) mungkin tidak menggunakan constraint NOT NULL karena dalam beberapa kasus, nomor telepon tidak selalu tersedia atau wajib diisi. Misalnya, saat membuat entri untuk pelanggan yang belum memiliki nomor telepon, memaksa kolom no_telp menjadi NOT NULL dapat menjadi kendala.
>
>Namun, dalam kebanyakan kasus, memang disarankan untuk menggunakan constraint NOT NULL pada kolom nomor telepon untuk memastikan bahwa setiap entri dalam tabel memiliki nomor telepon yang valid. Hal ini membantu menjaga integritas data dan mencegah nilai yang kosong atau tidak valid. Jadi, keputusan untuk menggunakan constraint NOT NULL pada kolom no_telp tergantung pada kebutuhan aplikasi dan preferensi desain basis data.


>[!faq] Perbedaan antara PK dan UNIQUE
>PK (Primary Key) dan Unique Key adalah dua konsep dalam desain database yang sering digunakan untuk memastikan keunikan nilai di dalam sebuah tabel, tetapi mereka memiliki perbedaan yang penting:

1. *Primary Key (PK)*:
   - Sebuah kolom atau kombinasi dari kolom yang secara unik mengidentifikasi setiap baris dalam tabel.
   - PK tidak boleh memiliki nilai yang duplikat, dan tidak boleh memiliki nilai NULL.
   - Hanya ada satu PK dalam satu tabel.
   - Biasanya digunakan untuk membangun hubungan antar-tabel (foreign key).

2. *Unique Key*:
   - Sebuah kolom atau kombinasi dari kolom yang juga memiliki nilai yang unik di dalam tabel.
   - Tidak ada batasan pada jumlah unique key yang bisa ada di sebuah tabel.
   - Nilai dari unique key bisa NULL, tetapi hanya satu baris yang boleh memiliki nilai NULL. Jika sebuah unique key memiliki nilai NULL, maka hanya satu baris yang bisa memiliki nilai NULL untuk unique key tersebut.
   - Biasanya digunakan untuk memastikan bahwa nilai-nilai tertentu dalam tabel unik, tetapi tidak secara khusus digunakan untuk mengidentifikasi setiap baris.

Jadi, perbedaan utama antara PK dan Unique Key adalah bahwa PK mengidentifikasi setiap baris secara unik dan tidak boleh memiliki nilai NULL, sedangkan Unique Key memastikan keunikan nilai tetapi bisa memiliki nilai NULL (dengan syarat tertentu) dan tidak secara khusus digunakan untuk mengidentifikasi setiap baris.

# Insert
## Insert 1 data

### Struktur
```mysql
insert into nama_table
valeus ('NILAI','NILAI2','NILAI3','NILAI4');
```

## Contoh
```mysql
insert into customerr values (1,'raihan','alfz','087868449445');
```
## Hasil
![alt text](https://github.com/alfazari06/basis-data/blob/main/ASETBASISDATA/h.select%201%20kolom.png?raw=true)

## Analisis
Query MySQL di atas adalah perintah INSERT INTO yang digunakan untuk menyisipkan data ke dalam tabel customerr. Data yang akan dimasukkan adalah: 1 sebagai nilai untuk kolom pertama (mungkin ID pelanggan), 'raihan' untuk kolom kedua (mungkin nama depan), 'alfz' untuk kolom ketiga (mungkin nama belakang), dan '087868449445' untuk kolom keempat (mungkin nomor telepon).

Namun, perlu diperhatikan bahwa jika tabel customerr belum ada, maka query ini akan menghasilkan error. Juga, pastikan bahwa struktur tabel customerr sesuai dengan urutan kolom yang dimasukkan dalam perintah INSERT INTO.
## Kesimpulan
Query MySQL di atas adalah sebuah perintah INSERT INTO yang bertujuan untuk menyisipkan data ke dalam tabel customerr. Data yang disisipkan adalah sebagai berikut:

- Kolom pertama (mungkin ID pelanggan) akan diisi dengan nilai 1.
- Kolom kedua (mungkin nama depan) akan diisi dengan nilai 'raihan'.
- Kolom ketiga (mungkin nama belakang) akan diisi dengan nilai 'alfz'.
- Kolom keempat (mungkin nomor telepon) akan diisi dengan nilai '087868449445'.

Kesimpulannya, query ini dimaksudkan untuk menambahkan data pelanggan dengan nama 'Raihan Alfz' dan nomor telepon '087868449445' ke dalam tabel customerr.


## Insert >1 data
```mysql
insert into nama_table
valeus ('NILAI','NILAI2','NILAI3','NILAI4'),
('NILAI','NILAI2','NILAI3','NILAI4'),
('NILAI','NILAI2','NILAI3','NILAI4');
```
## Contoh
```mysql
insert into customer
    -> Values(2,'isar','rmn','085882169640'),
    -> (3,'Jamil','lhm','085823967204'),
    -> (4,'ardy','rd','0895333405548');
```

## Hasil
![alt text](https://github.com/alfazari06/basis-data/blob/main/ASETBASISDATA/h.insert%20.png?raw=true)

## Analisis
Query MySQL di atas adalah perintah INSERT INTO yang bertujuan untuk menyisipkan beberapa baris data ke dalam tabel customer. Data yang ingin dimasukkan adalah sebagai berikut:

1. Baris pertama: Nilai 2 untuk kolom pertama (mungkin ID pelanggan), 'isar' untuk kolom kedua (mungkin nama depan), 'rmn' untuk kolom ketiga (mungkin nama belakang), dan '085882169640' untuk kolom keempat (mungkin nomor telepon).

2. Baris kedua: Nilai 3 untuk kolom pertama (mungkin ID pelanggan), 'Jamil' untuk kolom kedua (mungkin nama depan), 'lhm' untuk kolom ketiga (mungkin nama belakang), dan '085823967204' untuk kolom keempat (mungkin nomor telepon).

3. Baris ketiga: Nilai 4 untuk kolom pertama (mungkin ID pelanggan), 'ardy' untuk kolom kedua (mungkin nama depan), 'rd' untuk kolom ketiga (mungkin nama belakang), dan '0895333405548' untuk kolom keempat (mungkin nomor telepon).

## Kesimpulan
Query MySQL di atas berusaha untuk menyisipkan beberapa baris data ke dalam tabel customer. 

1. Baris pertama: Menambahkan data pelanggan dengan ID 2, nama depan 'isar', nama belakang 'rmn', dan nomor telepon '085882169640'.

2. Baris kedua: Menambahkan data pelanggan dengan ID 3, nama depan 'Jamil', nama belakang 'lhm', dan nomor telepon '085823967204'.

3. Baris ketiga: Menambahkan data pelanggan dengan ID 4, nama depan 'ardy', nama belakang 'rd', dan nomor telepon '0895333405548'.


## Menyebut kolom
```mysql
insert into nama_table
('NILAI','NILAI2','NILAI3','NILAI4') values ('NILAI','NILAI2','NILAI3','NILAI4')
```

## Contoh
```mysql
Insert into customer
(nama_asli,id_customer) values ('hansar',5);

```

## Hasil

![alt text](https://github.com/alfazari06/basis-data/blob/main/ASETBASISDATA/h.insert%20tabel%20baru.png?raw=true)

## Analisis
Query MySQL di atas adalah perintah INSERT INTO yang digunakan untuk menyisipkan/menambahkan data ke dalam tabel customer. Data yang disisipkan adalah sebagai berikut:

- Kolom nama_asli akan diisi dengan nilai 'hansar'.
- Kolom id_customer akan diisi dengan nilai 5.

Ini berarti data pelanggan dengan nama asli 'hansar' dan ID '5' akan dimasukkan ke dalam tabel customer. Perlu dicatat bahwa jika kolom-kolom lain dalam tabel memiliki nilai default atau tidak wajib diisi, mereka akan diisi dengan nilai default atau NULL sesuai dengan konfigurasi tabel.
## Kesimpulan
Query MySQL di atas adalah perintah INSERT INTO yang bertujuan untuk menyisipkan data ke dalam tabel customer. Data yang disisipkan adalah pelanggan dengan nama asli 'hansar' dan ID pelanggan '5'. Dengan kata lain, query ini menambahkan baris baru ke dalam tabel customer dengan nilai-nilai yang telah ditentukan untuk kolom nama_asli dan id_customer.

# Select
## Struktur
```mysql
select * from nama_tabel;
```

## Contoh
```mysql
select * from customer;
```

## Hasil
setelah kamu mengetikkan query diatas selanjutnya klik enter  maka akan muncul tampilan seperti yang di bawah ini yang berarti kamu telah berhasil:

![alt text](https://github.com/alfazari06/basis-data/blob/main/ASETBASISDATA/tabel3.png?raw=true)

## Analisis
Query MySQL di atas adalah perintah yang digunakan untuk menampilkan semua data dari tabel 'customer'. Tidak ada kondisi pencarian khusus yang ditentukan dalam query ini, sehingga query akan mengembalikan semua baris yang ada dalam tabel 'customer'.
- SELECT *: Memilih semua kolom dari tabel 'customer'.
- FROM customer: Menentukan tabel yang akan diambil datanya, yaitu 'customer'.

Jadi, hasil dari query ini akan menampilkan semua data yang tersimpan dalam tabel 'customer'.
## Kesimpulan
Query MySQL di atas digunakan untuk mengambil semua data yang tersimpan dalam tabel 'customer'. Ini berarti query tersebut akan mengembalikan daftar lengkap dari semua entri dalam tabel 'customer', termasuk semua kolom yang ada dalam tabel tersebut seperti nama, alamat, nomor telepon, dll.


# Data kolom tertentu
## Struktur

```mysql
select nama_kolom1,nama_kolom2,nama_kolom3,nama_kolom4 from nama_table;
```

## Contoh
```mysql
select nama_depan from customer;
```

## Hasil
setelah kamu mengetikkan query diatas selanjutnya klik enter  maka akan muncul tampilan seperti yang di bawah ini yang berarti kamu telah berhasil:

![alt text](https://github.com/alfazari06/basis-data/blob/main/ASETBASISDATA/tabel4.png?raw=true)

## Analisis
Query MySQL di atas adalah perintah yang digunakan untuk menampilkan hanya kolom 'nama_depan' dari tabel 'customer'. 

Analisis:
- SELECT nama_depan: Memilih hanya kolom 'nama_depan' dari tabel 'customer'.
- FROM customer: Menentukan tabel yang akan diambil datanya, yaitu 'customer'.

Jadi, hasil dari query ini akan menampilkan semua nilai yang ada dalam kolom 'nama_depan' dari tabel 'customer'.
## Kesimpulan
Query MySQL di atas digunakan untuk mengambil data dari kolom 'nama_depan' dalam tabel 'customer'. Ini berarti query tersebut akan menghasilkan daftar semua nilai yang ada dalam kolom 'nama_depan' dari tabel 'customer'.



# KLAUSA WHERE

## Struktur
```mysql
select nama_kolom/ *from nama_table
where kondisi;
```

## Contoh
```mysql
select * from customer
where id_customer=2;
```

## Hasil
setelah kamu mengetikkan query diatas selanjutnya klik enter  maka akan muncul tampilan seperti yang di bawah ini yang berarti kamu telah berhasil:

![alt text](https://github.com/alfazari06/basis-data/blob/main/ASETBASISDATA/tabel5.png?raw=true)

## Analisis
Query MySQL di atas adalah perintah yang digunakan untuk menampilkan semua data dari tabel 'customer' dimana nilai kolom 'id_customer' sama dengan 2.

Analisis:
- SELECT *: Memilih semua kolom dari tabel 'customer'.
- FROM customer: Menentukan tabel yang akan diambil datanya, yaitu 'customer'.
- WHERE id_customer=2: Menentukan kondisi pencarian dimana nilai kolom 'id_customer' harus sama dengan 2.

Jadi, hasil dari query ini akan menampilkan semua data dari tabel 'customer' dimana nilai kolom 'id_customer' sama dengan 2. Ini berarti hanya satu baris data yang akan ditampilkan, yaitu data dari pelanggan dengan ID 2.
## Kesimpulan
Query MySQL di atas digunakan untuk mengambil semua data dari tabel 'customer' dimana nilai kolom 'id_customer' sama dengan 2. Ini berarti query tersebut akan menghasilkan daftar lengkap dari semua kolom untuk pelanggan dengan ID 2.

# Update

## Struktur
```mysql
 update nama_tabel set nama_kolom where kondisi;
```

## Contoh
```mysql
 update customer set no_telp="08127611712" where id_customer="2";
```
## Hasil
setelah kamu mengetikkan query diatas selanjutnya klik enter  maka akan muncul tampilan seperti yang di bawah ini yang berarti kamu telah berhasil:

![alt text](https://github.com/alfazari06/basis-data/blob/main/ASETBASISDATA/H.UPDATE.png?raw=true)

## Analisis
Query MySQL di atas adalah perintah yang digunakan untuk memperbarui data dalam tabel 'customer'. Query tersebut memiliki dua bagian utama:

1. UPDATE customer: Menentukan tabel yang akan diperbarui, yaitu 'customer'.
2. SET no_telp="08127611712" WHERE id_customer="2": Menentukan nilai baru yang akan diatur untuk kolom 'no_telp' dimana nilai kolom 'id_customer' sama dengan 2.

Analisis:
- UPDATE customer: Menentukan tabel yang akan diperbarui.
- SET no_telp="08127611712": Menentukan nilai baru untuk kolom 'no_telp'.
- WHERE id_customer="2": Menentukan kondisi dimana hanya data dengan nilai kolom 'id_customer' sama dengan 2 yang akan diperbarui.

Jadi, hasil dari query ini akan memperbarui nomor telepon pelanggan dengan ID 2 menjadi "08127611712" dalam tabel 'customer'.
## Kesimpulan
Query MySQL di atas adalah perintah untuk memperbarui nomor telepon pelanggan dengan ID 2 menjadi "08127611712" dalam tabel 'customer'. Ini berarti nomor telepon untuk pelanggan dengan ID 2 akan diperbarui dengan nomor yang baru.
# Delate

## Struktur
```mysql
DELETE FROM nama_tabel WHERE kondisi;
```

##  Contoh
```mysql
DELETE FROM CUSTOMER WHERE ID_CUSTOMER=1;
```

## Hasil
setelah kamu mengetikkan query diatas selanjutnya klik enter  maka akan muncul tampilan seperti yang di bawah ini yang berarti kamu telah berhasil:

![alt text](https://github.com/alfazari06/basis-data/blob/main/ASETBASISDATA/H.DELETE.png?raw=true)

## Analisis
Query MySQL di atas adalah perintah yang digunakan untuk menghapus data dari tabel 'customer' dimana nilai kolom 'id_customer' sama dengan 1.

Analisis:
- DELETE FROM customer: Menentukan tabel yang akan dihapus datanya, yaitu 'customer'.
- WHERE id_customer=1: Menentukan kondisi pencarian dimana nilai kolom 'id_customer' harus sama dengan 1.

Jadi, hasil dari query ini akan menghapus satu baris data dari tabel 'customer' dimana nilai kolom 'id_customer' sama dengan 1. Ini berarti data pelanggan dengan ID 1 akan dihapus dari tabel 'customer'.Query MySQL di atas adalah perintah yang digunakan untuk menghapus data dari tabel 'customer' dimana nilai kolom 'id_customer' sama dengan 1.

Analisis:
- DELETE FROM customer: Menentukan tabel yang akan dihapus datanya, yaitu 'customer'.
- WHERE id_customer=1: Menentukan kondisi pencarian dimana nilai kolom 'id_customer' harus sama dengan 1.

Jadi, hasil dari query ini akan menghapus satu baris data dari tabel 'customer' dimana nilai kolom 'id_customer' sama dengan 1. Ini berarti data pelanggan dengan ID 1 akan dihapus dari tabel 'customer'.
## Kesimpulan
Query MySQL di atas adalah perintah untuk menghapus data dari tabel 'customer' dimana nilai kolom 'id_customer' sama dengan 1. Ini berarti data pelanggan dengan ID 1 akan dihapus dari tabel 'customer'
