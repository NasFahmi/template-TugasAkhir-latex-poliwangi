# 📘 Template LaTeX Proposal Tugas Akhir

*Program Sarjana Terapan Teknologi Rekayasa Perangkat Lunak – Politeknik Negeri Banyuwangi*

Template ini dirancang khusus untuk penulisan **Proposal Tugas Akhir** (BAB 1, BAB 2, dan BAB 3) bagi mahasiswa D3 dan D4 Politeknik Negeri Banyuwangi. Template ini memastikan keseragaman format sesuai Pedoman Mutu Tugas Akhir Poliwangi 2023.

---

## 📁 Struktur Proposal

```
proposal/
├── proposal.tex                      # File utama untuk kompilasi
├── a0-identitas.tex                  # Isi identitas proposal (WAJIB DIISI)
├── a1-database.hyphenate.tex         # Database untuk hyphenation
├── a2-abstrak.tex                    # Abstrak dalam Bahasa Indonesia  
├── a3-abstract.tex                   # Abstrak dalam Bahasa Inggris
├── a6-daftarsingkatan.tex            # Daftar Singkatan
├── a7-pustaka.bib                    # Daftar pustaka dalam format BibTeX
├── b1-bab1.tex                       # BAB 1 - Pendahuluan
├── b2-bab2.tex                       # BAB 2 - Tinjauan Pustaka
├── b3-bab3.tex                       # BAB 3 - Metode Penelitian
├── gambar/                           # Folder untuk menyimpan gambar
│   └── logo-poliwangi.png
├── kode/                             # Folder untuk menyimpan kode program
└── untouch/                          # Folder untuk file yang tidak perlu diubah
    ├── xx-daftar.tex
    ├── xx-daftarpustaka.tex
    ├── xx-persetujuan-proposal.tex
    ├── xx-preambles.tex
    ├── xx-sampul-proposal.tex
    └── xx-sampuldalam-proposal.tex
```

---

## 🧩 Fitur Utama

✅ Format sesuai **Pedoman Mutu Tugas Akhir Poliwangi 2023**

✅ Khusus untuk **Proposal TA** (BAB 1-3)

✅ **Warna cover otomatis** sesuai program studi

✅ Contoh gambar, kode program, persamaan, tabel, dan sitasi

✅ Dukungan referensi otomatis (BibTeX dengan APA Style)

✅ Kompatibel dengan TexStudio dan Overleaf

---

## 🎨 Warna Cover Per Program Studi

Template ini mendukung warna cover yang berbeda sesuai program studi Poliwangi. Edit file `a0-identitas.tex` dan ubah nilai `\covercolor`:

| Program Studi | Warna Cover | Kode RGB |
|--------------|-------------|----------|
| Teknik Informatika | Kuning | 255,215,0 |
| **Teknologi Rekayasa Perangkat Lunak** | **Kuning** | **255,215,0** |
| Teknik Sipil | Biru Tua | 0,0,128 |
| Teknik Mesin | Merah | 255,0,0 |
| Manajemen Bisnis Pariwisata | Orange | 255,127,0 |
| Agribisnis | Hijau Tua | 0,159,60 |
| Teknologi Pengolahan Hasil Ternak | Coklat Tua | 150,75,0 |
| Teknik Manufaktur Kapal | Biru Muda | 0,128,255 |

---

## 📐 Format Penulisan (Poliwangi 2023)

- **Margin:** Kiri 3cm, Atas 2cm, Kanan 2cm, Bawah 2cm
- **Font:** Times New Roman 12pt
- **Spasi:** 1.5 (isi), 1.0 (tabel/gambar)
- **Indentasi:** First Line 1.25cm
- **Penomoran Bab:** BAB 1, BAB 2, BAB 3 (angka, bukan romawi)
- **Section:** 1.1, 1.2, 2.1, 2.2 (sesuai bab)
- **Persamaan:** 2.3 (tanpa kurung)
- **Referensi:** APA Style, jurnal 10 tahun terakhir (D4)

---

## 🖥️ Panduan Instalasi dan Penggunaan

