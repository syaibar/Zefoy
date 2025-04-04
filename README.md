# 🎯 Zefoy Views Automation Script
Automasi untuk menambahkan views TikTok secara otomatis melalui situs **zefoy.com**, menggunakan OCR (Tesseract) untuk bypass CAPTCHA. Script ini ditulis dalam **Python**, cocok untuk keperluan eksperimen dan edukasi seputar otomasi web.


## 📁 Struktur Folder
```
📂 Zefoy/
├── 📁 Penyimpanan/         # Folder untuk menyimpan gambar CAPTCHA
├── 📄 Run.py               # Script utama automasi
├── 📄 requirements.txt     # Daftar library Python yang dibutuhkan
└── 📄 README.md            # Dokumentasi project
```


## ✨ Fitur
- ✅ **Bypass CAPTCHA** menggunakan `Tesseract OCR`
- ✅ Deteksi **Cloudflare protection**
- ✅ Kirim **views TikTok otomatis** via `zefoy.com`
- ✅ Ulangi request hingga views berhasil
- ✅ Tampilan output rapi dengan `rich`


## ⚙️ Instalasi
Clone repositori:
```
git clone https://github.com/syaibar/Zefoy.git
cd Zefoy
```

Install dependencies Python:
```
pip install -r requirements.txt
```

Install Tesseract OCR:  
*Windows: Download dari situs resmi Tesseract*

Setelah instalasi, sesuaikan path Tesseract di `Run.py`:
```python
pytesseract.pytesseract.tesseract_cmd = r'C:\Program Files\Tesseract-OCR\tesseract.exe'
```


## ▶️ Cara Menjalankan
```
python Run.py
```

Script akan:
- Mengakses `zefoy.com`
- Menyimpan CAPTCHA ke dalam folder `Penyimpanan`
- Membaca CAPTCHA via `Tesseract OCR`
- Mengisi formulir video secara otomatis
- Mengirim views secara berulang


## ⚠️ Catatan Penting
- **CAPTCHA** harus terbaca jelas agar proses berhasil.
- Jika mendeteksi **Cloudflare**, script akan keluar otomatis.
- Website `zefoy.com` bisa berubah sewaktu-waktu.
- **Gunakan hanya untuk edukasi dan pembelajaran.**
- Menggunakan Zefoy untuk meningkatkan jumlah views di TikTok memiliki risiko, termasuk kemungkinan melanggar ketentuan layanan TikTok. Penggunaan yang berlebihan dapat mengakibatkan penalti seperti penangguhan atau pemblokiran akun. Gunakan alat ini secara bijak dan pastikan setiap tindakan Anda tetap sesuai dengan aturan TikTok serta pedoman hukum yang berlaku agar terhindar dari konsekuensi negatif.

## Peringtan!!
Menggunakan Zefoy untuk meningkatkan jumlah views di TikTok memiliki risiko, termasuk kemungkinan melanggar ketentuan layanan TikTok. Penggunaan yang berlebihan dapat mengakibatkan penalti seperti penangguhan atau pemblokiran akun. Gunakan alat ini secara bijak dan pastikan setiap tindakan Anda tetap sesuai dengan aturan TikTok serta pedoman hukum yang berlaku agar terhindar dari konsekuensi negatif.
