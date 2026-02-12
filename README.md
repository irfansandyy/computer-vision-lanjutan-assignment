# Tugas Computer Vision Lanjutan

| Nama | NRP | Prodi |
|------|-----|-------|
| `...`|`...`| `...` |

## Links

### Link Video Demonstrasi (Youtube / Drive)

`...`

### Link Dataset Terlabel (Roboflow / Drive)

`...`

### Link Modul

[github.com/magang-bayucaraka-2026/modul-computer-vision-lanjutan](https://github.com/magang-bayucaraka-2026/modul-computer-vision-lanjutan)

### Link Dataset RAW

[drive.google.com](https://drive.google.com/drive/folders/1ztX09HlvcyN7Eqma3oeeyvcdcZv0j3Gx)

## Deskripsi Tugas

Ukuran payload LxWxH => 25cm x 25cm x 3cm

### Tugas 1

Label data yang ada di folder videos dan kumpulkan hasil label pada kolom link yang tertera diatas.

### Tugas 2

Train dataset yang telah dilabel dan kumpulkan model yang telah di train pada folder `/model` di repository ini (file dalam format `.pt` dan `.onnx`).

### Tugas 3

Buat script untuk melakukan inference (atau training kalo training lokal) pada model yang telah di train. Hitung juga estimasi letaknya pada koordinat real world 3D (X,Y,Z) dengan asumsi kamera menghadap ke bawah pada permukaan datar. Kumpulkan script pada folder `/src` di repository ini dalam bentuk `.ipynb` (jupyter notebook) lengkap dengan penjelasan kodenya.

#### Opsi Lainnya

Kalau kalian pake google colab bisa kumpulkan link colabnya disini:

`...`

### Tugas 4

Buat video demonstrasi dari hasil tugas 1-3 (dan tugas tambahan kalau mengerjakan) dan kumpulkan pada kolom link yang tertera diatas.

### Tugas Tambahan (Opsional)

Buat ROS Node yang mempublish koordinat benda yang dideteksi ke topic (titik 0,0,0 terserah dimana).
