# 📦 IT-Asset Inventory Management System

Sistem manajemen inventaris aset IT berbasis web yang responsif, interaktif, dan terintegrasi secara real-time dengan **Supabase**. Dashboard ini dirancang untuk memudahkan pemantauan aset berdasarkan departemen, status, dan jenis perangkat.

## 🚀 Fitur Utama

* **Real-time Dashboard**: Statistik aset otomatis terupdate (Total Aset, Laptop, Komputer, Maintenance, dll).
* **Filter Departemen Interaktif**: Klik pada kartu departemen (HRD, PPIC, EXIM, dll) untuk menyaring tabel secara instan tanpa reload.
* **Sistem Auth Supabase**: Login aman dengan sesi yang tetap terjaga (Persist Session).
* **Manajemen Data**: Tambah, edit, mutasi (transfer), dan hapus aset langsung dari interface.
* **Scan & Barcode**: Mendukung input barcode untuk identifikasi aset yang cepat.
* **Responsive Design**: Tampilan optimal di HP maupun Desktop menggunakan Tailwind CSS & DaisyUI.

## 🛠️ Teknologi yang Digunakan

* **Frontend**: HTML5, JavaScript (Vanilla ES6+), CSS3.
* **Styling**: [Tailwind CSS](https://tailwindcss.com/) & [DaisyUI](https://daisyui.com/).
* **Backend & Database**: [Supabase](https://supabase.com/) (PostgreSQL & Auth).
* **Icons**: [Font Awesome](https://fontawesome.com/).
* **Deployment**: GitHub Pages.

## 📁 Struktur Proyek

```text
├── index.html          # File utama (UI & Logika JS)
├── README.md           # Dokumentasi proyek
└── (Assets/Scripts)    # Integrated via CDN (Tailwind, Supabase, Barcode Lib)
