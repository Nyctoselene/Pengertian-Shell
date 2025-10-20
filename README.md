# Pengertian Shell

<h3>Apa itu Shell?</h3>
Shell merupakan program yang mengambil command dari keyboard dan memberikannya kepada Sistem Operasi (OS) untuk dijalankan. Dahulu kala, shell merupakan satu-satunya User Interface (UI) yang tersedia pada Unix-like system seperti Linux. Sekarang kita mempunyai Graphical User interface (GUI) selain Command Line Interface (CLI) seperti Shell.

Pada bagian besar sistem Linux, program bernama `bash` (singkatan daari Bourne Again SHell, versi yang ditingkatkan dari program shell asli unix yang ditulis oleh Steve Bourne) berfungsi sebagai program shell. Selalin `bash`, terdaat program shell lain yang tersedia pada sistem Linux. Diantaranya adalah `ksh`, `tsch`, dan `zsh`.

Kali ini kita akan membahas tentang Shell pada Linux

<h3>Cara Kerja Shell</h3>

Berikut adalah langkah-langkah detail tentang cara kerja shell:
1. User memberikan command.
2. Shell membagi command menjadi kata-kata individu.
3. Shell mencari file executable dengan nama yang sama dengan command pada lingkungan PATH.
4. Shell menjalankan program dan memberikan argumen serta input yang diperlukan.
5. Program berjalan berdasarkan masukan dan mengembalikan status exit di akhir.
6. Shell menampilkan output di layar.
7. Shell menunggu command baru.

<h3>Command-Line Shell dan Graphical Shell</h3>

Shell Linux secara umum dibagi menjadi 2 jenis:

1. Command Line Shell
   • Menggunakan interface text-based
   • Lebih fleksibel dan powerful, terutama dalam scripting
   • Memerlukan pengetahuan tentang command dan penggunaannya
   • Lebih cepat untuk bekerja dengan set data besar atau task berulang
   • menggunakan interface text-based
2. Graphical Shell
   • Menggunakan Graphical User Interface (GUI) 
   • Cocok untuk semua jenis user
   • Bisa drag and drop
   • Menyediakan berbagai aplikasi mulai dari web browser hingga media player.
   • Melmiliki banyak shortcut keyboard dan fitur berbasis GUI.

<h3>Jenis-jenis Shell untuk Sistem Linux</h3>
Saat ini, ada beberapa jenis Shells yang tersedia untuk sistem linux. Berikut ini beberapa diantaranya

1. Bourne Shell (sh)
   Digunakan untuk menjalankan basic command dan script.

2. Bourne Again Shell (bash)
   Merupakan versi uang ditingkatkan dari Bourne Shell. Ia memiliki fitur seperti command-line editing, job control, history serta support untuk script tingkat lanjut.
   
3. C Shell (csh) 
   Memiliki syntax mirip dengan bahasa pemrograman C. Shell ini juga menyediakan fitur seperti command-line editing, job control, dan history.

4. Korn Shell (ksh)
   Merupakan versi yang ditingkatkan dari Burne Shell. Shell ini juga menyediakan fitur-fitur lanjutan.
  
6. Z Shell (zsh)
   Shell ini menggabungkan fitur dari Bourne, C, dan Korn Shells. Selain itu, ia juga menyediakan fitur kanjutan seperti Spelling correction dan advanced globbing. Globbing membantu menentukan beberapa file atau direktori tanpa perlu mengetikkan nama mereka.

 7. Fish Shell (fish)
    Shell ini menawarkan interface yang lebih user firendly. Selain itu, ia juga dilengkapi dengan fitur seerti text highlighting.

<h3>Pengertian Terminal</h3>
Terminal merupakan text-based intereface yang memungknkan user untuk berinteraksi dengan komputer mereka dengan memasukkan command. Terminal berfungsi sebagai program pembungkus yang menyediakan lingkungan untuk menjalankan command, yang kemudain diproses oleh shell. Terminal sendiri adalah sebuah program dan dapat diinstall, dihapus, atau diganti dengan program terminal lainnya. 

