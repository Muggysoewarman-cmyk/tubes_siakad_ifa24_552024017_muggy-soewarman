# SIAKAD — Sistem Informasi Akademik Sederhan






> Tugas Besar Mata Kuliah Web II   
> **Nama:muggy soewarman 
> **NPM: 5520124017 
> **Kelas: IF-A  

---

## Deskripsi Aplikasi

SIAKAD adalah aplikasi web berbasis **Laravel** yang mensimulasikan Sistem Informasi Akademik sederhana. Aplikasi ini memungkinkan pengelolaan data dosen, mahasiswa, mata kuliah, jadwal perkuliahan, dan Kartu Rencana Studi (KRS) dengan sistem **role-based access control** (Admin & Mahasiswa).

---


## Penjelasan Halaman

| Halaman | Deskripsi |
|---------|-----------|
| `/login` | Halaman login untuk semua user |
| `/dashboard` | Dashboard utama (berbeda per role) |
| `/dosen` | CRUD data dosen (Admin) |
| `/mahasiswa` | CRUD data mahasiswa (Admin) |
| `/matakuliah` | CRUD data mata kuliah (Admin) |
| `/jadwal` | CRUD jadwal perkuliahan (Admin) |
| `/krs` | Lihat semua KRS mahasiswa (Admin) |
| `/mhs/jadwal` | Lihat jadwal perkuliahan (Mahasiswa) |
| `/mhs/krs` | Ambil/drop mata kuliah KRS (Mahasiswa) |

---

## Teknologi yang Digunakan

- **Framework:** Laravel 11
- **Auth & Role:** Spatie Laravel Permission
- **Database:** MySQL
- **Frontend:** Bootstrap 5 + Font Awesome 6
- **ORM:** Eloquent Laravel

---



## Akun Default

| Role | Email | Password |
|------|-------|----------|
| Admin | admin@siakad.com | password |
| Mahasiswa | arif@siakad.com | password |

---

## Screenshots

Lihat folder [`screenshots/`](./screenshots/) untuk tampilan setiap halaman.
