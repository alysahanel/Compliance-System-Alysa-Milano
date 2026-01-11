# Compliance System Alysa Milano

**Compliance System Alysa Milano** adalah sistem E-Monitoring terintegrasi untuk mengelola kepatuhan hukum dan perizinan perusahaan. Sistem ini dirancang untuk memudahkan pemantauan dokumen legal, izin operasional, lisensi keselamatan, dan perpustakaan regulasi.

## Fitur Utama

*   **Dashboard Monitoring**: Ringkasan status kepatuhan secara real-time.
*   **Company & Legal Entity**: Manajemen dokumen legal perusahaan (Akta, SK, NPWP, dll).
*   **Operational Permit**: Pemantauan izin operasional dan masa berlakunya.
*   **Safety License**: Pengelolaan sertifikat K3 dan lisensi personel/alat.
*   **Regulatory & E-Library**: Perpustakaan digital untuk peraturan perundang-undangan (UU, PP, Perpres, dll).
*   **Import/Export**: Dukungan impor data via CSV untuk migrasi data yang mudah.

## Teknologi

Project ini dibangun menggunakan:

*   **Backend**: Node.js dengan Express framework.
*   **Database**: MySQL (via `mysql2`).
*   **Frontend**: HTML5, Tailwind CSS, dan Vanilla JavaScript (Tanpa framework frontend berat).
*   **Styling**: Desain responsif dan modern dengan antarmuka yang ramah pengguna.

## Cara Menjalankan (Local Development)

1.  **Persiapan Database**:
    *   Pastikan MySQL server berjalan.
    *   Import file database jika tersedia, atau biarkan sistem membuat tabel secara otomatis saat dijalankan.

2.  **Instalasi Dependensi**:
    ```bash
    cd backend
    npm install
    ```

3.  **Menjalankan Server**:
    ```bash
    npm start
    ```
    Server akan berjalan pada port yang ditentukan (default: 3009 atau 3000).

4.  **Akses Aplikasi**:
    Buka browser dan kunjungi `http://localhost:3009` (sesuaikan dengan port yang muncul di terminal).

## Struktur Project

*   `backend/`: Kode sumber server, API endpoints, dan logika bisnis.
*   `frontend/public/`: Halaman statis HTML, aset gambar, CSS, dan file JavaScript client-side.

## Lisensi

Private & Confidential - Compliance System Alysa Milano.