Dengan kata lain, terminal adalah "window" tempat mengetikkan command, dan komputer memprosesnya

<h3>Terminal VS Shell</h3>
Beberapa orang berpikir bahwa terminal dan shell merupakan hal yang sama. Namun, keduanya berbeda satu sama lain

Terminal dapat berupa fisik atau virtual. Ini adalah text-based interface yang memungkinkan user untuk memasukkan command dan menampilkannya. Sedangkan Shell merupakan program yang menginterpretasikan perintah yang dimasukkan melalui terminal dan menyediakan cara untuk berinteraksi dengan sistem operasi

<h3>Keuntungan dari Shell</h3>
Shell di Linux menawarkan beberapa keuntungan, menjadikannya esensial untuk berinteraksi dengan sistem operasi

1. Command Execution
   Memungkinkan user untuk menjalankan command, shell menyediakan cara yang efisien dan lebih cepat untuk melakukan task dan mengontrol proses sistem.

2. Automation and Scripting
   Shell Linux mendukung bahasa pemrograman script, memungkinkan user untuk mengotomatisasi task-task repetitif dan membuat program untuk masalah yang kompleks.

3. Flexibility and Control
   Shell memberikan kontrol dan keleluasaan yang llebih besar dengan memungkinkan user menjalankan shell script dalam lingkungan shell saat ini.

4. Accesibility
   Shell dapat digunakan secara remote, dan sistem Linux dapat dikelola dari mana saja dengan koneksi internet.

<h3>Pengertian Shell Scripting</h3>
Shell scripting di Linux adalah pembuatan urutan perintah yang ditulis dalam bahasa pemrograman khusus shell untuk diinterpretasikan. Tujuan utama Shell scripting adalah untuk mengotomatisasi task dan menjalankan task repetitif dengan cepat dan efisien. Elemen dasar adalah daftar perintah yang disusun sesuai urutan eksekusi. Berkas yang berisi daftar perintah dan dieksekusi disebut Shell scriot atau Shell program. Setiap Shell scriot disimpan dengan ekstensi file “.sh”, misalnya, my_script.sh.

Shell script memiliki syntax seperti bahasa pemrograman lainnya. Terdapat uji kondisi dan loop yang membantu user dalam menangani data besar, dan shell juga dapat menyertakan fungsi. Shell script berkualitas memiliki komentar yang diawali dengan tanda “#”, yang menjelaskan setiap langkah.

<h3>Keuntungan Shell Script pada Linux</h3>
Penggunaan Shell script memiliki banyak manfaat. Beberapa diantaranya sebagai berikut:

1. Portabel
   Shell script yang dikembangkan di satu mesin dapat dijalankan di mesin lainnya.

2. Cepat
   Lebih cepat daripada interface grafis (GUI).

3. Menggunakan Sumber Daya Lebih Sedikit
   Membutuhkan sumber daya komputer yang lebih sedikit untuk dijalankan, sedangkan GUI mengonsumsi banyak sumber daya.

4. Bagus untuk Automation and Scripting
   Lebih fleksdibel, efisien, dan bertenaga untuk Automation adn Scripting.

<h3>Kekurangan Shell Script pada Linux</h3>
Penggunaan Shell script di Linux juga memiliki beberaa kekurangan:

1. Kurang Intuitif
   Shell script kurang intuitif dibandingkan interface grafis (GUI). Sulit untuk memahami apa yang sedang terjadi.

2. Tidak Ramah Pemula
   Membutuhkan kurva pembelajaran yang curam. Itulah mengapa tidak cocok untuk semua jenis pengguna.

3. Tidak Se-powerful Bahasa Pemrograman
   Bahasa pemrograman lebih cepat daripada Shell script. Selain itu, bahasa pemrograman menyediakan banyak fungsi dan fleksibilitas yang lebih besar daripada Shell script.

Sekian yang dapat saya sampaikan, mohon maaf apabila ada salah kata atau kekurangan dalam penyampaian. Akhir kata, Wassalam
