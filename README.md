# UAS membuat package dan modul
# Nama : Taufik Eka Albani
# Nim  : 312210347
# Kelas: TI.22.A3

## Link youtube : https://youtu.be/gqjGC-yREGA
## File PDF     : [UAS_packagedanmodul.pdf](https://github.com/taufikalbani13/lab2py/files/10373655/UAS_packagedanmodul.pdf)



# Penjelasan
 
 Membuat code program : `daftar_nilai.py` 
  
 

Penjelasan : 
•	Disini kita menggunakan dictionary ya untuk menyimpan inputan data mahasiswa 
•	Def tambahkan : Dibagian ini kita gunakan print untuk penulisan bagian input data mahasiswa nanti agar terlihat rapih • Def hapus :  
•	Disini kita buat inputan yang menginput nama o Gunanya untuk menghapus data mahasiswa dari nama mahasiswa itu sendiri o Kita gunakan del untuk fungsi menghapus datanya o (If)Jika mahasiswa tersebut ada maka data mahasiswa tersebut akan terhapus o (Else)Jika nama mahasiswa tersebut tidak ada maka datanya tidak akan ditemukan 
 
•	Def ubah 
Penjelasan: 
o	Disini kita hampir sama dengan yang hapus, kita gunakan inputan nama untuk mengubah NIM, Nilai Tugas, Ujian Tengah Semester(UTS), ataupun Ujian Akhir 
Semester(UAS) o Lalu setelah kita memasukkan nama maka dictionary akan mengeksekusi program menggunakan keys untuk mencari data dari nama mahasiswa tersebut 
o	(If)Jika nama mahasiswa tersebut ketemu atau ada didalam data maka program akan masuk ke inputan NIM, Nilai Tugas, Nilai UTS, dan Nilai UAS yang baru 
o	(Else)Jika nama mahasiswa tersebut tidak ada didalam data maka program akan memunculkan tulisan atau perintah bahwa data mahasiswa tidak ada. 
 
•	Def cari 
Penjelasan: 
•	Fungsinya sama dengan Def tambahkan 
 
 Membuat code program `input_nilai.py` 
 
 
Penjelasan: • From dan import Penjelasan: 
•	From digunakan untuk memanggil package sementara import untuk tujuan yang kita pilih yaitu modul daftar_nilai 
•	Lalu kita gunakan import data_mahasiswa itu gunanya agar saat kita menginputkan data atau setiap kali kita menambah data maka data mahasiswa secara otomatis akan masuk kedalam dictionary meskipun beda atau terpisah package dan juga modulnya. 
 
•	Def tambah data Penjelasan: 
o	Disini kita buat inputan karena tadi kita sudah membuat kata - kata outputnya kali ini kita cukup membuat inputan data mahasiswanya saja 
o	Jangan lupa gunakan perkalian untuk menghitung hasil total atau rata- ratanya 
     
 Membuat code program `view_nilai.py` 
   

Penjelasan: • From dan import Penjelasan: 
o Fungsinya sama saja dengan yang ada dibagian Input_Nilai<br> 
  
•	Def tampil Penjelasan: 
o	Disini kita buat sebuah tabel untuk menampilkan data - data dan nama - nama mahasiswa didalam dictionary 
o	(If)Jika terdapat data maka data dan nama mahasiswa tersebut akan muncul o Disini kita menggunakan for untuk melakukan perulangan nomor urut 
o	(Else)Jika kita belum menginputkan data sama sekali maka akan muncul tulisan "tidak ada data". 
     
•	Def cari data Penjelasan: 
o	Tadi kita sudah buat print sama seperti dibagian Input_Nilai 
o	Kita akan langsung membuat inputan dengan format nama untuk mencari data dari mahasiswa yang sedang kita cari 
o	(If)Jika data mahasiswa yang dicari ada didalam dictionary maka data baik Nama, 
NIM, Nilai Tugas, Nilai UTS, dan Nilai UAS akan muncul o (Else)Jika data mahasiswa yang dicari tidak ada didalam dictionary maka akan muncul tulisan "datanya tidak ada". 
     




 
 Membuat code program :  `main.py` 
 
 
•	From dan import Penjelasan: 
o	Sama seperti sebelumnya hanya saja disini sedikit berbeda o From disini kita tulis package.modulnya lalu import fungsi(def) tadi o Karena dibagian main ini kita akan menggunakan atau membuat syntax pilihan menu. 
    
•	While True Penjelasan: 
o	Kita gunakan print untuk membuat pilihan menunya o Lalu kita buat inputan untuk memilih menu nanti ketika program dijalankan o (If dan Elif)Kita gunakan karena kita akan membuat cabang pilihan yang banyak o Lalu dibawahnya kita tambahkan  juga fungsi - fungsi yang sudah kita buat tadi o Pada perintah ke 6 kita gunakan break untuk keluar dari program yang kita jalankan o (Else)Jika kita tidak memilih salah satu menu tersebut maka akan muncul peringatan "pilih menu yang tersedia diatas". 

Menjalankan program python 
 
 Untuk menjalankan program kita klik : Run > `main.py` 
 
	Pilih Menu Nomor : 1. Tambah 
![image](https://user-images.githubusercontent.com/115517181/211320368-25738fd1-f11e-4cbb-8f7a-eb077bf0105e.png)
![image](https://user-images.githubusercontent.com/115517181/211320907-37ae5b08-096d-4b75-84c5-06c66fa9a6cb.png)
![image](https://user-images.githubusercontent.com/115517181/211320945-5b61214e-c23b-4af8-b06e-3cea3ceb29ff.png)

 
 

	Pilih Menu Nomor : 2. Tampil 
![image](https://user-images.githubusercontent.com/115517181/211321011-92766e62-3b08-4eac-915d-cc274fcf3f53.png)
 


	Pilih Menu Nomor : 3. Hapus 
![image](https://user-images.githubusercontent.com/115517181/211321061-9cdd4433-e80b-4db0-b3cb-81db6dfecad7.png)
 






	Untuk menampilkan data yang kita hapus,Pilih Menu Nomor : 2. Tampil 
![image](https://user-images.githubusercontent.com/115517181/211321120-aa87598e-ef97-40c5-beb1-f2c8486e5445.png)

  

	Pilih Menu Nomor : 4. Ubah  
![image](https://user-images.githubusercontent.com/115517181/211321158-64cf6764-95bc-457b-b0cb-ead091223f33.png)
 










	Untuk menampilkan data yang kita ubah,Pilih Menu Nomor : 2. Tampil 
![image](https://user-images.githubusercontent.com/115517181/211321258-299dc603-f709-45d8-8ca8-20f6749a6c7f.png)
 

	Pilih Menu Nomor : 5. Cari 
![image](https://user-images.githubusercontent.com/115517181/211321350-e42202e0-718e-477a-a31a-527e0f6f30fe.png)
  

	Pilih Menu Nomor : 6. Keluar dari program 
![image](https://user-images.githubusercontent.com/115517181/211321304-90b8986a-794d-4ef8-b914-736b6acb8def.png)

 
 

TERIMAKASIH 
