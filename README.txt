
Script Pembuat Artikel
=======================

Instalasi
------------

Sebelum mengunggah skrip ke server Anda, Anda perlu membuat beberapa perubahan pada file berikut:
(PENTING: edit semua file ini menggunakan PLAIN TEXT EDITOR mis. Notepad. JANGAN mengeditnya menggunakan editor teks kaya seperti WordPad atau MS-Word.
Anda juga dapat menggunakan alat hebat ini: https://notepad-plus-plus.org/download/ untuk mengedit file php, gratis untuk mengunduh)

- go.php
  PENTING! Edit baris 44: $ baseurl = "https://patiku.xyz/";
  ubah url di atas ke url tempat Anda akan mengunggah skrip i.e "http://domainanda.com/" atau "http://sub.domainanda.com/"
  misalnya jika Anda mengunggah skrip ke http://yourwebsite.com/articlecreator/
  maka Anda harus mengubah baris itu ke $ baseurl = "http://yourwebsite.com/articlecreator/";
  sertakan tanda garis miring "/" di akhir url.
  
- accesskey.php
  Kami telah menetapkan kunci akses default ke "AccessKey1" dan "AccessKey2".
  Edit file ini jika Anda ingin menambah, menghapus atau mengedit kunci akses
  
- unikdata.txt (opsional)
  File ini berisi basis data sinonim, edit file ini untuk mengedit dan meningkatkan fitur rewriter.
  Anda dapat dengan mudah menambah, mengedit, menghapus sinonim.
  
Setelah Anda memodifikasi file di atas, unggah semua file dan folder, simpan semua nama file & direktori beserta strukturnya.
Pastikan folder "cache" & "foldertemp" dapat ditulis (777).

Kami menyertakan systemtest.php untuk memeriksa kompatibilitas server Anda.
Jika Anda telah mengikuti langkah-langkah di atas tetapi skrip tidak berfungsi, akses systemtest.php dengan browser Anda, mis. http://domainanda.com/systemtest.php
Halaman ini akan menunjukkan kepada Anda modul PHP apa yang perlu Anda instal / aktifkan di server Anda. Modul PHP tersebut diperlukan oleh ArticleCreator.
Jika Anda tidak memiliki akses atau tidak dapat menginstalnya, cukup hubungi server / penyedia hosting Anda untuk menginstal modul php yang diperlukan.
 

Jika Anda memiliki masalah, kirim email Anda ke mightyfaucet@gmail.com