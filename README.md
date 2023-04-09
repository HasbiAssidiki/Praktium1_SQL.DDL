# **Praktium1_SQL.DDL**


```
Nama    : Hasbi Assidiki
NIM     : 312210448
Kelas   : TI.22.A.4
```
# **SQL DDL (Data Definiton Language)**
# **Daftar Isi**
[A. TUGAS PRAKTIKUM 1](#a-tugas-praktikum-1)             
[B. Evalulasi dan Pertanyaan](#b-evaluasi-dan-pertanyaan)

## **A. TUGAS PRAKTIKUM 1**

1. Buat sebuah database dengan nama **latihan2**
  
    contoh:     
   ![P1](https://user-images.githubusercontent.com/115614317/230758642-954fb068-251a-402b-adba-46beace13079.png)         
    [HOME](#daftar-isi)
2. Buat sebuah tabel dengan nama **biodata** (nama, alamat) di dalam database **latihan1!**     
         
   ![P2](https://user-images.githubusercontent.com/115614317/230758646-37a4c47d-e2e9-4c67-8964-953069c6bf64.png)     
    [HOME](#daftar-isi)
3. Tambahkan sebuah kolom keterangan (varchar 15), sebagai kolom terakhir!  
   
   ![P3](https://user-images.githubusercontent.com/115614317/230758650-ede77b67-6144-44fa-aa06-3ca716649266.png)      
    [HOME](#daftar-isi)
4. Tambahkan kolom id (int 11) di awal (sebagai kolom pertama)!
       
    ![P4](https://user-images.githubusercontent.com/115614317/230758653-ff5954ba-b409-49ed-82b8-6da06a025dcb.png)    
    [HOME](#daftar-isi)
5. Sisipkan sebuah kolom dengan nama **phone** (varchar 15) setelah kolom **alamat**!       
    
    ![P5](https://user-images.githubusercontent.com/115614317/230758656-0b35946d-82d3-454e-aba7-6343e538eef8.png)   
    [HOME](#daftar-isi)
6. Ubah tipe data kolom id menjadi char(11)     
        
    ![P6](https://user-images.githubusercontent.com/115614317/230758664-02c80ed8-259d-4508-81ce-1989067584cc.png)       
    [HOME](#daftar-isi)
7. Ubah nama kolom **phone** menjadi **hp** (varchar 20)!       
    
    ![P7](https://user-images.githubusercontent.com/115614317/230758666-90b6aaca-be24-4fa9-9441-2ce79589976d.png)    
    [HOME](#daftar-isi)
8. Tambahkan kolom **email** setelah kolom **hp**       
    
    ![P8](https://user-images.githubusercontent.com/115614317/230758674-273687b3-9615-49e2-870e-8c25c69fbc5d.png)      
    [HOME](#daftar-isi)
9. Hapus kolom **keterangan** dari tabel!
      
    ![P9](https://user-images.githubusercontent.com/115614317/230758679-de03bec4-2c51-46e4-b776-6066530eb7b0.png)         
    [HOME](#daftar-isi)
10. Ganti nama tabel menjadi **data_mahasiswa**!        
       
    ![P10](https://user-images.githubusercontent.com/115614317/230758690-ed7a3349-2ed0-40dc-8dfc-e23b6633975d.png)  
    [HOME](#daftar-isi)
11. Ganti nama **field** id menjadi **nim**!        
        
    ![P11](https://user-images.githubusercontent.com/115614317/230758698-faa09e30-98d9-4a67-b23c-94032790839e.png)        
    [HOME](#daftar-isi)
12. Jadikan **nim** sebagai **PRIMARY KEY**!        
       
    ![P12](https://user-images.githubusercontent.com/115614317/230758702-8329db04-4b40-4df4-ba61-b54a0296f9a8.png)        
    [HOME](#daftar-isi)
13. Jadikan kolom **email** sebagai **UNIQUE KEY**      
        
    ![P13](https://user-images.githubusercontent.com/115614317/230758706-5a61bb79-048d-47e3-b89d-106c28337225.png)  
    [HOME](#daftar-isi)

### **B. Evaluasi dan Pertanyaan**

- Maksud dari int (11) adalah **int** sebagai tipe data dan **(11)** sebagai index/ukuran tipe data tersebut, jadi jika **int(11)** maka artinya sebuah tipe data integer ber-index 11 (0<11) atau panjang dari tipe data integer tersebut tidak boleh lebih dari 10.
- **Kolom Null**, 
    1. jika berisi **Yes** maka data dalam kolom tersebut boleh kosong/tidak ada data atau juga bisa diartikan jika user menginputkan sebuah data maka kolom tersebut boleh tidak diisi dan tidak akan terjadi eror jika data tersebut kosong. Contohnya kolom keterangan. 
    2. Sedangkan jika berisi **No** maka data dalam kolom tersebut tidak boleh kosong/tidak ada data, jika tidak ada data dalam kolom tersebut akan terjadi eror jika data dalam kolom tersebut kosong/tidak diisi. contohnya kolom nama dan nim.       
    [HOME](#daftar-isi)
