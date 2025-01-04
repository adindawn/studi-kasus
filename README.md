# studi-kasus

NAMA  : ADINDA AULIA NABILA PUTRI

NIM   : 312410309

KELAS : TI.24.A.4 

# Validasi Input Pendaftaran Online

Program ini dibuat untuk memberikan memvalidasi data input pada proses pendaftaran online. Validasi dilakukan pada tiga jenis data : Nama lengkap, Nomor telepon, dan Email. Program ini memberikan pesan kesalahan yang spesifik jika ada input yang tidak valid dan menyatakan bahwa data pendaftaran valid jika semua input benar. 

# Input 

  ![code](https://github.com/user-attachments/assets/7ada9b10-4b57-4d70-8bc0-cca5d85c7c77)

# cara kerja program 

1. Validasi Nama
   ![Screenshot 2025-01-04 210959](https://github.com/user-attachments/assets/b2775722-d2ca-411b-8cc7-2cd438931ae5)

   * Fungsi isalpha() memastikan bahwa name hanya terdiri dari huruf.
   * Jika nama berisi angka, spasi, atau karakter khusu, valdasi akan gagal, dan pesan error ditambahkan ke daftar errors.

2. Validasi Nomor Telepon
     ![Screenshot 2025-01-04 213001](https://github.com/user-attachments/assets/a688533c-b5a1-4ab6-b8a6-21bd1058fc3b)

   * Fungsi isdigit() memastikan bahwa phone hanya terdiri dari angka.
   * Jika phone berisi huruf, spasi, atau karakter lain, validasi akan gagal.

3. Validasi Email
     ![Screenshot 2025-01-04 211638](https://github.com/user-attachments/assets/f2d88866-bb8a-4fe5-9aa1-1af2e7141fe4)

     * Ekspresi reguler ^\S+@\S+\.\S+$ memastikan bahwa:
           * Ada karakter sebelum @ (\S+ berarti non-spasi).
           * Ada karakter sebelum dan sesudah ..
           * Tidak ada spasi diseluruh string email.
     * Jika format email tidak sesuai, validasi akan gagal.

4. Hasil Validasi
   
 ![Screenshot 2025-01-04 212156](https://github.com/user-attachments/assets/b26473fe-2888-4fd5-a2e0-eed1e6237315)

   * Jika ada elemen dalam daftar errors, setiap pesan kesalahan akan ditampilkan
   * Jika tidak ada kesalahan, program akan menampilkan "Data pendaftran valid."

# Output Valid
  ![Screenshot 2025-01-04 212633](https://github.com/user-attachments/assets/a04a1f15-dbfb-45d8-a131-6fcbc07ad029)
 
# Output Tidak Valid
  ![Screenshot 2025-01-04 210520](https://github.com/user-attachments/assets/f4b147bd-7561-49ee-87b2-b3809f23608c)






