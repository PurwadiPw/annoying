*Sistem Informasi*
    Sistem kumpulan dari unsur/elemen-elemen yang saling berkaitan/berinteraksi dan saling mempengaruhi dalam melakukan kegiatan bersama untuk mencapai suatu tujuan tertentu.
    
    Informasi data yang telah diproses menjadi bentuk yang memiliki arti bagi penerima dan dapat berupa fakta, suatu nilai yang bermanfaat. Jadi ada suatu proses transformasi data menjadi suatu informasi == input - proses – output.
    
    Sistem Informasi “Sekumpulan prosedur manual atau terkomputerisasi yang mengumpulkan/mengambil, mengolah, menyimpan dan menyebarkan informasi dalam mendukung pengambilan dan kendali keputusan”

*Aturan DFD (anak panah)*
    Fungsi
        a. Alur data yang berasal dari data store, berarti proses membutuhkan data yang berada pada data store tersebut
        b. Alur data yang menuju ke data store, berarti suatu proses akan menghasilkan output atau keluaran yang disimpan pada data store tersebut.
        c. Alur data yang berasal dan yang menuju ke data store berarti suatu proses akan mengupdate data, menghapus atau mengubah data.
    Aturan
        a. Pada setiap Proses harus ada arus masuk (input) dan arus keluar(output)
        b. Sebuah Arus Data harus dilampirkan ke dalam Proses
        c. Suatu Arus Data memiliki nama atau label berupa kata benda
        d. Input ke suatu proses harus berbeda dengan output dari proses

*Studi kasus perwalian*
    Deskripsi
        Dalam hal ini Universitas Widyatama khususnya pada Prodi Sistem Informasi sangat membutuhkan sistem informasi yang berhubungan dengan perwalian mahasiswa. Sehingga dengan adanya program ini diharapkan akan mempermudah dosen wali dalam memberikan bimbingan dan nasehat kepada mahasiswanya berdasarkan data – data dari mahasiswa itu sendiri yang mencakup IP per semester ,pengambilan jumlah krs, keluhan – keluhan mahasiswa, jumlah tatap muka perwalian per mahasiswa dan lain lain agar membantu mahasiswa dalam menyiapkan kegiatan perkuliahan dalam suatu semester tertentu. 
    
    Kebutuhan fungsionalitas
        a) Untuk Dosen Wali
            1) Laporan Indek Prestasi
                adalah laporan indek prestasi baik kumulatif atau indek prestasi per semester untuk setiap mahasiwa perwaliannya.
            2) Laporan Record Perwalian.
                adalah laporan record perwalian untuk mahasiswa perwaliannya dari awal sampai semester yang telah dicapai.
            3) Laporan Mahasiswa Perwalian.
                adalah laporan mengenai data pribadi dari setiap mahasiwa perwaliannya.
        b) Untuk Mahasiswa
            1) Dosen dan Jadwal Perwalian.
                Nama Dosen dan Jadwal perwaliannya sangat dibutuhkan oleh mahasiswa pada saat kegiatan perwalian.
        c) Untuk Administrator / KaProgdi
            1) Daftar Dosen Wali
                daftar yang menjelaskan tentang data – data tentang dosen yang telah ditugaskan menjadi dosesn wali di progdi.
            2) Daftar Mahasiswa Perwalian
                daftar yang berisi data – data mahasiswa beserta setiap dosen wali yang mengampunya. 
    
    Kebutuhan non fungsionalitas
        Kebutuhan non–fungsional adalah batasan layanan atau fungsi yang ditawarkan sistem seperti batasan waktu, batasan pengembangan proses, standarisasi dll. Kebutuhan non-fungsional ini membantu proses jalannya sistem, antara lain :
        1. Dibutuhkan kecepatan internet yang stabil
        2. Dibutuhkan keamanan terhadap data
        3. Dibutuhkan sistem perangkat keras (Hardware) untuk membantu jalannya sistem
        4. Dibutuhkan sistem perangkat lunak (Software) untuk pembuatan sistem

    DFD Level 0
        ![DFD Level 0](dfd-lv-0-perwalian.png?raw=true)