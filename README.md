# Tugas-writing-week-5
  - # *Back-End Development*
# DAY 1

- ## Database Intro MySQL - Basic

    - Database
    
        Kumpulan informasi yang disimpan didalam komputer secara sistematik dan saling berelasi. Database merupakan sekumpulan tabel yang berisikan informasi untuk diolah yang kemudian data tersebut bisa digunakan di dalam sebuah sistem. Untuk membuat Database diperlukan sebuah software yang dinamakan dengan DBMS(Database Management System)

    - Database Management System
    
        Software yang dapat digunakan oleh user untuk berkomunikasi dengan data yang ada dalam media penyimpanan. 
        
        ![image](https://user-images.githubusercontent.com/113356785/200208965-03fa045f-770e-4ffd-874a-94541bcc7e9b.png)
        
        Tipe utama pada Database management System antara lain, Hierarchical, Network, Relational, Non Relational, and Object Oriented.

    - Istilah pada Database
    
        - Table
        
            Kumpulan value yang dibangun oleh baris dan kolom, yang didalamnya berisikan atribut dari sebuah data.
            
            ![image](https://user-images.githubusercontent.com/113356785/200209171-53081307-9d0b-42eb-83a0-4730d42c3beb.png)

        - Field
            
            Kolom dari sebuah tabel dimana masing-masing field memiliki tipe data masing-masing.
            
            ![image](https://user-images.githubusercontent.com/113356785/200209254-95c18764-1834-4f6f-8925-371825ab0394.png)

      
        - Record
        
            Kumpulan nilai yang saling terkait. Record merupakan isi dari sebuah tabel.
            
            ![image](https://user-images.githubusercontent.com/113356785/200209343-3a75b91b-7dd0-4d24-a0e4-0b7218ba9d84.png)
            
            ![image](https://user-images.githubusercontent.com/113356785/200209421-cc8319ed-8747-472b-9e4d-3af99f8b47d4.png)
            
            
     - SQL
     
        Structured Query Language merupakan suatu bahasa (Language) yang digunakan untuk mengakses database. SQL adalah Bahasa Query yang digunakan untuk melakukan interaksi di RDMS (Relational Database Management System). 
        
        - Membuat, Menampilkan dan menghapus data didalam database.
        
        - Mengatur “Permission” (siapa saja yang bisa mengakses data).
        
        - Membuat dan menghapus Database.
        
        
    - SQL Table Join
    
        Join, adalah penggabungan tabel yang dilakukan melalui kolom/key tertentu yang memiliki nilai terkait untuk mendapatkan satu set data dengan informasi lengkap.
        
        ![image](https://user-images.githubusercontent.com/113356785/200210270-4de10944-0b6e-419d-a69e-83946f39bed6.png)
        
        - Inner Join : menampilkan data hanya yang sesuai di kedua tabel.
        
          ![image](https://user-images.githubusercontent.com/113356785/200210401-3fe5d1fa-f025-4af2-83ac-ab05b8c4d590.png)
          
        - Left Join : menampilkan semua data sebelah kiri dari tabel yang di joinkan dan menampilkan data sebelah kanan yang cocok dengan kondisi join. Jika tidak ditemukan kecocokan, maka akan di set NULL secara otomatis
        
            ![image](https://user-images.githubusercontent.com/113356785/200210485-a65a8957-4639-4abf-aa25-e5b415bf7c56.png)
            
         - Right Join : menampilkan semua data sebelah kanan dari tabel yang di joinkan dan menampilkan data sebelah kiri yang cocok dengan kondisi join. Jika tidak ditemukan kecocokan, maka akan di set NULL secara otomatis. 
         
            ![image](https://user-images.githubusercontent.com/113356785/200210573-c2e50bca-8e4f-4e31-834c-cd2e95572b87.png)

    
    - DDL (Data Definition Language)
    
        Kumpulan perintah SQL yang digunakan untuk membuat, mengubah dan menghapus struktur dan definisi metadata dari objek-objek Database. 
        
        ![image](https://user-images.githubusercontent.com/113356785/200209846-f56a33e5-a0ee-4dd8-a50b-552ce8858383.png)

        - ALTER
        
            Digunakan untuk mengubah struktur dari tabel yang ada, seperti untuk menambahkan atau menghapus kolom/field.
            
            ![image](https://user-images.githubusercontent.com/113356785/200210023-1b8d81c8-7427-4e6a-8823-e39a3a220f3d.png)
            
        - DROP
        
            Digunakan untuk menghapus Database, Table, dan View atau Index.
            
            ![image](https://user-images.githubusercontent.com/113356785/200210126-77ebab3f-0cd9-40b1-8a38-5081df53b057.png)
            
            
    - NoSQL
    
        Database NoSQL adalah database yang tidak memiliki perintah SQL. Konsep penyimpanannya semi struktural atau tidak struktural, dan tidak harus memiliki relasi layaknya tabel-tabel MySQL. 
        
        *Kelebihan NoSQL di banding Relasional Database.*
        
        
         - NoSQL bisa menampung data yang terstruktur, semi terstruktur dan tidak terstruktur.
            
         - Menggunakan OOP dalam pengaksesan/manipulasi data.
            
         - NoSQL tidak mengenal schema tabel yang kaku.


    - Apa itu MySQL ?

        MySQL adalah sistem manajemen basis data relasional open source berbasis SQL. Itu dirancang dan dioptimalkan untuk aplikasi web dan dapat berjalan di platform apa pun. Sebagai persyaratan baru dan berbeda muncul dengan internet, MySQL menjadi platform pilihan untuk pengembang web dan aplikasi berbasis web.
        
    - Data type SQL
    
      - Number 
      
        Tipe data Number adalah data yang berisi kumpulan karakter angka

        ![image](https://user-images.githubusercontent.com/113356785/200215866-757cff71-f9e8-4a47-939e-54fcb5c0056b.png)
        
      - String
      
        Tipe data string adalah tipe data berupa kumpulan karakter termasuk karakter simbol
        
        ![image](https://user-images.githubusercontent.com/113356785/200216114-0fba9676-7e24-4eab-a6bd-3fad45578d1f.png)

      - boolean
        
        Tipe ini hanya menyimpan 2 tipe data yaitu TRUE dan FALSE, dan dapat di convert menjadi int dengan representasi TRUE = 1, dan FALSE = 0
        
      - Date time
        
        Tipe ini merupakan tipe data untuk menyimpan tanggal dan waktu

        ![image](https://user-images.githubusercontent.com/113356785/200216307-72128f32-6612-44ad-aadd-261428e6c71b.png)
        
        
      - Other data type

         ![image](https://user-images.githubusercontent.com/113356785/200216384-16369ca6-7cdd-46af-b764-f7aea26f156a.png)

    - melakukan manipulasi query sederhana


![image](https://user-images.githubusercontent.com/113356785/200216943-ffc9a0d5-ba13-4334-b59b-1d2f5808cc2a.png)

![image](https://user-images.githubusercontent.com/113356785/200217001-fc29998b-02fd-4085-a7e0-978f7f27c3be.png)

![image](https://user-images.githubusercontent.com/113356785/200217050-4ef5beaa-62bd-40cd-bfad-43716f3834ff.png)

![image](https://user-images.githubusercontent.com/113356785/200217121-2441a40a-1a39-40de-bdea-464db7383b7d.png)

![image](https://user-images.githubusercontent.com/113356785/200217159-a7572cd5-0811-4477-b740-1cabb3596a3c.png)

![image](https://user-images.githubusercontent.com/113356785/200217222-d42d28c4-e9be-47ee-8a27-84a3ba14212b.png)

Perintah alter table produk

  > change Type_Pr Merek_Pr varchar(19) not null; 
    
   *merupakan perintah yang digunakan untuk memanipulasi tabel yaitu mengubah nama field / kolom pada tabel.*
    
  > mysql> alter table produk
  > add Profit int(19) not null
  > after Harga; 
    
*Yaitu perintah untuk penambahan field bernama Profit pada tabel yang diletakkan setelah filed Harga. Sedangkan perintah mysql> alter table produk -> drop profit; merupakan perintah untuk menghapus field pada tabel.*

  > mysql> alter table produk -> alter Status drop default; 
  
   *merupakan perintah untuk menghapus nilai / isi default yang telah ditetapkan sebelumnya*
    
  > mysql> alter table produk -> alter Status set default 'ada'; 
  
   *merupakan perintah untuk menambah isi / nilai default pada suatu field yang telah dibuat sebelumnya.*

 *Primary key* dimaksudkan untuk menjadi kolom utama sebuah tabel yang isinya tidak boleh sama dengan yang lainnya, jika terjadi rududansi atau penggandaan data maka proses tersebut akan ditolak oleh database, dan kolom ini tidak boleh kosong (not null).

 *Unique Key* ini sebenarnya hampir sama dengan fungsi primary key, maksudnya adalah apabila primary key yang dibuat pada suatu tabel adalah merupakan autonumber (angka yang bertambah terus-menerus ketika proses insert data, sehingga tidak dimungkinkan terdapat nilai yang sama), dikarenakan tidak diperbolehkan ada dua primary key maka dapat dibantu oleh unique key ini sebagai penanda unique-nya sebuah record dengan record lain. Dalam sebuah tabel diperbolehkan lebih dari satu unique key.

 *auto_increment* merupakan atribut tipe data numeric yang memungkinkan kolom memiliki nilai yang berurutan dan secara otomatis dihasilkan oleh MySQL sendiri tanpa harus didefinisikan eksplisit dalam perintah MySQL.


# DAY 2
- ## MySQL Lanjutan

- Relations di SQL

  - One to Many
    
    Paling Sering Digunakan, Satu baris dalam tabel dapat memiliki beberapa baris di table relasinya
    
    ![image](https://user-images.githubusercontent.com/113356785/200221502-5a4b8fab-68ab-4d6a-a5ba-56fb1767cc64.png)
    
  - Many to Many

     Digunakan ketika kedua tabel yang berelasi dapat memiliki beberapa baris di tabel relasinya.

    ![image](https://user-images.githubusercontent.com/113356785/200221580-e7225e0f-fe5e-4172-b146-03fd920aca1a.png)
    
  - One to One

    Sangat jarang digunakan, Diimplementasikan dengan cara yang sama seperti One to Many tetapi dengan kondisi tambahan (foreign key merupakan primary key).
    
    ![image](https://user-images.githubusercontent.com/113356785/200221859-3528f9ad-879b-42a4-9192-607930d73073.png)
    
   
# DAY 3

- ## Authentication & Authorization in Express

- Authentication adalah verivikasi siapa anda

    Authentication adalah proses dimana seorang user (melalui berbagai macam akses fisik berupa komputer , melalui jaringan , atau melalui remote access ) mendapatkan hak akses kepada suatu entity (dalam hal ini jaringan suatu corporate). Seorang user melakukan login kedalam suatu infrastruktur jaringan dan sistem mengenali user ID ini dan menerimanya untuk kemudian diberikan akses terhadap resources jaringan sesuai dengan authorisasi yang dia terima.
    
    ![image](https://user-images.githubusercontent.com/113356785/200319910-3413170c-da6d-477f-983a-d9ac27a08feb.png)


    Authentication bergantung pada satu atau lebih faktor untuk memverifikasi identitas, dan faktor-faktor ini datang dalam tiga jenis utama:
    
     - Knowledge, sesuatu yang Anda ketahui, seperti nama pengguna dan kata sandi.

     - Possession, sesuatu yang Anda miliki, seperti kartu keamanan atau perangkat seluler
        
     - Inherence, sesuatu tentang Anda, yang umumnya mengacu pada data biometrik seperti sidik jari.
     
     ![image](https://user-images.githubusercontent.com/113356785/200321199-bdcb80ce-8c15-44ed-92c9-f6b4c84b0f65.png)

     
     
  Authentication bergantung pada satu faktor, seperti kombinasi nama pengguna/sandi sederhana, disebut Authentication Satu Faktor, dan menjadi semakin tidak aman.


![image](https://user-images.githubusercontent.com/113356785/200318081-8ce30952-c629-4297-ba36-67b23635482a.png)

![image](https://user-images.githubusercontent.com/113356785/200318218-9ec45fd4-7aa1-4267-9b19-82e9f70cf17d.png)


 - Authorization adalah verifikasi atas apa yang boleh Anda lakukan.
 
    Authorization adalah proses penentuan apakah user tersebut diijinkan / ditolak untuk melakukan satu atau beberapa action atau akses terhadap resources tertentu dalam system. User login terhadap system dengan menggunakan user-ID dan password, kemudian system mengenalinya dan user mendapatkan akses atau ditolak terhadap suatu resource system tertentu.
    
      Authorization sangat penting untuk keamanan web, dan bertanggung jawab atas segala hal mulai dari mencegah pengguna memodifikasi akun satu sama lain, melindungi aset back-end dari penyerang, hingga memberikan akses terbatas ke layanan eksternal.

    
    ![image](https://user-images.githubusercontent.com/113356785/200320278-7e43b487-0076-437e-859f-63fe02ab5381.png)
    
    Hubungan antara client,server,authentication dan authorization system bisa dilihat pada gambar di atas. Client sebelum bisa menikmati layanan server harus melalui proses authentication. Setelah authentication berhasil akan terjalin hubungan trust antara client dan server sehingga cukup sekali saja authentication sampai client logout/keluar. Selanjutnya setiap ada permintaan layanan, server akan menghubungi system authorization untuk menentukan apakah client tersebut berhak atas layanan yang dimintanya.
    
  > Salah satu alat inti untuk menegakkan otentikasi dan otorisasi adalah enkripsi. Enkripsi adalah proses mengubah data menjadi format yang tidak dapat dibaca kecuali Anda memiliki kunci yang benar untuk mendekripsinya. 
  
  - Enkripsi datang dalam dua jenis utama:
  
      - Symmetric encryption
      - Asymmetric encryption
      
      ![image](https://user-images.githubusercontent.com/113356785/200321080-190f74f9-68c0-4e28-9c72-f279d3407639.png)
      
      
- ## JavaScript Authentication

- membuat authentication dan authorization

![image](https://user-images.githubusercontent.com/113356785/200321696-0a635f33-c7e5-4ff7-bae3-62c0459bdb87.png)

Pada contoh diatas, kita menggunakan local strategy.


![image](https://user-images.githubusercontent.com/113356785/200321853-c61b706e-6b6a-4e29-894e-aa26b9ca48c2.png)


Pada contoh diatas, secara default, setelah authentication success, user akan dilempar ke halaman homepage. Jika gagal akan dikembalikan ke login page.


![image](https://user-images.githubusercontent.com/113356785/200322035-5eb5c9cb-b7ec-4ac6-855f-13ba820dbed9.png)


Secara default, failure flash akan memiliki nilai true, untuk memberi informasi kepada user jika authentication gagal.


![image](https://user-images.githubusercontent.com/113356785/200322164-8a186595-de48-44a0-af34-c0fe8c8e25ff.png)


Kita dapat menonaktifkan session pada routes API.


![image](https://user-images.githubusercontent.com/113356785/200322313-268a7d77-692a-494a-afbf-eae70d002d6b.png)


Contoh konfigurasi dengan menggunakan LocalStrategy.


# DAY 5

- ## Sequelize

    Sequelize adalah ORM (Object Relational Mapping) Node JS yang berbasis promise. Sequelize mendukung sebagian besar relational Database seperti MySQL, PostgresQL, MariaDB, SQLite dan Miscrosoft SQL Server.

    Dengan fitur fitur di Sequelize, kita bisa mengelola dan mengatur data di database kita dengan cepat, dan efisien.

    *ORM adalah suatu metode/teknik pemrograman yang digunakan untuk mengkonversi data dari lingkungan bahasa pemrograman berorientasi objek (OOP) dengan lingkungan database relational.*
    
    Sequelize bisa digunakan dengan PostgreSQL, MySQL, MariaDB, SQLite, dan MSSQL.

![image](https://user-images.githubusercontent.com/113356785/200324077-2586cafb-61a3-4d16-9f58-e3c7a851cd9e.png)


  - Setting Up Connection

    ![image](https://user-images.githubusercontent.com/113356785/200324209-278c4418-0372-4561-8c0c-7f0a2a518fd3.png)


   - Express with Sequelize

     ![image](https://user-images.githubusercontent.com/113356785/200324343-59ec81dc-52a2-45f7-b6a6-b9e99d3bc639.png)

       *Opsi dialect adalah database yang kita gunakan yaitu sqlite, dan storage merupakan opsi khusus dari sqlite yaitu path tempat databasenya nanti disimpan.*
        
        
      ![image](https://user-images.githubusercontent.com/113356785/200324587-d4ea917c-6a6f-440b-8418-af4d8267531e.png)


       Fungsi authenticate() akan melakukan ping ke database jika berhasil maka akan mengembalikan object promise yang bisa then (berhasil) atau catch (tidak berhasil)
          
        sync() berfungsi untuk melakukan sinkronisasi model dengan database, 
          
        sync() return promise dengan callback dipanggil ketika sudah melakukan sinkronisasi.
