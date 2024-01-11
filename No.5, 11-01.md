5.  menggunakan perintah gif melalui cmd
   
    **jawab:**
    
     Membuat repository lokal dan menghubungkan dengan Github:
     
    ![Github3](https://github.com/cayyaa/labsmkn/assets/156055082/a571ce93-fe18-40ce-9e68-0abbae229bd7)

    -Perintah baris pertama untuk memastikan kita berada pada folder project android kita
    
    -Perintah baris kedua berguna untuk membuat repositori baru pada folder saat ini
    
    -Sedangkan baris perintah ketiga untuk menambahkan semua file yang telah kita buat pada stagging area
    
    -Perintah baris ke 4 dan 5 hanya dijakanlan jika ini adalah pertama kali kita melakukan operasi git (setelah instalasi git client), perintah tersebut digunakan untuk mengeset nama dan email yang diasosiasikan dengan pemakaian git
    
    -Perintah baris ke 6 Untuk menyimpan perubahan di repository lokal
    
    -Sedangkan baris perintah ke 7 digunakan untuk menghubungkan repositori lokal kita dengan repositori github
    
    -Terakhir baris perintah ke 8 digunakan untuk meng-upload semua pekerjaan kita ke Github
     
      Melakukan perubahan dan mengupload perubahan source code:
  
     ![Github4](https://github.com/cayyaa/labsmkn/assets/156055082/0bdbec48-d98d-4846-b81d-825313d398a5)

     Ketiga perintah tersebut berarti adalah menambahkan hasil pekerjaan ke stagging area, menyimpan perubahan pada repositori lokal, dan mengupload perubahan ke Github. Ketiga perintah ini kemungkinan adalah perintah git yang paling sering kita eksekusi.

    
Inisialisasi Repositori:

Membuat repositori Git baru:

![1](https://github.com/cayyaa/Labsmkn/assets/156055082/323a519a-7ee9-4082-9d57-389822153175)

Menambahkan dan Mengonfirmasi Perubahan:

Menambahkan file ke indeks (staging area):

![2](https://github.com/cayyaa/Labsmkn/assets/156055082/c4f9d8d5-af7e-46ee-8314-49bdbfdd87bb)

Menambahkan semua perubahan:

![3](https://github.com/cayyaa/Labsmkn/assets/156055082/2c7d9fef-d2f0-40da-90a9-4e5010d83249)

Membuat commit dengan pesan:




Melihat Status dan Riwayat:

Melihat status perubahan:
lua
Copy code
git status
Melihat riwayat commit:
bash
Copy code
git log
Cabang (Branch):

Membuat cabang baru:
Copy code
git branch nama_cabang
Pindah ke cabang tertentu:
Copy code
git checkout nama_cabang
Sinkronisasi dengan Repositori Jarak Jauh:

Menambahkan repositori jarak jauh:
csharp
Copy code
git remote add origin url_repositori
Mengambil perubahan dari repositori jarak jauh:
Copy code
git pull origin nama_cabang
Mengirim perubahan ke repositori jarak jauh:
perl
Copy code
git push origin nama_cabang
Menggabungkan Cabang:

Pindah ke cabang tujuan:
Copy code
git checkout cabang_tujuan
Menggabungkan cabang ke cabang tujuan:
sql
Copy code
git merge nama_cabang
Membatalkan Perubahan:

Membatalkan perubahan yang belum di-commit:
lua
Copy code
git checkout -- nama_file
Membatalkan commit terakhir (hati-hati dengan perintah ini):
perl
Copy code
git reset HEAD~1
Itu adalah beberapa perintah Git dasar yang dapat Anda gunakan di Command Prompt. Pastikan untuk menggantikan "nama_file", "nama_cabang", dan "url_repositori" dengan nilai yang sesuai untuk proyek Anda. Juga, penting untuk berhati-hati saat menggunakan perintah yang dapat mengubah sejarah commit, seperti git reset.

