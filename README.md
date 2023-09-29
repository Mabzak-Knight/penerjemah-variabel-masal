# Penerjemah Variabel Masal

Ini adalah alat untuk menerjemahkan variabel dalam format [variabel]=[yang ingin di terjemakan], contoh anda memiliki file txt dengan isi
```bash
西瓜 (xīguā) = Watermelon
苹果 (píngguǒ) = Apple
香蕉 (xiāngjiāo) = Banana
```
jika di terjemaknan akan menjadi 
```bash
西瓜 (xīguā) = Semangka
苹果 (píngguǒ) = Apel
香蕉 (xiāngjiāo) = pisang
```
yang di terjemakna adalah isi dari variabel, program di jalankan menggunakan Python. dapat juga menerjemahkan jia file ada didalam folder dengan menzipnya

## Cara Penggunaan

Clone repositori ini ke dalam direktori lokal Anda:

```bash
git clone https://github.com/Mabzak-Knight/penerjemah-variabel-masal.git
```
Instal dependensi yang diperlukan:
```bash
cd penerjemah-variabel-masal
pip install -r requirements.txt
from penerjemah import *
```

### Menerjemahkan File txt
Untuk menerjemahkan file txt dan menyimpan file, gunakan fungsi terjemahkan_dan_simpan():
```bash
terjemahkan_dan_simpan('lokasi_file_input', 'lokasi_file_output')
```
Contoh:

```bash
terjemahkan_dan_simpan('/content/tes.txt', 'hasil_tes.txt')
```
### Menerjemahkan file.zip
Untuk menerjemahkan filez.zip yang didalamnya adalah folder yang memiliki banyak sub foder dan file txt lalu menzip kembali, dapat menggunakan fungsi menerjemahkan_zip():
```bash
menerjemahkan_zip('lokasi_file_zip', 'lokasi_file_output')
```
Contoh:

```bash
menerjemahkan_zip('/content/belum.zip','hasil_terjemahan.zip')
```
