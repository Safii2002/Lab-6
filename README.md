# Program Daftar Nilai Mahasiswa
Program ini bertujuan untuk mengelola data nilai mahasiswa dengan tampilan perintah sebagai berikut : 

![Screenshot 2024-12-07 024216](https://github.com/user-attachments/assets/f60cc5d6-73a0-4d18-ad9a-bbe7cb0cdbc6)

![Screenshot 2024-12-07 024238](https://github.com/user-attachments/assets/f859a0e9-3daf-492c-b046-7d4fb997188a)


## Fungsi Utama

1. **Tambah Data**  
   Menambahkan data mahasiswa berupa nama dan nilai.

2. **Tampilkan Data**  
   Menampilkan semua data mahasiswa dalam bentuk daftar.

3. **Hapus Data**  
   Menghapus data mahasiswa berdasarkan nama.

4. **Ubah Data**  
   Mengubah nilai mahasiswa berdasarkan nama.

5. **Keluar**  
   Mengakhiri program.

## Struktur Data
Data mahasiswa disimpan dalam dictionary data_mahasiswa, di mana Nama adalah kunci, dan nilai lainnya (nama, tugas, UTS, UAS) disimpan dalam dictionary sebagai nilai.

### Dictionary `data_mahasiswa`
- **Kunci**: Nama mahasiswa.
- **Nilai**: Dictionary yang berisi:
  - `nama`: Nama mahasiswa.
  - `nilai_tugas`: Nilai tugas.
  - `nilai_uts`: Nilai UTS.
  - `nilai_uas`: Nilai UAS.

## Tampilan Program

![Screenshot 2024-12-07 024254](https://github.com/user-attachments/assets/ea066854-4e4b-4df4-86ce-83b0db3f972a)

![Screenshot 2024-12-07 024729](https://github.com/user-attachments/assets/23c4b18a-8f67-47e0-8c2a-50b93bb1582b)

## Alur Program

1. Start : Titik awal program
2. Program akan menampilkan menu pilihan kepada pengguna:
   - Tambah data : Dengan memilih nomer 1
   - Tampilkan data : Dengan memilih nomer 2
   - Hapus data : Dengan memilih nomer 3
   - Ubah data : Dengan memilih nomer 4
   - Keluar : Dengan memilih nomer 5
3. Pengguna memilih opsi sesuai kebutuhan dengan memasukkan angka (1-5).
4. Program akan menjalankan fungsi berdasarkan pilihan pengguna
5. Meminta input tambahan (jika diperlukan).
6. Menampilkan hasil sesuai fungsi yang dipilih.
7. Program akan terus berjalan hingga pengguna memilih opsi "Keluar".
8. Jika pengguna memilih 5 (Keluar):
9. Tampilkan pesan bahwa program selesai dan keluar dari loop.
10. End: Titik akhir program.

## Flowchart

![Untitled Diagram (1)](https://github.com/user-attachments/assets/ce290745-1b0e-4f49-9f3d-33ebbd451ad6)

