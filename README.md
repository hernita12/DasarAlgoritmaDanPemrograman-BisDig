1. Fungsi Rekursif Faktorial
   Manfaat menggunakan fungsi:
   - Membagi program menjadi bagian kecil (Modular).
   - Dapat digunakan berulang kali (Reusability).
   - Mudah dalam menemukan dan memperbaiki kesalahan.
   - Membuat kode lebih rapi dan jelas.
   Cara kerja rekursi adalah cara di mana sebuah fungsi memanggil dirinya sendiri untuk menyelesaikan masalah. contohnya untuk menghitung faktorial dengan rekursi memiliki aturan berhenti (basis) jika angkanya 0 atau 1 maka langsung kembali ke 1, dan jika lebih dari 1 maka faktorial(n) = n × faktorial(n - 1).
   
2. Penggunaan Loop dan Array
   Dalam kasus ini Array digunakan untuk menyimpan nilai dari setiap siswa, sedangkan Loop digunakan untuk mengulang proses input nilai sebanyak jumlah siswa juga dapat digunakan untuk mencari nilai tertinggi dan posisi siswa yang mendapat nilai tersebut.
 
3.  Algoritma Kasir
   Langkah-langkah algoritma:
   - Mulai program
   - Input harga barang:
      - Minta pengguna memasukkan harga barang pertama. 
      - Minta pengguna memasukkan harga barang kedua.
      - Minta pengguna memasukkan harga barang ketiga.
         for i in range(3):
          harga = float(input(f"Masukkan harga barang ke-{i+1}: "))
          harga_barang.append(harga)
   - Proses:
      - Jumlahkan ketiga harga barang tersebut.
           total = sum(harga_barang)
   - Selesai.
     
4. Menentukan syarat lulus berdasarkan nilai rata-rata
   Peran tipe data:
   - int dan float untuk menyimpan nilai ujian siswa.
   - str untuk menyajikan teks, seperti pesan mengenai hasil kelulusan siswa.
   Peran operator:
   - Operator aritmatika (+,/) digunakan dalam proses penjumlahan dan pembagian untuk menghitung rata-rata dari ketiga nilai ujian.
   - Operator perbandingan (>=) digunakan untuk memerikasa apakah rata-rata nilai siswa memenuhi batas minimal kelulusan (75).

5. Struktur kontrol percabangan yang digunakan untuk logika pemberian diskon dapat menggunakan pernyataan if, else if, dan else  untuk membuat percabangan. contoh:
   - jika total belanja > 500.000 maka di berikan diskon 10%.
   - jika tidak maka tidak ada diskon.
