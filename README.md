```
  ██████╗██████╗ ██╗   ██╗██████╗ ████████╗ ██████╗  █████╗ ███╗   ███╗
 ██╔════╝██╔══██╗██║   ██║██╔══██╗╚══██╔══╝██╔═══██╗██╔══██╗████╗ ████║
 ██║     ██████╔╝██║   ██║██████╔╝   ██║   ██║   ██║███████║██╔████╔██║
 ██║     ██╔═══╝ ██║   ██║██╔═══╝    ██║   ██║   ██║██╔══██║██║╚██╔╝██║
 ╚██████╗██║     ╚██████╔╝██║        ██║   ╚██████╔╝██║  ██║██║ ╚═╝ ██║
  ╚═════╝╚═╝      ╚═════╝ ╚═╝        ╚═╝    ╚═════╝ ╚═╝  ╚═╝╚═╝     ╚═╝
           CRYPTO | AI COACH | REAL-TIME MARKET | PYTHON
```

# CryptoAnalizer-Aii

💻 CryptoAnalizer-Aii

CryptoAnalizer-Aii adalah terminal pintar berbasis Python untuk edukasi, analisis pasar kripto & forex, serta simulasi trading real-time langsung dari perangkat Anda. Diperkuat oleh AI interaktif dan sistem keamanan login, tool ini adalah asisten belajar dan analisis yang ideal, baik untuk pemula maupun trader profesional.


---

✨ Fitur Unggulan

🔐 Sistem Login Aman

Buat akun dengan username & password unik.

Akun terhubung ke perangkat (device-bound).

Maksimum 3 percobaan login untuk mencegah brute-force.


📊 Analisis Pasar Real-Time

Menampilkan harga kripto (CoinGecko API) & forex terbaru.

Menyediakan indikator teknikal: RSI, EMA, dan analisis tren.

Prediksi harian berbasis data sederhana.


🧠 AI Coach & Mentor (Powered by Gemini AI)

Jawab pertanyaan Anda seputar:

Strategi & teknik trading

Psikologi pasar

Terminologi rumit yang dijelaskan dengan simpel


AI dapat membimbing proses belajar & pengambilan keputusan.


📰 Update Berita Pasar

Integrasi langsung dengan NewsData.io untuk mendapatkan berita harian pasar global.

Ringkasan otomatis langsung di terminal Anda.


💡 Psikologi Market & Tips Praktis

Saran & tips mengatasi fear, FOMO, dan emosi pasar lainnya.

Materi edukasi yang dikurasi berdasarkan pengalaman nyata trader.



---

⚙️ Cara Instalasi (via Termux Android)

1. Update Termux

pkg update && pkg upgrade -y

2. Izin Akses Penyimpanan

termux-setup-storage

> Tekan "Allow" saat muncul pop-up.



3. Install Git & Python

pkg install git python -y

4. Clone Repositori

git clone https://github.com/batsm75/CryptoAnalizer-Aii.git

5. Masuk ke Direktori Proyek

cd CryptoAnalizer-Aii

6. Install Dependensi Python

pip install -r requirements.txt

> Jika file requirements.txt belum tersedia, buat file dengan isi:



requests
numpy
textwrap

7. Jalankan Aplikasi

python main.py


---

🔑 Konfigurasi API Key

NewsData.io – NEWS_API_KEY

Dapatkan key gratis di NewsData.io

API Key sudah disiapkan di kode, tapi bisa diedit di main.py.


Gemini AI – GEMINI_API_KEY

Dapatkan dari Google AI Studio

Edit file main.py jika ingin menggunakan key milik Anda sendiri.


> ⚠️ Catatan Keamanan: Jangan simpan API key sensitif secara langsung di repositori publik. Gunakan .env atau os.environ untuk perlindungan lebih lanjut.




---

📄 Lisensi

Proyek ini menggunakan MIT License. Lihat file LICENSE untuk detail lengkap.


---

🤝 Kontribusi

Kami menyambut kontribusi dari siapa pun!
Buatlah issue atau kirim pull request untuk menyumbangkan ide, fitur, atau perbaikan.


---

👨‍💻 Creator

Dibuat dengan ❤️ oleh Bays Exploit


<p align="center">
  <img src="https://img.shields.io/github/stars/batsm75/CryptoAnalizer-Aii?style=social" alt="GitHub stars">
  <img src="https://img.shields.io/github/forks/batsm75/CryptoAnalizer-Aii?style=social" alt="GitHub forks">
  <img src="https://img.shields.io/github/license/batsm75/CryptoAnalizer-Aii" alt="License">
</p>


