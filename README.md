# demo-streamlit-chatbot-v3
Latihan Project LLM-Based Tools and Gemini API Integration for Data Scientists - Partnership H8 By Hacktiv8

TERIMA KASIH DIUCAPKAN KEPADA PIHAK HACKTIV8 & MAS ADIPTA MARTULANDI ! 

---

# SiCakap (Sistem Chat Pintar)

💬 **SiCakap** adalah aplikasi chatbot interaktif berbasis Streamlit yang didukung Google Gemini (LangChain) dan dapat menganalisis file yang diupload oleh pengguna. Cocok untuk curhat, tanya jawab, analisis data, dan diskusi dokumen!

---

## Fitur Utama

- **Chatbot AI**: Jawab pertanyaan dan diskusi dengan model Gemini dari Google.
- **Upload File PDF, TXT, Excel (CSV/XLSX)**: Chatbot dapat membaca dan mengkaji isi file yang diupload.
- **Analisis Data Excel**: Menampilkan ringkasan data (jumlah baris, kolom, nama kolom, dan 5 data teratas) dari file Excel.
- **Tampilan Modern**: Background dark gradient yang elegan dan ramah di mata.
- **Reset Chat**: Mulai percakapan baru kapan saja.

---

## Cara Menjalankan

1. **Clone repository**
    ```bash
    git clone https://github.com/<username>/<repo-name>.git
    cd <repo-name>
    ```
2. **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```
3. **Jalankan aplikasi**
    ```bash
    streamlit run streamlit_react_app.py
    ```
4. **Masukkan Google AI API Key** di sidebar aplikasi.
5. **Mulai chat dan upload file** sesuai kebutuhan.

---

## Contoh Penggunaan

- Upload file PDF untuk dikaji isinya oleh chatbot.
- Upload file Excel dan dapatkan ringkasan data serta analisis langsung dari chatbot.
- Chat bebas untuk curhat, tanya jawab, atau diskusi data.

---

## Struktur Folder

```
chatbot-streamlit-demo/
├── streamlit_react_app.py      # Main chatbot app
├── requirements.txt           # Daftar library yang dibutuhkan
├── README.md                  # Dokumentasi aplikasi
├── ...                        # File dan folder lain
```

---

## Konfigurasi API

- Diperlukan API Key Google Gemini. Masukkan di sidebar aplikasi.

---

## Lisensi

Aplikasi ini menggunakan lisensi MIT. Silakan gunakan, modifikasi, dan distribusikan sesuai kebutuhan.

---

## Kontribusi

Kontribusi sangat terbuka! Silakan fork, buat pull request, atau laporkan issue untuk pengembangan lebih lanjut.

---

## Kontak

Untuk pertanyaan atau kerjasama, silakan hubungi melalui GitHub Issues atau email yang tertera di profil.

---

Selamat mencoba SiCakap! 🚀
