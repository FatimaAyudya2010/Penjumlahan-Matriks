# Penjumlahan-Matriks #

# Deskripsi Program
Program PenjumlahanMatriks digunakan untuk menghitung hasil penjumlahan dua buah matriks berukuran sama.
Pengguna akan diminta memasukkan ukuran matriks (jumlah baris dan kolom) serta elemen-elemen dari Matriks A dan Matriks B, kemudian program akan menampilkan hasil penjumlahannya dalam bentuk matriks baru.

# Cara Kerja Program
> Input Ukuran Matriks
- Program meminta pengguna memasukkan jumlah baris dan kolom matriks.
Contoh: Matriks berukuran 2×2 berarti memiliki 2 baris dan 2 kolom.
> Input Elemen Matriks A dan B
- Pengguna diminta mengisi setiap elemen matriks A dan B satu per satu.
- Data disimpan dalam array dua dimensi matriksA dan matriksB.
> Proses Penjumlahan Matriks
- Program melakukan perulangan ganda (for) untuk menghitung setiap elemen hasil:
  hasil[i][j] = matriksA[i][j] + matriksB[i][j];
  Hasil penjumlahan setiap elemen disimpan dalam array hasil.
> Output Hasil Penjumlahan
- Program menampilkan matriks hasil penjumlahan dalam bentuk susunan baris dan kolom.

# Contoh Input dan Output
> Input:
Masukkan jumlah baris matriks: 2
Masukkan jumlah kolom matriks: 2
Masukkan elemen matriks A:
A[0][0] = 2
A[0][1] = 3
A[1][0] = 4
A[1][1] = 5
Masukkan elemen matriks B:
B[0][0] = 1
B[0][1] = 2
B[1][0] = 3
B[1][1] = 4
> Output:
Hasil penjumlahan matriks A + B adalah:
3 5 
7 9

# Konsep yang Digunakan
> Array dua dimensi (int[][]) untuk menyimpan elemen matriks.
> Perulangan bersarang (for di dalam for) untuk mengakses setiap elemen matriks.
> Operasi aritmetika dasar (penjumlahan elemen per elemen).
> Input menggunakan kelas Scanner untuk membaca nilai dari pengguna.

<img width="1919" height="1004" alt="Screenshot 2025-11-04 165256" src="https://github.com/user-attachments/assets/b3bb8feb-45eb-42d3-bf5f-1e57f074fc38" />
