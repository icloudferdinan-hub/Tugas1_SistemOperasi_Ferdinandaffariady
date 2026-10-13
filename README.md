1. Buatlah laporan proses instalasi di komputer mahasiswa dan tampilkan screenshot-nya

Tahap 1:
<img width="1887" height="946" alt="image" src="https://github.com/user-attachments/assets/01a4a396-f1af-4eef-9b31-b4fcc956a2bc" />

Tahap 2: 
<img width="1786" height="744" alt="image" src="https://github.com/user-attachments/assets/ca6a2fdc-4c7e-41f6-9301-216b11783395" />
  
Tahap 3: 
<img width="1188" height="820" alt="image" src="https://github.com/user-attachments/assets/9c68c692-5cd0-4d73-bd2f-3c19e240cc93" />

Tahap 4: 
<img width="1440" height="903" alt="image" src="https://github.com/user-attachments/assets/e4a9c4a9-868b-498a-8e04-ad3c09fe0445" />

2. Analisislah pada gambar kenapa saat instalasi perlu dipilih “/” pada opsi Mount Point?

Jawab: Mount Point “/” perlu digunakan karena merupakan root directory atau direktori utama dalam sistem Linux. Root berfungsi sebagai tempat awal penyimpanan berbagai direktori penting seperti /etc, /usr, /var, dan /home. Dengan adanya Mount Point “/”, sistem operasi dapat memiliki lokasi utama untuk menyimpan dan menjalankan seluruh komponen sistem. Selain itu, installer Linux mutlak memerlukan mount point / untuk meletakkan kernel Linux serta berkas-berkas dasar sistem. Tanpa menentukan mount point /, proses instalasi tidak dapat dilanjutkan karena sistem tidak mengetahui di mana harus memasang berkas utama agar komputer dapat melakukan booting dan menjalankan sistem operasi dengan benar.

3. Berikan penjelasan tentang ext4, ext3, swap, ntfs, fat32,btrfs !

Jawab: • ext3 (Third Extended Filesystem): Sistem file pada Linux yang digunakan sebelum ext4. Ext3 memiliki fitur journaling yang berguna untuk menjaga konsistensi dan keamanan data apabila terjadi gangguan seperti mati listrik atau sistem mengalami crash.

• ext4 (Fourth Extended Filesystem): Pengembangan dari ext3 yang menawarkan performa, kapasitas penyimpanan, dan kemampuan pengelolaan file yang jauh lebih baik. Ext4 merupakan sistem file standar yang paling umum digunakan pada sistem operasi Linux saat ini.

• swap: Bagian dari media penyimpanan (harddisk/SSD) yang dialokasikan sebagai memori virtual. Swap membantu sistem menampung data sementara ketika kapasitas RAM fisik yang tersedia sudah tidak mencukupi untuk menjalankan proses.

• NTFS (New Technology File System): Sistem file utama yang dikembangkan oleh Microsoft dan banyak digunakan pada sistem operasi Windows modern. NTFS mendukung penyimpanan file berukuran besar serta dilengkapi fitur keamanan seperti file permission, enkripsi, dan journaling.

• FAT32 (File Allocation Table 32): Sistem file format lama yang memiliki tingkat kompatibilitas sangat tinggi lintas platform (Windows, Linux, macOS, hingga perangkat portabel). Namun, FAT32 memiliki keterbatasan utama, yaitu tidak dapat menyimpan file tunggal yang berukuran lebih dari 4 GB.

• btrfs (B-tree File System): Sistem file Linux modern berbasis Copy-on-Write (CoW) yang menyediakan fitur tingkat lanjut seperti snapshot, kompresi data otomatis, pengecekan integritas data (checksumming), dan manajemen subvolume. Cocok digunakan untuk pengelolaan data yang fleksibel dan pemulihan sistem yang cepat.
