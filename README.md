1. Fungsi Rekursif Faktorial
   Manfaat menggunakan fungsi:
   a. Membagi program menjadi bagian kecil (Modular).
   b. Dapat digunakan berulang kali (Reusability).
   c. Mudah dalam menemukan dan memperbaiki kesalahan.
   d. Mmebuat kode lebih rapi dan jelas.
   Cara kerja rekursi adalah cara di mana sebuah fungsi memanggil dirinya sendiri untuk menyelesaikan masalah. contohnya untuk menghitung faktorial dengan rekursi memiliki aturan berhenti (basis) jika angkanya 0 atau 1 maka langsung kembali ke 1, dan jika lebih dari 1 maka faktorial(n) = n × faktorial(n - 1).
   
2. Penggunaan Loop dan Array
   Dalam kasus ini Array digunakan untuk menyimpan nilai dari setiap siswa, sedangkan Loop digunakan untuk mengulang proses input nilai sebanyak jumlah siswa juga dapat digunakan untuk mencari nilai tertinggi dan posisi siswa yang mendapat nilai tersebut.
 
3.  Algoritma Kasir
   Langkah-langkah algoritma:
   a. Mulai program
   b. Input harga barang:
      - Minta pengguna memasukkan harga barang pertama. 
      - Minta pengguna memasukkan harga barang kedua.
      - Minta pengguna memasukkan harga barang ketiga.
         for i in range(3):
          harga = float(input(f"Masukkan harga barang ke-{i+1}: "))
          harga_barang.append(harga)
   c. Proses:
      - Jumlahkan ketiga harga barang tersebut.
           total = sum(harga_barang)
   d. Selesai.
