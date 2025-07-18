# NOTIFCARE

### Ganti Alert, Confirm, Prompt, dan File Input kamu jadi lebih modern dan fleksibel dengan **Notifcare**!

Notifcare menghadirkan berbagai macam *interaction box* (seperti alert bawaan JavaScript) dengan tampilan yang lebih menarik dan opsi kostumisasi penuh (termasuk tanpa CSS). Yuk, pelajari cara penggunaannya!

---

## DAFTAR ISI
- [Instalasi](#instalasi)
  - [Cara Pakai](#penggunaan)
    - [Alert](#alert)
    - [Confirm](#confirm)
    - [Prompt](#prompt)
    - [File Input](#file-input)
    - [Ads Box](#ads)
    - [Toast](#toast)
    - [loading](#loading)
  - [Kostumisasi](#kostumisasi)
    - [Custom Fonts](#ganti-font)
    - [Full Custom (Tanpa CSS Default)](#full-custom)
- [Change Log](#change-log)

---

## INSTALASI

Lihat dokumentasi pada:

📄 https://notifcare.vercel.app/article/?id=0

---

## CHANGE LOG

### Version (V1.2.1) ✅⚙️ *(Sab, 20 Jul 2025)*

🔧 **Fix:**
- 🚫 Beberapa bug file `notifcare.css` dan modul seperti `alert.js`, `confirm.js` tidak dimuat otomatis saat `notifcare.js` dipanggil terlalu awal.

✅ **Solusi:**
- 📦 Modul kini otomatis tersedia meskipun `notifcare.js` ditaruh di `<head>` tanpa atribut `defer`.

---

### Version (V1.2.0) 🎯🔥 *(Jum, 18 Jul 2025)*

🚀 **Update Besar – Modularisasi Fungsi**

✨ Manajemen file kini lebih ringan dan fleksibel.

✅ **Penambahan Fitur Baru:**
- 🔸 `Notifcare.Toast()` – menampilkan notifikasi mengambang ringan (top-left, top-right, bottom-left, bottom-right).
- 🔸 `Notifcare.Loading()` – tampilan loading animasi dengan opsi pesan, mode terang/gelap, dan auto-close timer.

📌 **Catatan Developer:**
- Untuk pemakaian optimal, pastikan file `notifcare.js` ditempatkan sebelum `</body>`.
- Versi ini memberikan dasar kuat untuk plugin eksternal dan pengembangan fitur lebih lanjut.

### Version (V1.1.1 - V1.1.2)
- 🔧 **Fix:** Masalah pada pemanggilan file `notifcare.css` yang tidak termuat otomatis telah diperbaiki.  
  Kini **CSS** akan terhubung dengan benar melalui CDN tanpa perlu tambahan manual.
- 🔁 Pembaruan ini sekaligus menyempurnakan bug serupa yang sempat terjadi di versi `1.1.1`.

### Version (V1.1.0)
- 🌟 **Fitur Baru:**
  - `timer` – atur durasi otomatis menutup box, contoh: `timer: 5000` (milidetik).
  - `timerStatus` – tampilkan progress bar timer jika `true`.
  - `iconType` – tambahkan ikon custom, contoh: `<i class="ri-delete-bin-line"></i>`.
- 🔁 **Peningkatan:**  
  🎞️ Animasi kini berlaku untuk ikon berdasarkan `type` seperti `"success"`, `"danger"`, dll.

### Version (V1.0.6)
- 🔧 **Fix:** Bug ikon ganda saat menggunakan `type` seperti `"danger"`, `"info"`, dll sudah diperbaiki.  
  Ikon default kini hanya muncul satu.

### Version (V1.0.5) *(Initial Release)*
- 🚀 **Notifcare resmi dirilis!**
- 🎨 Menggantikan alert dan confirm bawaan browser:
  - `Notifcare.Alert` – tampilkan pesan stylish.
  - `Notifcare.Confirm` – konfirmasi dengan dua tombol dan respons callback.
- 💡 Antarmuka ringan, fleksibel, dan profesional.
