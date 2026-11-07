# Rangkuman Materi Workshop

## 1. Prompt Engineering
Prompt engineering merupakan proses merancang instruksi agar AI menghasilkan respons yang relevan dan sesuai dengan kebutuhan pengguna.

Materi menjelaskan bahwa prompt yang memiliki konteks jelas dapat menghasilkan keluaran yang lebih terarah daripada instruksi yang terlalu umum.

Struktur prompt yang diperkenalkan terdiri atas:
- **Role:** Peran yang diberikan kepada AI.
- **Task:** Tugas yang perlu dikerjakan.
- **Context:** Informasi dan persyaratan yang mendukung tugas.
- **Format:** Bentuk hasil yang diharapkan.

## 2. Pengenalan Git
Git merupakan distributed version control system yang digunakan untuk mencatat dan mengelola perubahan file dalam suatu proyek.

Git dikembangkan oleh Linus Torvalds pada tahun 2005. Dengan Git, pengguna dapat menyimpan riwayat perubahan dan menelusuri perkembangan proyek.

## 3. Perbedaan Git dan GitHub
Git adalah sistem version control yang dapat digunakan secara lokal, sedangkan GitHub adalah platform berbasis web untuk menyimpan repository Git secara online dan mendukung kolaborasi.

## 4. Git Workflow
Git workflow melibatkan tiga komponen utama:

1. **Working Directory:** Tempat file proyek dibuat dan dimodifikasi.
2. **Staging Area:** Tempat mempersiapkan perubahan sebelum disimpan sebagai commit.
3. **Git Directory:** Tempat Git menyimpan objek dan metadata riwayat proyek.

## 5. Perintah Dasar Git
- `git init`: Membuat repository Git lokal.
- `git add .`: Menambahkan perubahan ke staging area.
- `git add -A`: Menambahkan seluruh perubahan, termasuk penghapusan file, ke staging area.
- `git commit -m "pesan"`: Merekam perubahan dalam commit.
- `git clone URL`: Menyalin repository dari lokasi lain.
- `git remote add origin URL`: Menghubungkan repository lokal dengan repository remote.
- `git push origin main`: Mengirim commit dari branch lokal main ke remote.
- `git pull origin main`: Mengambil dan mengintegrasikan perubahan dari remote.

## 6. Konfigurasi Git
Pengguna dapat memeriksa instalasi dan mengatur identitas Git menggunakan:

```bash
git --version
git config --global user.name "Nama Pengguna"
git config --global user.email "email@example.com"
git config --global --list
```

## 7. SSH dan GitHub
Workshop juga membahas pembuatan SSH key menggunakan algoritma Ed25519 serta penambahan public key ke pengaturan GitHub.

SSH key digunakan untuk autentikasi saat mengakses GitHub melalui protokol SSH tanpa harus memasukkan kata sandi akun pada setiap operasi.

## 8. Praktik Student Task Planner
Materi praktik memperkenalkan pengembangan aplikasi sederhana bernama Student Task Planner dengan bantuan AI.

Aplikasi ini dirancang untuk membantu mahasiswa mencatat tugas, tenggat waktu, serta status penyelesaian tugas.

Alur praktik yang diperkenalkan:
1. Menyiapkan platform AI.
2. Menulis prompt pengembangan aplikasi.
3. Menginisialisasi Git.
4. Melakukan commit dan push ke GitHub.
5. Memodifikasi proyek.
6. Melakukan commit dan push kembali untuk menyimpan perubahan.