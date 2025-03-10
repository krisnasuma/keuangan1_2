# Keuangan1_2

Pastikan Python sudah terinstal, lalu instal Django menggunakan pip:
<br>
> pip install django

Pastikan pustaka html ke pdf sudah terpasang di program python anda
<br>
> pip install xhtml2pdf

xhtml2pdf sudah include beberapa dependency, seperti Pillow dan reportlab. Pastikan dependency tersebut sudah terinstal.
<br>
> pip install pillow reportlab

Kemudian akses folder projek dengan command line sampai menemukan file yang bernama "manage", lalu jalankan perintah: 
<br>
> python manage.py runserver

Akses urls Web
* Panel admin: http://127.0.0.1:8000/admin/
* Tampilan transaksi: http://127.0.0.1:8000/transaksi/
* Tampilan add transaksi tanpa perantara admin: http://127.0.0.1:8000/transaksi/tambah/
* Ekspor CSV: http://127.0.0.1:8000/transaksi/ekspor-csv/
* Backup Data: http://127.0.0.1:8000/transaksi/backup/
* Restore Data: http://127.0.0.1:8000/transaksi/restore/
* Halaman Laporan Keuangan: http://127.0.0.1:8000/transaksi/laporan/
* Cetak PDF hasil Laporan Keuangan: http://127.0.0.1:8000/transaksi/laporan/pdf/

<br>
username: admin
<br>
password: admin

# Fitur
Fitur Tambahan (Opsional)
<br>
1. Laporan Keuangan
* Membuat laporan keuangan agar bisa di eksport ke format PDF.

2. Backup dan Restore Data
* Menambahkan fitur backup dan restore database untuk keamanan data.

# Tampilan

![Sample Image](https://github.com/krisnasuma/keuangan1_2/blob/main/DaftarTransaksiBagAtasV1_2.PNG)

![Sample Image](https://github.com/krisnasuma/keuangan1_2/blob/main/DaftarTransaksiBagBawahV1_2.PNG)

![Sample Image](https://github.com/krisnasuma/keuangan1_2/blob/main/HasilBackupData.PNG)

![Sample Image](https://github.com/krisnasuma/keuangan1_2/blob/main/TampilanRestoreData.PNG)

![Sample Image](https://github.com/krisnasuma/keuangan1_2/blob/main/LaporanKeuanganV1_2.PNG)

![Sample Image](https://github.com/krisnasuma/keuangan1_2/blob/main/LaporanKeuanganPDF.PNG)

# Versi Sebelumnya
* V0: https://github.com/krisnasuma/keuangan/
* V1: https://github.com/krisnasuma/keuangan1
* V1_1: https://github.com/krisnasuma/keuangan1_1
