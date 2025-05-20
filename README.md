1. Fungsi Rekursif Faktorial
   - factorial(n): Fungsinya untuk menghitung faktorial secara rekursif.
   -  if n == 0 or n == 1: return 1: jika n itu 0 atau 1, langsung dikembalikan ke 1.
   -  else: return n * factorial(n - 1): Jika lebih besar dari 1, dia akan mengalikan n dengan faktorial dari angka sebelumnya (n - 1).
   -  main(): fungsinya untuk meminta pengguna memasukkan angka n dengan bilangan bulat non-negatif. jika angka yang dimasukkan salah atau yang dimasukkan bukan angka (huruf) maka akan muncul pesan eror. jika yang dimasukkan adalah angka yang benar maka akan menghitung faktorial dari angka tersebut dan menampilkan hasilnya.
   -  if __name__ == "__main__": main(): menjalankan fungsi main jika file ini dijalankan.
2. Penggunaan Loop dan Array
   - nilai_siswa = []: fungsinya membuat list kosong untuk menyimpan semua nilai siswa.
   - for i in range(5): fungsinya untuk menerima input dari 5 siswa.
   - nilai = int(input(f"Masukkan nilai siswa ke-{i+1}: ")): fungsinya untuk meminta pengguna memasukkan nilai.
   - nilai_siswa.append(nilai): untuk menyimpan nilai ke dalam list (nilai_siswa). 
   - nilai_tertinggi = max(nilai_siswa): untuk mencari nilai tertinggi dalam list.
   - indeks_tertinggi = nilai_siswa.index(nilai_tertinggi) + 1: mencari posisi (indeks) dari nilai tertinggi, ditambah +1 agar sesuai dengan nomor urut siswa (bukan indeks Python yang dimulai dari 0).
