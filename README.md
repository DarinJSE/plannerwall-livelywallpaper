# 🌿 Planner Wall — Interactive Productivity Wallpaper

**Planner Wall** adalah *personal productivity dashboard* yang bisa dijadikan wallpaper interaktif di **Lively Wallpaper**.  
Project ini menggabungkan todo list, rutinitas harian, kalender, mode fokus, Pomodoro timer, dan statistik progres — semuanya dalam satu interface yang clean dan responsif.

## 🧩 Fitur Utama
- 🖼️ **Wallpaper Mode:** Tampilin quote acak buat ningkatin mood.
- 📅 **Planner Mode:** Liat daftar todo berdasarkan tanggal.
- ✅ **Routine Tracker:** Tambah rutinitas harian dan pantau streak.
- 🍅 **Pomodoro Timer:** Biar fokus kerja lo nggak buyar.
- 📊 **Stats Mode:** Liat heatmap, top streaks, dan progress mingguan.
- 🎯 **Focus Zone:** Mode fokus dengan timer & motivasi quote.
- 🌗 **Dark / Light Theme Toggle.**
- 🎉 **Confetti Animation:** Muncul tiap lo nyelesain sesuatu.

## 🛠️ Tech Stack
- **HTML5 + CSS3 + JavaScript (Vanilla)**
- **Chart.js** untuk chart statistik
- **localStorage API** untuk penyimpanan data lokal
- **Lively Wallpaper** sebagai platform tampilan interaktif

## ⚙️ Cara Jalanin
1. Buka file `Planner-Wall-patch2.html` langsung di browser (untuk tes).
2. Kalo mau dijadiin wallpaper, tambahin ke **Lively Wallpaper**:
   - Buka app Lively → *Add Wallpaper* → pilih file HTML ini.
   - Atur scaling & interaksi sesuai preferensi lo.
3. Semua data (todo, rutinitas, progres) otomatis kesimpen di browser lewat localStorage.

## 🧠 Cara Pakai
- Tambah **tugas** di panel kanan, klik tanda centang buat nyelesain.
- Tambah **rutinitas harian** di panel tengah, set target bulanan.
- Klik **Reset Today** buat mulai ulang status rutinitas harian.
- Pindah antar mode lewat tombol header (Wallpaper, Planner, Stats, Focus, dll).

## 🗂️ Struktur Project
```
index.html   # Semua UI + logic dalam satu file
```

## 🚀 Ide Pengembangan Selanjutnya
- Sinkronisasi data ke cloud (Firebase / Supabase).
- Custom quotes & tema.
- Integrasi dengan kalender eksternal (Google Calendar API).
- Notifikasi desktop saat timer selesai.

## 📜 Lisensi
Project latihan pribadi — bebas dipelajari dan di-modifikasi untuk tujuan non-komersial.
