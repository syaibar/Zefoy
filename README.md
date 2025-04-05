# 🎯 Zefoy Views Automation Script
![Zefoy](https://github.com/user-attachments/assets/f0ac0fef-d4a3-46d7-b77c-c7ee95d6a9da)

Automasi untuk menambahkan views TikTok secara otomatis melalui situs zefoy.com, menggunakan OCR (Tesseract) untuk bypass CAPTCHA. Script ini ditulis dalam Python, cocok untuk keperluan eksperimen dan edukasi seputar otomasi web.

💻 Script ini dirancang untuk dijalankan melalui Command Prompt (CMD) di Windows, dan membutuhkan pengaturan path Tesseract secara manual agar dapat berjalan dengan optimal.

📱 Klik [https://github.com/RozhakXD/Zefoy](https://github.com/RozhakXD/Zefoy) untuk versi yang bisa dijalankan di Termux.

## 📁 Struktur Folder
```
📂 Zefoy/
├── 📁 Penyimpanan/         # Folder untuk menyimpan gambar CAPTCHA
├── 📄 RunCMD.py            # Script untuk dijalankan di CMD Windows!
├── 📄 RunTermux.py         # Script untuk dijalankan di Termux!
├── 📄 requirements.txt     # Daftar library Python yang dibutuhkan
└── 📄 README.md            # Dokumentasi project
```


## ✨ Fitur
- ✅ **Bypass CAPTCHA** menggunakan `Tesseract OCR`
- ✅ Deteksi **Cloudflare protection**
- ✅ Kirim **views TikTok otomatis** via `zefoy.com`
- ✅ Ulangi request hingga views berhasil
- ✅ Tampilan output rapi dengan `rich`


## 💻 Instalasi di WINDOWS!
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
*Windows: [Download dari situs resmi Tesseract](https://github.com/tesseract-ocr/tesseract/releases)*

Setelah instalasi, sesuaikan path Tesseract di `Run.py`:
```python
pytesseract.pytesseract.tesseract_cmd = r'C:\Program Files\Tesseract-OCR\tesseract.exe'
```


## 📱 Instalasi di TERMUX!
Jalankan perintah dibawah ini:
```
$ pkg update -y && pkg upgrade -y
$ pkg install git python-pip tesseract
$ git clone https://github.com/syaibar/Zefoy.git
$ cd "Zefoy"
$ pip install -r requirements.txt
$ python RunTermux.py
```


## ▶️ Cara Menjalankan di CMD Windows dan Termux!
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

## Peringatan!!
Menggunakan Zefoy untuk meningkatkan jumlah views di TikTok memiliki risiko, termasuk kemungkinan melanggar ketentuan layanan TikTok. Penggunaan yang berlebihan dapat mengakibatkan penalti seperti penangguhan atau pemblokiran akun. Gunakan alat ini secara bijak dan pastikan setiap tindakan Anda tetap sesuai dengan aturan TikTok serta pedoman hukum yang berlaku agar terhindar dari konsekuensi negatif.
