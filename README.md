# labpy4

# penjelasan

Flowchart

![ss21](https://user-images.githubusercontent.com/115911489/202916515-645f2586-a00c-4296-a8ec-8d76e1bd4f47.JPG)

![ss22](https://user-images.githubusercontent.com/115911489/202916537-62c303c8-d244-41df-982d-2f748e57df72.JPG)

Berikut adalah tampilan program menggunakan bahasa phyton

![ss19](https://user-images.githubusercontent.com/115911489/202916621-97901f1e-7049-42f1-8997-8ba5fd416959.JPG)

1. from prettytable import PrettyTable Membuat header table menggunakan prettytable . Variabel import berfungsi untuk memanggil file lain di dalam satu modul yang berbeda.

2. print("Program Input Data Mahasiswa") print() untuk menampilkan kalimat yang di input.

tabelNama = PrettyTable(["No" ,"Nama" ,"NIM" ,"Nilai Tugas" ,"Nilai UTS" ,"Nilai UAS" ,"Nilai Akhir" ])
a = 0
(Deklarasi daftar)untuk menginput data yang dimasukkan ke dalam daftar. inputNamatabel untuk memanggil. sedangkan PrettyTable berfungsi untuk membungkus semua list. Deklarasi *a = 0*untuk membuat nomor pada isi tabel.

3. Membuat program perulangan menggunakan py while True:

4. a += 1
   b = input("Masukkan Nama : ")
   c = input("Masukkan NIM : ")
   d = int(input("Masukkan Nilai Tugas : "))
   e = int(input("Masukkan Nilai UTS : "))
   f = int(input("Masukkan Nilai UAS :" ))
   g = "{:.2f}".format((d*.30) + (e*.35) + (f*.35))
   a += 1untuk menginput nomer pada awal tabel. daftar deklarasi dan Memasukkan Input Dengan Fungsi input()untuk menulis nama yang akan kita simpan dalam variabel.        int(input())untuk menginput tipe data interger (bilangan bulat) dalam variabel.

   {:.2f}".format((d*.30) + (e*.35) + (f*.35)) untuk menginput Nilai Akhir yang di ambil dari perhitungan 3 komponen nilai.

 5. tabelNama.add_ro ([a,b,c,d,e,f,g])
    tabelNama.horizontal_char = "="
    tabelNama.junction_char = "="
    variabel di atas adalah untuk membentuk sebuah table.

6. Program input tanya [y/t], apabila jawaban t atau T, maka program inputan dihentikan statement break dan akan menampilkan data yang sudah diinput.

#Keluaran


Bila dijalankan maka program akan menghasilkan output seperti dibawah ini

![ss20](https://user-images.githubusercontent.com/115911489/202917047-8d41fbd5-fa68-4601-97c2-1d9885ed8c6a.JPG)
