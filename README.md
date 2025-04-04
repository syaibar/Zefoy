# 🎯 Zefoy Views Automation Script
Automasi untuk menambahkan views TikTok secara otomatis melalui situs **zefoy.com**, menggunakan OCR (Tesseract) untuk bypass CAPTCHA. Script ini ditulis dalam **Python**, cocok untuk keperluan eksperimen dan edukasi seputar otomasi web.


## 📁 Struktur Folder
```
📂 repo-zefoy/
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
git clone https://github.com/username/repo-zefoy.git
cd repo-zefoy
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


## Warning
Using Zefoy to increase TikTok views comes with risks, including the potential violation of TikTok’s terms of service. Excessive use may result in penalties such as account suspension or banning. Always use this tool responsibly and ensure your actions comply with TikTok’s rules and legal guidelines to avoid any negative consequences.
