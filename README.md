# 🍌 Banana Detect-Version
### Sistem Deteksi Kondisi Pisang Berbasis YOLOv11

Banana Segar Busuk adalah aplikasi computer vision berbasis browser yang digunakan untuk mendeteksi kondisi pisang secara real-time menggunakan model **YOLOv11**.

Project ini dibuat untuk menunjukkan bagaimana teknologi **Edge AI** dapat dijalankan langsung di browser tanpa memerlukan backend server tambahan.

Masalah yang ingin diselesaikan:
- Membantu identifikasi kondisi pisang secara otomatis
- Mengurangi pengecekan manual
- Menyediakan sistem lightweight yang dapat dijalankan di berbagai device

---

# 🧠 Arsitektur Model

Project ini menggunakan model **YOLOv11 Nano (YOLOv11n)** karena:

- Ringan dan cepat
- Cocok untuk edge devices
- Optimal untuk inferensi real-time
- Kompatibel dengan ONNX Runtime Web

Teknologi yang digunakan:
- YOLOv11
- ONNX Runtime Web
- WebAssembly (WASM)
- JavaScript ES6
- HTML5 Canvas

---

# 📂 Struktur Project

```bash
banana_segar_busuk/
│
├── index.html      # Tampilan utama aplikasi
├── app.js          # Logika inferensi & deteksi
├── best.onnx       # Model YOLOv11
└── README.md
```

# 👨‍💻 Author

IKMAL CHAERUL IHSAN, ANURIFA, M.REVAN DWIANSYAH

> 🧠 AI bukan hanya tentang teknologi masa depan — tetapi tentang membantu memilih kualitas terbaik hari ini.
