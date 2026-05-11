# 🎊 Template Undangan Pernikahan (Ultra Premium)

Selamat! Anda memiliki kreasi terbaik dari seri undangan kami dengan pengalaman sinematik 3D yang megah.

Versi *Ultra Premium* dirancang khusus dengan fitur andalan: Efek Debu Partikel Emas 3D, Animasi Rotasi Hologram saat Hover (di bagian kartu mempelai), dan integrasi Live Streaming!

## 🛠️ Kustomisasi Tingkat Lanjut di `index.html`

1. **Ubah Data Acara**: Gunakan VS Code / Text Editor untuk mengganti Nama Mempelai, Alamat, Tanggal, dan Cerita di `index.html`.
2. **Fitur Live Streaming (YouTube/IG)**:
   - Cari baris kode penanda: `<!-- GANTI KODE DI BAWAH INI DENGAN IFRAME YOUTUBE ANDA -->`
   - Temukan tulisan `<span ...>📹 Live Stream Akan Tampil Di Sini</span>`. 
   - Hapus tulisan span tersebut, lalu **paste _Embed Code_ iframe** Live YouTube Anda di tempat tersebut.
   - Pastikan Anda mengatur iframe ke `width="100%" height="100%"` agar proporsional di HP.
3. **Ganti Musik Latar & Auto-play**: Cari tag `<audio id="weddingMusicUltra">` dan isikan link MP3 baru di dalam tag `<source src="...">` nya.

## ✨ Mengatur Efek 3D (Opsional)
Jika Anda merasa efek debu partikel berlebihan atau memberatkan perangkat, Anda temukan elemen `<div class="particles" id="particles"></div>` dan ubah menjadi `<div class="particles" id="particles" style="display: none;"></div>` (ini akan menonaktifkannya). Namun secara default efek tersebut sangat ringan dan mempesona.

## 🚀 Siap Rilis!
Pastikan mempublikasikan folder ini menggunakan **Netlify**, **Vercel**, atau **GitHub Pages** agar undangan mega mewah ini bisa dinikmati kerabat Anda secara online dari seluruh penjuru dunia dengan lancar.
