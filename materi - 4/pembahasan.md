<h1> Materi-04 Docker Orchestration Hands-on Lab </h1>

1. Membuat container baru yang dijalankan pada node 1, perintah berikut berguna untuk membuat container baru yang akan tetap berjalan pada background image docker saat sleep.
![g1](g1.jpg) 

2. Melakukan cek apakah container tersebut sudah berjalan.
![g2](g2.jpg) 

3. Membuat Swarm baru, dan join dengan single node lalu melakukan verifikasi jika operasi berhasil.
![g3](g3.jpg)

4. Melakukan join swarm untuk node 2 dan node 3 dengan menggunakan token yang didapat dari pembuaatan swarm sebelumnya.
![g4](g4.jpg)
![g4.2](g42.jpg)

5. Setelah melakukan join node2 dan node3, kemudian kembali ke node1, dan jalankan perintah docker node ls untuk memastikan bahwa kedua node tersebut sudah join ke Swarm.
![g5](g5.jpg)

6. Dari node 1 akan melakukan deploy sleep pada docker swarm. Deploy merupakan layanan dari docker swarm.
![g6](g6.jpg)

7.  Mereplika pada container sleep-app , ini berguna untuk mendeskripsikan container pada layanan service.
![g7](g7.jpg)

8. Mereplika layanan kembali menjadi hanya 4 container(melakukan pembaruan layanan docker container).
![g8](g8.jpg)

9. Mengecek status node yang berjalan pada node 1.
![g9](g9.jpg)

10. Melihat container yang berjalan pada node 2.
![g10](g10.jpg)

11. Kembali ke node 1 untuk mengambil node 2 dari layanan service. node 2 akan digunakan untuk melakukan drain dimana akan menggantikan node kita dengan node 2.
![g11](g11.jpg)

12. kembali ke node 2, dan jalankan perintah docker ps. hasilnya container pada node 2 sudah tidak berjalan lagi.
![g12](g12.jpg)

13. Kemudian menghapus layanan service pada node 1.
![g13](g13.jpg)

14. Kemudian menjalankan perintah docker ps pada node 1 untuk melihat daftar container yang sedang berjalan.
![g14](g14.jpg)

15. Kemudian menghapus semua swarm container untuk node 1, node 2 dan node 3.
