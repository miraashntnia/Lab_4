```
                                                            MIRA SHINTANIA
                                                              312010290
                                                               TI.20.B2

```




# **Tugas Praktikum 4*
Program Menambahkan Data Kedalam Sebuah List Dengan Rincian Sebagai Berikut:
- Program meminta memasukan data sebanyak-banyaknya (gunakan perulangan)
- Tampilkan pernyataan untuk menambah data (y/t), apabila jawabannya t (tidak), maka program akan menampilkan daftar datanya.
- Nilai akhir diambil dari perhitungan 3 komponen nilai (tugas 30%, UTS 35%, UAS: 35%)
- Membuat Flowchart

### **Source Code**

1. Untuk program meminta masukan data sebanyak-banyaknya maka gunakanlah source code perulangan seperti berikut:
```
Nilai = []                              ## Membuat list nilai kosong
Perulangan = True                       ## Membuat variable perulangan "true" untuk logika looping
While perulangan                        ## Looping
```

2. Untuk program penginputan data gunakanlah source code sebagai berikut: 
```
nama = input("Masukkan Nama: ")                                          ## Membuat variable nama untuk list dan menginputkan datanya
nim = input("Masukkan NIM: ")                                            ## Membuat variable nim untuk list dan menginputkan datanya
nilaiTugas = int(input("Masukkan Nilai Tugas: "))                        ## Membuat variable nilaiTugas untuk list dan menginputkan datanya
nilaiUts = int(input("Masukkan Nilai UTS: "))                            ## Membuat variable nilaiUts untuk list dan menginputkan datanya
nilaiUas = int(input("Masukkan Nilai UAS: ")                             ## Membuat variable nilaiUas untuk list dan menginputkan datanya
```

3. Untuk mendapatkan hasil output dengan nilai akhir diambil dari 3 komponen nilai, gunakan source code sebagai berikut:
```
nilaiAkhir = (nilaiTugas * 30/100) + (nilaiUts * 35/100) + (nilaiUas * 35/100)    ## Membuat variable nilaiAkhir untuk list dan menggabungkan nilaiTugas, uts, dan uas dengan syarat yang sudah ditentukan.
```

4. Untuk menambahkan semua list, gunakan source code berikut:
```
nilai.append([nama, nim, nilaiTugas, nilaiUts, nilaiUas, int(nilaiAkhir)])        ## Menambahkan semua list dari nama sampai nilaiAkhir ke list nilai.
```

5. Untuk menampilkan pertanyaan menambah data atau tidak, maka gunakan source code sebagai berikut:
```
if (input("Tambah data (y/t)? ") == 't'):                                 ## Jika kita tidak menambahkan data ketik "t" untuk mengakhiri
perulangan = False                                                        ## Looping selesai
```

### **Flowchart**

### **Screenshot Input**

### **Screenshot Ouput**
