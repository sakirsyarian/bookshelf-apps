# Submission Bookshelf Apps

Buatlah aplikasi web yang dapat memasukan data buku ke dalam rak, memindahkan data buku antar rak, dan menghapus data buku dari rak.
Untuk lebih jelasnya, terdapat 5 kriteria utama pada Bookshelf Apps yang harus Anda buat.

### Kriteria 1: Mampu Menambahkan Data Buku

- Bookshelf Apps harus mampu menambahkan data buku baru.
- Data buku yang disimpan merupakan objek JavaScript dengan struktur berikut:

```javascript
  {
  id: string | number,
  title: string,
  author: string,
  year: number,
  isComplete: boolean,
}
```

Berikut contoh data riilnya:

```javascript
  {
  id: 3657848524,
  title: 'Harry Potter and the Philosopher\'s Stone',
  author: 'J.K Rowling',
  year: 1997,
  isComplete: false,
}
```

Catatan:

> Untuk id buku pada tiap buku yang disimpan haruslah unik. Tips dalam menetapkan nilai untuk adalah Anda bisa memanfaatkan nilai timestamp. Untuk mendapatkan nilai timestamp di JavaScript cukup mudah, cukup dengan menuliskan expressions +new Date().

### Kriteria 2: Memiliki Dua Rak Buku

- Bookshelf Apps harus memiliki 2 Rak buku. Yakni, “Belum selesai dibaca” dan “Selesai dibaca”.
- Rak buku "Belum selesai dibaca" hanya menyimpan buku jika properti isComplete bernilai false.
- Rak buku "Selesai dibaca" hanya menyimpan buku jika properti isComplete bernilai true.

### Kriteria 3: Dapat Memindahkan Buku antar Rak

- Buku yang ditampilkan pada rak, baik itu "Belum selesai dibaca" maupun "Selesai dibaca" harus dapat dipindahkan di antara keduanya.

### Kriteria 4: Dapat Menghapus Data Buku

- Buku yang ditampilkan pada rak, baik itu "Belum selesai dibaca" maupun "Selesai dibaca" harus dapat dihapus.

### Kriteria 5: Manfaatkan localStorage dalam Menyimpan Data Buku

- Data buku yang ditampilkan pada rak, baik itu "Belum selesai dibaca" maupun "Selesai dibaca" harus dapat bertahan walaupun halaman web ditutup.
- Dengan begitu, Anda harus menyimpan data buku pada localStorage.

## Penilaian Submission

Submission Anda akan dinilai oleh Tim Reviewer guna menentukkan kelulusan Anda. Untuk lulus dari kelas ini, proyek Bookshelf Apps harus memenuhi seluruh kriteria yang telah disebutkan pada bagian Kriteria Bookshelf Apps. Submission Anda akan dinilai oleh Tim Reviewer dengan skala 1-5. Untuk mendapatkan nilai tinggi, silakan penuhi saran-saran berikut ini:

- Tambahkan fitur pencarian untuk mem-filter buku yang ditampilkan pada rak sesuai dengan title buku yang dituliskan pada kolom pencarian.
- Berkreasilah dengan membuat proyek Bookshelf Apps tanpa menggunakan project starter.
- Menuliskan kode dengan bersih.
  - Bersihkan comment dan kode yang tidak digunakan.
  - Indentasi yang sesuai.
- Terdapat improvisasi fitur seperti (pilih satu):
  - Custom Dialog ketika menghapus buku.
  - Dapat edit buku.

Berikut adalah detail penilaian submission:

1. Bintang satu : Semua ketentuan terpenuhi, namun terdapat indikasi kecurangan dalam mengerjakan submission.
2. Bintang dua : Semua ketentuan terpenuhi, namun terdapat kekurangan pada penulisan kode.
3. Bintang tiga : Semua ketentuan terpenuhi, namun tidak terdapat improvisasi atau saran yang dipenuhi.
4. Bintang empat : Semua ketentuan terpenuhi dan menerapkan minimal satu saran yang diberikan.
5. Bintang lima : Semua ketentuan terpenuhi dan menerapkan seluruh saran yang diberikan.

Catatan:

> Jika submission Anda ditolak maka tidak ada penilaian. Kriteria penilaian bintang di atas hanya berlaku jika submission Anda lulus.

### Hasil Penilaian

Terpenuhi:

- [x] Mampu Menambahkan Data Buku baru.
- [x] Memiliki minimal Dua Rak Buku. Yakni “Belum selesai dibaca” dan “Selesai dibaca”.
- [x] Dapat Memindahkan Buku antar Rak.
- [x] Dapat Menghapus Data Buku.
- [x] Manfaatkan localStorage dalam Menyimpan Data Buku
- [x] Aplikasi dapat berfungsi dengan baik (tidak terdapat bug, tidak mengalami force close, fungsionalitas aplikasi berjalan dengan baik).

**Rating Submission Anda**:
⭐⭐⭐⭐ (4/5)
