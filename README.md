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

<img width="639" alt="tambah" src="https://user-images.githubusercontent.com/92905452/147248911-20ac982a-7dbd-45bd-837f-c558ef5cb6dd.png">

Melihat data

<img width="521" alt="lihat1" src="https://user-images.githubusercontent.com/92905452/147251289-6367ed84-414f-4df6-9f9c-41b6e419c0e8.png">

Menambah data lagi

<img width="461" alt="tambahLagi" src="https://user-images.githubusercontent.com/92905452/147251355-4ca34152-1d9c-424d-a11e-2fcb2450e95f.png">

Melihat hasil

<img width="489" alt="lihat2" src="https://user-images.githubusercontent.com/92905452/147251426-d57f0e04-042f-42e6-ae11-fc1084728534.png">

Mengubah data

<img width="482" alt="ubah" src="https://user-images.githubusercontent.com/92905452/147251461-5d58a7ef-8f9c-46ba-83c4-32241e6a6a79.png">

Melihat hasil

<img width="512" alt="lihat3" src="https://user-images.githubusercontent.com/92905452/147251505-be4756b9-cd59-4fac-bca8-ade704cf2dfa.png">

Menghapus apabila memilih t

<img width="478" alt="hapus(t)" src="https://user-images.githubusercontent.com/92905452/147251574-a24a4056-f386-4c3d-bc77-789f89a9425b.png">

menghapus apabila memilih y

<img width="446" alt="hapus(y)" src="https://user-images.githubusercontent.com/92905452/147251638-eeab1ea0-de28-4cd5-90b4-bddac8af51f6.png">

Melihat hasil

<img width="505" alt="lihat4" src="https://user-images.githubusercontent.com/92905452/147251697-3ae0d153-a980-4246-b5d0-308881e30633.png">

Keluar

<img width="447" alt="keluar" src="https://user-images.githubusercontent.com/92905452/147251758-d4195f57-101b-42f7-920e-7fbb05bb4548.png">
