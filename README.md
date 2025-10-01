# Proyek Preprocessing Data Film - Tugas Praktikum Data Mining

Repositori ini berisi proyek untuk tugas praktikum mata kuliah Data Mining, yang fokus pada proses pembersihan dan persiapan (preprocessing) dataset film.

**Nama: Priscilia Putri Wildasari**

**UNIVERSITAS NEGERI SEMARANG**

## Deskripsi Proyek

Proyek ini bertujuan untuk menerapkan berbagai teknik preprocessing data pada dataset film mentah (`movie_sample_dataset.csv`) agar menjadi data yang bersih, terstruktur, dan siap untuk tahap analisis atau permodelan selanjutnya.

## Dataset

* **Dataset Mentah:** `movie_sample_dataset.csv`
* **Dataset Bersih:** `movie_sample_dataset_cleaned.csv`

## Alat dan Pustaka yang Digunakan

* **Bahasa Pemrograman:** Python
* **Pustaka:** Pandas, NumPy

## Tahapan Preprocessing yang Dilakukan

Script `preprocessing.py` (atau nama file script kamu) melakukan langkah-langkah berikut:
1.  **Memuat Data**: Membaca file CSV ke dalam DataFrame Pandas.
2.  **Inspeksi Awal**: Memeriksa struktur data, tipe data, dan nilai-nilai kosong awal.
3.  **Pembersihan Data (Data Cleaning)**:
    * Menangani nilai-nilai yang hilang (*missing values*) dengan cara menghapus baris atau mengisi dengan nilai tertentu (modus, "anonim", "tidak diketahui").
    * Menghapus baris data yang duplikat.
    * Menyeragamkan format data teks (misalnya, mengubah menjadi huruf kecil/besar dan menghapus spasi ekstra).
4.  **Transformasi Data**:
    * Mengubah tipe data kolom ke format yang sesuai (misalnya, dari teks ke angka).
    * Memisahkan satu kolom (seperti `genres`) menjadi beberapa kolom terpisah (*dummy variables*).
5.  **Penyimpanan**: Menyimpan DataFrame yang sudah bersih ke dalam file CSV baru.
