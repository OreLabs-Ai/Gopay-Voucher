![Deskripsi Gambar](https://i.postimg.cc/0QbZ9ZGr/Screenshot-2025-02-10-12-21-25-87-61c78dc80ee02b53007c815fefe993e3.jpg)

# Script Gojek-Gopay Premium

**Deskripsi:**  
Script ini dirancang untuk mengotomatisasi pendaftaran akun Gojek dan klaim voucher secara otomatis, **tanpa harus login langsung ke aplikasi**. Hal ini penting karena login langsung bisa bikin akun kamu terdeteksi. Jadi, script ini mengambil pendekatan yang lebih aman dan tersembunyi.

## Fitur Utama

- **Otomatisasi Registrasi:**  
  Menggunakan nomor ponsel, script ini secara otomatis mendaftarkan akun dengan mengatur device info (nama device, GPU, kode unik device, dll). Setiap nomor akan tercatat dengan device dan kode uniknya sendiri, sehingga tidak ada dua akun yang identik.

- **Penggunaan Proxy Perumahan:**  
  Script ini otomatis mengambil daftar proxy perumahan dan menyesuaikannya dengan data device. Ini membantu menghindari deteksi karena setiap registrasi tampak berasal dari lingkungan yang berbeda.

- **Logging yang Rapi:**  
  Semua aksi (misalnya cek voucher, pendaftaran) akan tercatat dengan rinci. Jadi, kamu bisa dengan mudah melacak aktivitas setiap akun, mulai dari nomor ponsel hingga device info yang unik.

- **Update Otomatis & Notifikasi:**  
  Jika ada update atau masalah, script akan mendeteksinya dan mengirim laporan ke admin. Admin akan segera memperbaiki masalah tersebut. Proses update dilakukan secara otomatis melalui server, jadi kamu nggak perlu repot-repot update manual.

## Persyaratan

- **Sistem Operasi:**  
  - **Wajib:** VPS Linux Ubuntu  
  - **Alternatif:** Termux (boleh dipakai asal HP kamu sudah di-root)

- **Dependensi:**  
  Pastikan untuk menginstal Python dan pip. Selanjutnya, dependencies lainnya bisa diinstal otomatis melalui file `requirements.txt` saat setup di VPS baru.

## Aturan Penggunaan

### Boleh Dilakukan
- Menggunakan script untuk mendaftar akun dan klaim voucher selama tidak melanggar aturan dan ketentuan yang berlaku.

### Tidak Boleh Dilakukan
- Mengirim laporan ke email Gojek dengan cepat.
- Mencoba mendekode atau membongkar script.
- Melaporkan admin ke pihak berwajib.
- Mendaftar akun Gojek tanpa menggunakan proxy perumahan.
- Meminta diskon saat pembelian script.

## FAQ (Pertanyaan & Jawaban)

1. **Boleh tanya seputar penggunaan atau error script?**  
   Boleh, selama pertanyaan terkait error yang muncul karena kesalahan script, bukan karena kesalahan pada pengguna. Untuk pertanyaan lebih mendalam, kamu bisa langsung bertanya ke bot Open AI yang disediakan oleh admin untuk yang memiliki seluruh pemahaman mengenai script ini. dia akan membantu mu.

2. **Apakah script ini akan selalu bisa dipakai meski Gojek melakukan update?**  
   Pasti! Setiap masalah pasti ada jalan keluarnya. Kalau masih terkait deteksi (misalnya API detect bot), biasanya cukup dengan penyesuaian kecil. Admin selalu siap mengatasi kendala yang muncul.

3. **Bagaimana dengan garansi script?**  
   Jika suatu saat script tidak bisa digunakan lagi karena masalah berat (misalnya admin memasang "bendera putih"), ada garansi 12 bulan. Dalam kondisi tersebut, admin akan mengembalikan 40% dari uang pembelian kepada kamu.

4. **Verifikasi IP VPS yang tiap bulan berubah gimana?**  
   Kamu perlu melakukan verifikasi IP melalui bot verifikasi (https://t.me/verifv3bot). Prosesnya dengan memasukkan username dan password yang diberikan admin. Max 2 IP per user per bulan. Jika VPS kamu dibanned sebelum satu bulan, hubungi admin untuk penghapusan IP lama.

## Cara Instalasi (untuk VPS Linux)

1. Clone repository:
   ```bash
   git clone https://github.com/OreLabs-Ai/Gopay-Voucher.git
   ```

2. Masuk ke direktori repository:
   ```bash
   cd Gopay-Voucher
   ```

3. Instal dependensi:
   ```bash
   pip3 install -r requirements.txt
   ```

4. Jalankan script:
   ```bash
   python3 go.py
   ```

5. Jika terjadi delay, harap menunggu sampai 5-10 menit.

---

## Cara Instalasi (untuk Termux di Android)

> **Catatan:** Pastikan HP kamu sudah di-root jika ingin menggunakan Termux.

1. Instal Git dan Python:
   ```bash
   pkg install git python
   ```

2. Clone repository:
   ```bash
   git clone https://github.com/OreLabs-Ai/Gopay-Voucher.git
   ```

3. Masuk ke direktori repository:
   ```bash
   cd Gopay-Voucher
   ```

4. Instal dependensi:
   ```bash
   pip3 install -r requirements.txt
   ```

5. Jalankan script:
   ```bash
   python3 go.py
   ```

6. Jika terjadi delay, harap menunggu sampai 5-10 menit.



## Catatan Tambahan

- **Penggunaan di Windows:**  
  Meskipun bisa dipakai di Windows, disarankan untuk menggunakan VPS. Jika pakai Windows, pastikan spesifikasinya mumpuni (minimal RAM 8GB, ideal 8-32GB) karena prosesnya akan delay jika speknya rendah.

- **Setup Awal:**  
  Instalasi awal cuma perlu mengatur dependensi (Python, pip, dll). Sisanya bisa langsung diatur via `requirements.txt` untuk instalasi otomatis. Setelah itu, biaya operasional hanya berupa bulanan VPS dan verifikasi IP melalui bot.

## Kontak

Jika ada pertanyaan lebih lanjut, silakan hubungi saya melalui:  

📞 **WhatsApp:** [+62 831-3982-4761](https://wa.me/6283139824761)  
✉️ **Email:** [indraaa-f@neezc.art](mailto:indraaa-f@neezc.art)  
📲 **Telegram:** [@neezc](https://t.me/neezc)

---

