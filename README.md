# Transkripsi YouTube dengan Python

Repository ini menyediakan skrip sederhana menggunakan Python untuk mentranskripsi audio dari video YouTube menjadi teks. Skrip ini menggunakan Libary PyTube untuk mengunduh audio dari video YouTube, model Whisper ASR (Automatic Speech Recognition) dari OpenAI untuk mentranskripsi, dan Langdetect untuk deteksi bahasa.

### Anggota Kelompok
|**No**| **Nama** | **NIM** |
|------|----------|---------|
| 1 | Abdurrahman Ridho | 21.11.4341 |
| 2 | Oxa Defrizal Khasay | 21.11.4388 |
| 3 | Hamim Nur Khamid | 21.11.4395 |

## Repositori Referensi
Proyek ini terinspirasi dan diadaptasi dari [javedali99/audio-to-text-transcription](https://github.com/javedali99/audio-to-text-transcription). Terima kasih khusus kepada penulis asli yang menyediakan dasar untuk alat transkripsi ini.

## Daftar Isi
1. [Instalasi](#installation)
2. [Penggunaan](#usage)
3. [Ketergantungan](#dependencies)
4. [Cara Kerja](#how-it-works)
5. [Lisensi](#license)

## Instalasi

Sebelum menjalankan skrip, pastikan untuk menginstal ketergantungan yang diperlukan:

```bash
!pip install pytube
!pip install git+https://github.com/openai/whisper.git
!pip install langdetect
```
## Penggunaan
1. Klon repository ini:  https://github.com/OxaDefrizal/ml_transcribe_video.git
2. Jalankan skrip:
3. Masukkan URL video YouTube ketika diminta.
4. Skrip akan mengunduh audio, mentranskripsikannya menjadi teks, dan menyimpannya dalam file teks (misalnya, Hasil Transkripsi_id.txt). Bahasa secara otomatis terdeteksi.

## Ketergantungan
* PyTube: Mengambil konten YouTube.
* Whisper ASR: Model ASR dari OpenAI.
* Langdetect: Mendeteksi bahasa dari teks yang ditranskripsi.

## Cara Kerja
1. Input Video YouTube: Pengguna memberikan URL video YouTube.
2. Unduh Audio: PyTube mengunduh aliran audio.
3. Transkripsi: Whisper ASR mentranskripsi audio.
4. Deteksi Bahasa: Langdetect menentukan bahasa.
5. Output Teks: Teks yang ditranskripsi disimpan dalam file dengan informasi bahasa.

## Lisensi
Kontribusi dipersilakan. Laporkan masalah atau usulkan perbaikan melalui GitHub.
