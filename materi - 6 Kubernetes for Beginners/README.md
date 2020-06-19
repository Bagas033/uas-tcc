<h1> Materi-06 Kubernetes For Beginners </h1>

1. Melakukan clonning repo dari git dockercoins.
![g1](g1.jpg) 

2. Selanjutnya masuk pada direktori dockercoins dan kemudian menjalankan perintah docker-compose up, untuk menjalankan semua container yang ada pada dockercoins.
![g2](g2.jpg) 

3. Melihat cluster kita. apakah semuanya sudah terkoneksi pada server yang sama atau tidak.
![g3](g3.jpg)

4. Melakukan ping pada server image docker alpine pada 0.0.0.0 .
![g4](g4.jpg)


5. Masuk ke direktori stacks, kemudian membuka file dockercoins.yml lalu melakukan push.
![g5](g5.jpg)

6. Melihat hasil deploy pada rng dan worker
![g6](g6.jpg)

7.  Melihat hasil deploy pada port server redis 6379, pada server rng di port 80 dan server hasher di port 80
![g7](g7.jpg)

8. Melihat logs deploy worker, melakukan cek service node port pada tcp 80 dan port 30001 serta menampilkan svc
![g8](g8.jpg)

9. Melakukan export rng menjadi file yml dan menampilkannya
![g9](g9.jpg)

10. Melakukan running rng ,melihat describe rng dan selanjutnya melakukan update rng serta menjalankannya.
![g10](g10.jpg)

