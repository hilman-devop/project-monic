# MONIC — Aquaponic IoT Monitoring

![Python](https://img.shields.io/badge/Python-2f81f7?style=flat) ![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-2f81f7?style=flat) ![DHT22](https://img.shields.io/badge/DHT22-2f81f7?style=flat) ![HC-SR04](https://img.shields.io/badge/HC-SR04-2f81f7?style=flat) ![Ubidots](https://img.shields.io/badge/Ubidots-2f81f7?style=flat) ![RPi.GPIO](https://img.shields.io/badge/RPi.GPIO-2f81f7?style=flat)

> Proyek IoT untuk memantau suhu, kelembapan, dan level air secara berkala pada instalasi aquaponik.

## Tentang proyek

Proyek IoT untuk memantau suhu, kelembapan, dan level air secara berkala pada instalasi aquaponik. Dokumentasi ini dibuat sebagai panduan singkat untuk memahami ruang lingkup proyek, menjalankannya secara lokal, dan membaca batasan penggunaannya.

## Fitur utama

- Monitoring suhu dan kelembapan
- Pengukuran level air dengan ultrasonic
- Pengiriman telemetri ke cloud
- Modul sensor terpisah
- Dirancang untuk pengembangan aktuator pompa dan notifikasi

## Teknologi

- Python
- Raspberry Pi
- DHT22
- HC-SR04
- Ubidots
- RPi.GPIO

## Menjalankan secara lokal

Prasyarat dan konfigurasi dapat berbeda menurut sistem operasi. Contoh langkah utama:

```bash
pip install -r requirements.txt
python kirim_ubi.py
```

## Struktur dan pengembangan

Mulai dari entry point dan folder konfigurasi proyek. Pisahkan credential lokal dari source code, tambahkan test untuk perubahan penting, dan gunakan environment variable untuk konfigurasi deployment.

## Keamanan

- Jangan commit API key, password, token, session ID, atau data pribadi.
- Gunakan file environment lokal dan contoh konfigurasi tanpa nilai rahasia.
- Uji perubahan pada environment development sebelum deployment.

## Status

Proyek ini merupakan bagian dari portofolio **Hilman Arifin Ilham** dan dapat dikembangkan sesuai kebutuhan penggunaan.

> **Catatan:** Credential Ubidots harus dibuat ulang dan disediakan melalui konfigurasi lokal. Token tidak disimpan di repository publik.

## Lisensi

Belum ada lisensi open-source yang dinyatakan di repository ini. Hubungi pemilik repository sebelum menggunakan ulang atau mendistribusikan kode.

---

Dibuat oleh [Hilman Arifin Ilham](https://github.com/hilman-devop).