> **Lihat panduan lengkap instalasi di [README utama](../README.md#-panduan-instalasi-dan-penggunaan)**

### Quick Start - Overleaf (Paling Mudah) ☁️

1. **Login ke Overleaf**: [https://www.overleaf.com/](https://www.overleaf.com/)
2. **Upload Project**: New Project → Upload Project → Upload ZIP folder `proposal/`
3. **Set Main File**: Menu (☰) → Main document → pilih `proposal.tex`
4. **Compile**: Klik Recompile → PDF akan muncul

### Quick Start - Lokal

#### Windows:
1. Install MikTeX: [https://miktex.org/download](https://miktex.org/download)
2. Install TeXstudio: [https://www.texstudio.org/](https://www.texstudio.org/)
3. Buka `proposal.tex` di TeXstudio
4. Klik **Build & View** (F5)

#### MacOS:
```bash
brew install --cask mactex texstudio
# Buka proposal.tex di TeXstudio, lalu Build & View
```

#### Linux:
```bash
sudo apt install texlive-full texstudio
# Buka proposal.tex di TeXstudio, lalu Build & View
```

---

## ✍️ Langkah Pengerjaan Proposal

| File | Keterangan |
|------|-----------|
| `a0-identitas.tex` | **WAJIB:** Isi nama, NIM, judul TA, pembimbing, jurusan, warna cover prodi |
| `b1-bab1.tex` | **BAB 1 - Pendahuluan:** Latar belakang, rumusan masalah, tujuan, manfaat |
| `b2-bab2.tex` | **BAB 2 - Tinjauan Pustaka:** Teori-teori pendukung dan penelitian terkait |
| `b3-bab3.tex` | **BAB 3 - Metode Penelitian:** Metodologi yang akan digunakan |
| `a7-pustaka.bib` | Tambah referensi dengan BibTeX (APA Style) |
| `a2-abstrak.tex` | Abstrak dalam Bahasa Indonesia |
| `a3-abstract.tex` | Abstrak dalam Bahasa Inggris |

**Khusus untuk a0-identitas.tex, pastikan mengisi:**
- Nama dan NIM mahasiswa
- Judul TA (Indonesia & Inggris)
- Program Studi: Sarjana Terapan Teknologi Rekayasa Perangkat Lunak
- Jurusan: Jurusan Bisnis dan Informatika
- Pembimbing 1 dan Pembimbing 2
- Warna cover sesuai prodi (kuning: 255,215,0)

---

## 📚 Manajemen Referensi

Gunakan:
* [Mendeley](https://www.mendeley.com/)
* [Zotero](https://www.zotero.org/)
* [JabRef](https://www.jabref.org/) *(direkomendasikan)*

Format ekspor: `.bib` (BibTeX), lalu tambahkan ke file `a7-pustaka.bib`.

**Penting:** Untuk D4/Sarjana Terapan, gunakan minimal 10 referensi jurnal/prosiding dari 10 tahun terakhir.

---

## 📝 Isi Minimal Proposal

### BAB 1 - Pendahuluan
- Latar Belakang
- Rumusan Masalah
- Batasan Masalah
- Tujuan
- Manfaat

### BAB 2 - Tinjauan Pustaka
- Penelitian Terkait
- Landasan Teori
- Kerangka Pemikiran

### BAB 3 - Metode Penelitian
- Waktu dan Tempat Penelitian
- Alat dan Bahan
- Metode Pengumpulan Data
- Metode Pengembangan Sistem
- Diagram Alir Penelitian

---

## 📬 Kontak & Kontribusi

**Repository:** [github.com/codelabs-poliwangi/template-TugasAkhir-latex-poliwangi](https://github.com/codelabs-poliwangi/template-TugasAkhir-latex-poliwangi)

Saran, kontribusi, dan perbaikan sangat terbuka.
Silakan buat **Pull Request** atau buka **Issue** melalui GitHub.

**Kontak:**
📧 sepyan@poliwangi.ac.id

---

## 📝 Informasi Template

- **Institusi:** Politeknik Negeri Banyuwangi
- **Program Studi:** Sarjana Terapan Teknologi Rekayasa Perangkat Lunak
- **Jurusan:** Jurusan Bisnis dan Informatika
- **Pedoman:** Pedoman Mutu Tugas Akhir Poliwangi 2023
- **Logo:** Politeknik Negeri Banyuwangi
- **Warna Cover Default:** Kuning (RGB: 255,215,0)
- **Jenis Dokumen:** Proposal Tugas Akhir (BAB 1-3)

---

## 📄 Lisensi

Proyek ini dilisensikan di bawah [MIT License](../LICENSE).

---

## 💡 Catatan Penting

1. **Proposal vs Laporan:** Template ini khusus untuk **Proposal** (BAB 1-3). Untuk laporan lengkap (BAB 1-5), gunakan template di folder `Project/`.

2. **Setelah Seminar Proposal:** Setelah proposal disetujui, lanjutkan dengan template laporan yang mencakup BAB 4 dan BAB 5.

3. **Kompilasi:** File utama adalah `proposal.tex`, bukan `laporan.tex`.

---