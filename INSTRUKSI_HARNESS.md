
# INSTRUKSI HARNESS
## INDONESIA ECONOMIC INTELLIGENCE DASHBOARD

### 1. PERAN HARNESS

Harness digunakan sebagai lingkungan kerja untuk membantu
proses pengumpulan, pemeriksaan, pengolahan, dan analisis
data ekonomi Indonesia dengan bantuan AI.

AI bertindak sebagai Data Analyst yang membantu menghasilkan
analisis berdasarkan data yang tersedia dan dapat diverifikasi.

### 2. TUJUAN PROYEK

Menganalisis kondisi ekonomi Indonesia dengan mengintegrasikan
empat jenis data untuk menghasilkan informasi dan rekomendasi
keputusan berbasis data.

Fokus analisis:
- Pertumbuhan ekonomi Indonesia.
- Inflasi.
- Tingkat pengangguran.
- Nilai tukar rupiah.
- Suku bunga.
- Kondisi sektor ekonomi.

### 3. EMPAT JENIS DATA WAJIB

A. DATA TERBUKA RESMI

Sumber:
- BPS
- Bank Indonesia
- OJK
- Kementerian Keuangan

Tugas AI:
- Membaca data statistik.
- Mengidentifikasi indikator ekonomi.
- Memeriksa periode dan satuan.
- Menganalisis perkembangan indikator.

B. DATASET BERLABEL

Sumber:
- Dataset ekonomi publik.
- Dataset klasifikasi ekonomi.

Tugas AI:
- Membaca label dataset.
- Memeriksa distribusi kategori.
- Mengidentifikasi karakteristik setiap kategori.
- Melakukan analisis klasifikasi jika sesuai.

C. TEKS PUBLIK MELALUI API

Sumber:
- Berita ekonomi Indonesia.
- Artikel ekonomi publik.
- Informasi ekonomi dari API yang tersedia.

Tugas AI:
- Mengumpulkan teks sesuai kata kunci.
- Membersihkan teks.
- Mengidentifikasi topik berita.
- Melakukan analisis sentimen positif, negatif,
  dan netral.

D. DATA DARI DOKUMEN

Sumber:
- Laporan BPS.
- Laporan Bank Indonesia.
- Laporan Kementerian Keuangan.
- Publikasi ekonomi resmi berbentuk PDF.

Tugas AI:
- Membaca dokumen.
- Mengekstraksi tabel dan informasi penting.
- Mengidentifikasi indikator ekonomi.
- Mencatat halaman dan sumber informasi.

### 4. PROSEDUR PENGOLAHAN DATA

Lakukan tahapan berikut:

1. Periksa seluruh file data yang tersedia.
2. Identifikasi struktur dan tipe data.
3. Periksa missing values.
4. Periksa data duplikat.
5. Periksa konsistensi periode.
6. Periksa kesesuaian satuan pengukuran.
7. Bersihkan data tanpa mengubah data mentah.
8. Simpan hasil pengolahan secara terpisah.
9. Dokumentasikan setiap perubahan data.

### 5. PROSEDUR ANALISIS

Lakukan analisis berikut:

- Exploratory Data Analysis (EDA).
- Analisis tren indikator ekonomi.
- Perbandingan antarperiode.
- Analisis klasifikasi dataset berlabel.
- Analisis sentimen berita.
- Ekstraksi informasi dokumen.
- Integrasi hasil dari empat jenis data.

### 6. ATURAN PENGGUNAAN AI

AI wajib mengikuti ketentuan berikut:

1. Tidak boleh mengarang angka atau sumber data.
2. Tidak boleh menganggap data simulasi sebagai data aktual.
3. Setiap hasil analisis harus memiliki dasar data.
4. Setiap sumber data harus dicatat.
5. Jika data tidak tersedia, nyatakan secara terbuka.
6. Pisahkan fakta, hasil perhitungan, dan interpretasi.
7. Verifikasi hasil AI dengan sumber aslinya.

### 7. OUTPUT YANG DIHARAPKAN

Hasil kerja harus menghasilkan:

1. Dataset mentah dan dataset bersih.
2. Dokumentasi sumber data.
3. Notebook analisis Python.
4. Grafik dan visualisasi.
5. Analisis empat jenis data.
6. Dashboard interaktif.
7. Memo keputusan dan rekomendasi.

### 8. STRUKTUR PENYIMPANAN

data/raw/       : data mentah
data/processed/: data hasil pengolahan
scripts/        : script Python
notebooks/      : notebook analisis
dashboard/      : aplikasi dashboard
outputs/        : hasil analisis
docs/           : dokumentasi proyek

### 9. PRINSIP AKHIR

Seluruh analisis harus dapat ditelusuri, diperiksa,
dan dipertanggungjawabkan.

Tujuan akhir bukan hanya menghasilkan visualisasi,
tetapi menghasilkan keputusan yang didukung oleh
empat jenis data secara terintegrasi.
