# Penerjemah Variabel Masal

Ini adalah alat untuk menerjemahkan variabel dalam format [bahasa]=[terjemahan] menggunakan Python. Alat ini memungkinkan Anda untuk menerjemahkan banyak folder atau file sekaligus.

## Cara Penggunaan

1. Clone repositori ini ke dalam direktori lokal Anda:

```bash
git clone https://github.com/Mabzak-Knight/penerjemah-variabel-masal.git
```
```bash
cd penerjemah-variabel-masal
pip install -r requirements.txt
from penerjemah import *
```
Untuk menerjemahkan dan menyimpan file, gunakan fungsi terjemahkan_dan_simpan():
```bash
terjemahkan_dan_simpan('lokasi_file_input', 'lokasi_file_output')
```
Contoh:

```bash
terjemahkan_dan_simpan('/content/tes.txt', 'hasil_tes.txt')
```
