<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=4000&pause=1000&color=00C2FF&center=true&vCenter=true&width=600&lines=ZAXXYCREATE+V2;Facebook+Account+Creator+Premium" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-2.0-blue?style=for-the-badge&logo=github" />
  <img src="https://img.shields.io/badge/python-3.8%2B-brightgreen?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/license-Proprietary-red?style=for-the-badge&logo=open-source-initiative" />
  <img src="https://img.shields.io/badge/platform-Termux%20%7C%20Linux%20%7C%20Windows%20%7C%20macOS-lightgrey?style=for-the-badge" />
</p>

<p align="center">
  <b>🔐 Alat pembuat akun Facebook otomatis dengan antarmuka premium dan sistem lisensi ekslusif.</b><br>
  <sub>Dikembangkan oleh <a href="https://github.com/ZaxxyDev78">ZaxxyDev78</a></sub>
</p>

---

## 📑 Daftar Isi
- [✨ Fitur Unggulan](#-fitur-unggulan)
- [📦 Instalasi Lengkap per Platform](#-instalasi-lengkap-per-platform)
  - [Persyaratan Sistem](#persyaratan-sistem)
  - [Termux (Android)](#-termux-android)
  - [Linux (Ubuntu/Debian, Fedora, Arch)](#-linux-ubuntudebian-fedora-arch)
  - [Windows](#-windows)
  - [macOS](#-macos)
- [🚀 Cara Menjalankan](#-cara-menjalankan)
- [🔑 Lisensi & Verifikasi](#-lisensi--verifikasi)
- [🛠 Troubleshooting](#-troubleshooting)
- [📜 Source Code](#-source-code)
- [⚠️ Peringatan Keras](#️-peringatan-keras)
- [📄 Disclaimer](#-disclaimer)
- [📞 Kontak Admin](#-kontak-admin)

---

## ✨ Fitur Unggulan
- 🔄 **Pembuatan akun massal** – atur jumlah akun yang ingin dibuat
- 🌈 **UI Premium** – tampilan Rich Console dengan panel, tree, spinner
- 👤 **Data acak realistis** – nama, tanggal lahir, gender, foto profil & cover dari Faker
- 🌐 **Multi-bahasa** – dukung Indonesia, Inggris, Mandarin, dan custom
- 🔐 **Password manual / otomatis** – fleksibel sesuai kebutuhan
- 📧 **Verifikasi email manual** – kode OTP dimasukkan langsung
- 💾 **Hasil tersimpan otomatis** – akun sukses tercatat di `/sdcard/Premium/CreateFbrif/AcounttFresh.txt`
- 🛡️ **Sistem lisensi perangkat** – hanya device terdaftar yang bisa menjalankan

---

## 📦 Instalasi Lengkap per Platform

### Persyaratan Sistem
| Komponen | Minimal |
|----------|---------|
| **Python** | 3.8 atau lebih baru |
| **pip** | terbaru |
| **Git** | opsional (bisa download ZIP) |
| **Koneksi Internet** | wajib |

---

### 📱 Termux (Android)

1. **Buka Termux** lalu perbarui dan pasang dependensi dasar:
   ```bash
   pkg update -y && pkg upgrade -y
   pkg install python git -y
   git clone https://github.com/ZaxxyDev78/CreateFacebookv2.git
   cd CreateFacebookv2
   pip install requests faker rich
   python createv2.py
