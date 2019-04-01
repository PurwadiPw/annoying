## Sistem Informasi
Sistem kumpulan dari unsur/elemen-elemen yang saling berkaitan/berinteraksi dan saling mempengaruhi dalam melakukan kegiatan bersama untuk mencapai suatu tujuan tertentu.

Informasi data yang telah diproses menjadi bentuk yang memiliki arti bagi penerima dan dapat berupa fakta, suatu nilai yang bermanfaat. Jadi ada suatu proses transformasi data menjadi suatu informasi == input - proses – output.

Sistem Informasi “Sekumpulan prosedur manual atau terkomputerisasi yang mengumpulkan/mengambil, mengolah, menyimpan dan menyebarkan informasi dalam mendukung pengambilan dan kendali keputusan”

## Peranan SI dan TI pada Organisasi
1. Menunjang kegiatan bisnis operasional.

   Mulai dari akuntansi sampai dengan penelusuran pesanan pelanggan, sistem informasi menyediakan dukungan bagi manajemen dalam operasi kegiatan bisnis sehari-hari. Ketkka tanggapan atau respon yang cepat menjadi penting, maka kemampuan sistem informasi untuk dapat mengumpulkan dan mengintegrasikan informasi ke berbagai fungsi bisnis menjadi kritis atau penting.
2. Menunjang untuk pengambilan keputusan.

   Sistem informasi dapat mengombinasikan informasi untuk membantu manajer menjalankan bisnis dengan lebih baik, informasi yang sama dapat membantu para manajer mengidentifikasikan kecenderungan dan untuk mengevaluasi hasil dari keputusan sebelumnya. Sistem informasi akan membantu para manajer membuat keputusan yang lebih baik, lebih tepat, dan lebih bermakna.

http://kuantin1993.blogspot.com/2013/06/peran-teknologi-informasi-dalam.html

## Aturan DFD (anak panah)
### Fungsi
1. Alur data yang berasal dari data store, berarti proses membutuhkan data yang berada pada data store tersebut
2. Alur data yang menuju ke data store, berarti suatu proses akan menghasilkan output atau keluaran yang disimpan pada data store tersebut.
3. Alur data yang berasal dan yang menuju ke data store berarti suatu proses akan mengupdate data, menghapus atau mengubah data.

### Aturan
1. Pada setiap Proses harus ada arus masuk (input) dan arus keluar(output)
2. Sebuah Arus Data harus dilampirkan ke dalam Proses
4. Suatu Arus Data memiliki nama atau label berupa kata benda
5. Input ke suatu proses harus berbeda dengan output dari proses

## Output SDLC
Merancang bentuk laporan dan dokumen-dokumen untuk system yang baru berdasarkan system saat ini.

Tujuan : Memerikan bentuk-bentuk laporan sistem dan dokumennya.

Hasil : Bentuk (forms) dari dokumentasi keluaran (output).

## Studi kasus perkuliahan
### Deskripsi
Information Display System Jadwal Perkuliahan Informatika Universitas Muhammadiyah Surakarta berbasis Web. Aplikasi ini nantinya akan ditampilkan kedalam sebuah layar LCD yang diletakkan didepan kantor tata usaha, sehingga mahasiswa dapat mengetahui dosen yang mengajarnya hadir atau tidak dan apakah jam mengajarnya dirubah atau tidak. Sistem yang akan peneliti buat ini nantinya akan menampilkan seluruh jadwal perkuliahan. Dosen dapat menginformasikan kehadirannya melalui sistem tersebut dengan cara SMS dengan format yang sudah ditentukan dan sistem akan mengolah data yang dikirimkan dan menampilkan informasi tersebut ke dalam layar LCD. 

### Kebutuhan fungsionalitas
Kebutuhan fungsionalitas yang dibutuhkan dalam mendukung aplikasi ini adalah:

1. Daftar Dosen Prodi Sistem Informasi Universitas Widyatama
2. Daftar Jadwal Mata Kuliah Prodi Informatika Universitas Widyatama

### Kebutuhan non fungsionalitas
Kebutuhan non–fungsional adalah batasan layanan atau fungsi yang ditawarkan sistem seperti batasan waktu, batasan pengembangan proses, standarisasi dll.

Kebutuhan non-fungsional ini membantu proses jalannya sistem, antara lain :

* Dibutuhkan kecepatan internet yang stabil
* Dibutuhkan keamanan terhadap data
* Dibutuhkan sistem perangkat keras (Hardware) untuk membantu jalannya sistem
* Dibutuhkan sistem perangkat lunak (Software) untuk pembuatan sistem

### DFD Level 0
<div align="center" markdown="1">

![DFD Level 0](https://raw.githubusercontent.com/PurwadiPw/annoying/master/kuliah/apsi/dfd-lv-0-perkuliahan.png)

</div>

## Studi kasus perwalian
### Deskripsi
Dalam hal ini Universitas Widyatama khususnya pada Prodi Sistem Informasi sangat membutuhkan sistem informasi yang berhubungan dengan perwalian mahasiswa. Sehingga dengan adanya program ini diharapkan akan mempermudah dosen wali dalam memberikan bimbingan dan nasehat kepada mahasiswanya berdasarkan data – data dari mahasiswa itu sendiri yang mencakup IP per semester ,pengambilan jumlah krs, keluhan – keluhan mahasiswa, jumlah tatap muka perwalian per mahasiswa dan lain lain agar membantu mahasiswa dalam menyiapkan kegiatan perkuliahan dalam suatu semester tertentu. 

### Kebutuhan fungsionalitas
1. Untuk Dosen Wali
  * Laporan Indek Prestasi 
     
    adalah laporan indek prestasi baik kumulatif atau indek prestasi per semester untuk setiap mahasiwa perwaliannya.
  * Laporan Record Perwalian. 
    
    adalah laporan record perwalian untuk mahasiswa perwaliannya dari awal sampai semester yang telah dicapai.
  * Laporan Mahasiswa Perwalian.
    
    adalah laporan mengenai data pribadi dari setiap mahasiwa perwaliannya.
2. Untuk Mahasiswa
  * Dosen dan Jadwal Perwalian. 
    
    Nama Dosen dan Jadwal perwaliannya sangat dibutuhkan oleh mahasiswa pada saat kegiatan perwalian.
3. Untuk Administrator / KaProdi 
  * Daftar Dosen Wali 
   
    daftar yang menjelaskan tentang data – data tentang dosen yang telah ditugaskan menjadi dosesn wali di Prodi.
  * Daftar Mahasiswa Perwalian 
    
    daftar yang berisi data – data mahasiswa beserta setiap dosen wali yang mengampunya. 
 
### Kebutuhan non fungsionalitas
Kebutuhan non–fungsional adalah batasan layanan atau fungsi yang ditawarkan sistem seperti batasan waktu, batasan pengembangan proses, standarisasi dll.

Kebutuhan non-fungsional ini membantu proses jalannya sistem, antara lain :

* Dibutuhkan kecepatan internet yang stabil
* Dibutuhkan keamanan terhadap data
* Dibutuhkan sistem perangkat keras (Hardware) untuk membantu jalannya sistem
* Dibutuhkan sistem perangkat lunak (Software) untuk pembuatan sistem

### DFD Level 0
<div align="center" markdown="1">

![DFD Level 0](https://raw.githubusercontent.com/PurwadiPw/annoying/master/kuliah/apsi/dfd-lv-0-perwalian.png)

</div>