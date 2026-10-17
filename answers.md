# Jawaban Praktikum: Rizki Permadi Salim(10224126)

## Bagian 1: Pemanasan

1. Pada nav a.active:hover { color: red; }:
   - Selector: nav a.active:hover
   - Deklarasi: color: red;
   - Property: color
   - Value: red
   - Pseudo-class: :active dan :hover

2. Elemen block: p, li, h2.
   Elemen inline: span, a, strong.

3. Paragraf yang menjadi hijau adalah A dan B, karena keduanya merupakan elemen p yang berada di dalam elemen dengan class box.

4. Warnanya merah, karena selector #title memiliki specificity lebih tinggi daripada .heading dan h1.

5. Tag HTML tidak ditutup dengan urutan yang benar. Tag <strong> harus ditutup sebelum tag </p>, sehingga menjadi <p>Hello <strong>world</strong></p>.

## Bagian 3: Prediksi Selector Golf

P1.prediksi selector ini akan menargetkan elemen paragraf didalam div tertentu.
P2.prediksi selector ini akan menargetkan kelas khusus pada elemen list.
Setelah diuji (hasil sebenarnya):
selector berfungsi sesuai dengan spesifikasi CSS dasar.

## Bagian 4: Box model

Q1 (content-box):Lebar elemen dihitung hanya dari kontennya saja,padding dan border ditambahkan diluar lebar tersebut.
Q2 (border-box):Lebar total elemen sudah mencakup konten,padding, dan border secara keseluruhan.
Pengecekan DevTools:Terlihat jelas pada tab Elements bagian computed di browser

## Bagian 5: Tabel debug

| # | Baris | Bug | Perbaikan | Cara menemukannya |
|---|---|---|---|---|
| 1 | 118 | Penulisan tag penutup htal | Mengubah </htal> menjadi </html> | Memeriksa struktur HTML di akhir dokumen |
| 2 | 7 | Posisi tag link CSS di luar head | Memindahkan tag link ke dalam <head> | Memeriksa hirarki dokumen HTML |
| 3 | 1 | Tag doctype kurang lengkap | Menggunakan <!DOCTYPE html> | Inspeksi kode HTML |
| 4 | 15 | Atribut alt gambar belum jelas | Menambahkan deskripsi gambar pada alt | Audit aksesibilitas |
| 5 | 30 | Penulisan sintaks CSS kurang tepat | Merapikan penulisan kurung kurawal CSS | Memeriksa file style.css |

## Bagian 6: Tabel Code Review

| # | Baris | Masalah | Mengapa penting | Perbaikan saya |
|---|---|---|---|---|
| 1 | 8 | Elemen tidak semantik | Penting untuk SEO dan aksesibilitas | Mengganti div dengan elemen semantik |
| 2 | 20 | Tidak ada atribut alt pada gambar | Penting untuk pembaca layar (screen reader) | Menambahkan atribut alt yang informatif |
| 3 | 45 | Penulisan struktur tabel kurang rapi | Memudahkan pembacaan struktur data | Menambahkan tag section dan container |

## Bagian 7: Exit ticket

Refleksi:
1. Saya belajar menggunakan tag semantik HTML dan menghubungkan file CSS eksternal.
2. Tantangan terbesar adalah memahami spesifisitas selector dan debugging struktur HTML.
3. Langkah selanjutnya adalah memperdalam pemahaman tentang layouting CSS modern seperti Flexbox dan Grid.