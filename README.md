# Sistem Pendukung Keputusan Ekstrakurikuler (SPK) - Algoritma MACROS

## 📌 Deskripsi Project

Sistem Pendukung Keputusan (SPK) berbasis website yang dibangun menggunakan framework Laravel untuk membantu menentukan rekomendasi ekstrakurikuler siswa berdasarkan beberapa kriteria penilaian dengan menggunakan algoritma **MACROS (Multi-Attributive Comprehensive Ranking by Ordinal Scoring)**.

Project ini masih dalam tahap pengembangan dan sedang melalui proses **Quality Assurance (QA)** untuk peningkatan kualitas sistem.

---

## ⚙️ Teknologi yang Digunakan

- Laravel (PHP Framework)
- PHP 8+
- MySQL / MariaDB
- Bootstrap
- JavaScript

---

## 🎯 Fitur Sistem

- Login & Autentikasi User
- Manajemen Data Ekstrakurikuler
- Manajemen Kriteria Penilaian
- Input Nilai Siswa
- Perhitungan SPK menggunakan metode MACROS
- Hasil rekomendasi & ranking
- Dashboard Admin

---

## 🧠 Metode yang Digunakan

### Algoritma MACROS
Metode ini digunakan untuk melakukan perangkingan alternatif berdasarkan beberapa kriteria yang telah diberi bobot.

---

## 🚧 Status Project

Project saat ini masih dalam tahap pengembangan dan telah melalui proses awal **Quality Assurance (QA)**.

Beberapa hal yang sedang atau akan diperbaiki:

- Validasi form input
- Perbaikan logika algoritma MACROS
- Optimasi query database
- Refactoring struktur kode (Laravel Best Practice)
- Peningkatan performa aplikasi
- Perbaikan keamanan sistem

---

## 🧪 Catatan QA

Hasil audit QA dilakukan untuk menemukan potensi bug dan masalah sistem seperti:

- Bug validasi form
- Potensi kesalahan perhitungan ranking
- Query database tidak efisien
- Potensi N+1 query
- Struktur database yang perlu normalisasi

Perbaikan akan dilakukan secara bertahap di commit berikutnya.

---

## 🚀 Cara Instalasi

```bash
git clone https://github.com/username/spk-ekstra-macros.git
cd spk-ekstra-macros
composer install
cp .env.example .env
php artisan key:generate