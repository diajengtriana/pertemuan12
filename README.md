# PERTEMUAN 12

# NAMA    = Diajeng triana k.

# NIM     = 312110474

# KELAS   = TI 21 C5

# SOAL

![soal](https://user-images.githubusercontent.com/92905452/147248042-599e8314-59e2-4f8e-b601-6e91ccafae46.png)

# DIAGRAM CLASS

![diagramClass](https://user-images.githubusercontent.com/92905452/147248385-29d76b83-ee7b-42ae-90aa-2411df8a8059.png)

# FLOWCHART

![flowchart](https://user-images.githubusercontent.com/92905452/147248797-a174e7ab-175c-45c2-8842-a987671f8987.png)

# PROGRAM
pertama saya membuat sebuah class daftar nilai

    class daftarNilai()

Lalu saya melanjutkan dengan membuat method method fungsinya

    def tambah(self)
    def ubah(self)
    def lihat(self)  
    def hapus(self)
  
  Lalu saya mengisi setiap method dengan elemen elemen nya
  
    nama= input("Masukkan Nama\t\t: ")        
    nim= input("Masukkan NIM\t\t: ")      
    nilaiTugas= int(input("Masukkan Nilai Tugas\t: "))       
    nilaiUts= int(input("Masukkan Nilai UTS\t: "))        
    nilaiUas= int(input("Masukkan Nilai UAS\t: "))        
    nilaiAkhir= (0.30 * nilaiTugas) + (0.35 * nilaiUts) + (0.35 * nilaiUas)        
    dt[nama]= nim, nilaiTugas, nilaiUts, nilaiUas, nilaiAkhir

Lalu saya membuat sebuah looping

    while True:       
        input('tambah   (1)             
               ubah     (2)          
               lihat    (3)            
               hapus    (4)             
               ')     
        c = input("\nsilahkan masukan pilihan : ")

Dan terakhir membuat fungsi if else untuk menjalankan method

    if (c=="1"):
        data.tambah()
    elif (c=="2"):
        data.ubah()
    elif (c=="3"):
        data.lihat()
    elif (c=="4"):
        data.hapus()
    else:
        data.keluar()
        break

# OUTPUT
Menambah data

