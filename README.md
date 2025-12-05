# ManajemenKost — Landing Page Modern (Single HTML)

Landing page manajemen kost/hospitality dengan gaya glassmorphism, palet pastel hangat, animasi halus, dan efek aurora latar. Seluruh kode ada di satu file `index.html` (CSS & JS inline) untuk deployment super cepat.

## Highlight Desain
- Glassmorphism konsisten pada hero, kartu layanan, CTA, testimoni.
- Aurora & particles layer untuk ambience lembut tanpa mengorbankan performa.
- Typography tebal + spacing longgar untuk hierarki jelas.
- Animasi scroll (fade-in), hover lembut, dan tombol gradient.
- Responsif: grid layanan/testimoni otomatis menjadi 1 kolom di mobile.

## Palet Warna
- Primary/Accent: `#FFD6BA`, `#FFE8CD`, `#FFDCDC`
- Background lembut: `#FFF2EB`
- Teks: `#2C2C2C` (utama), `#6B6B6B` (sekunder)

## Struktur Singkat (`index.html`)
- `<style>`: seluruh CSS (root variables, layout, glass effects, responsive).
- `<body>`:
  - Layer efek: `.bg-particles`, `.bg-aurora`
  - Hero dengan `hero-card` (teks + gambar)
  - Stats, Layanan, Keunggulan, Proses, Testimoni, FAQ, CTA, Footer
- `<script>`: particles, navbar scroll, smooth scroll, FAQ toggle, intersection observer untuk fade-in.

## Cara Pakai
1) Buka `index.html` langsung di browser atau host di static server.
2) Pastikan gambar `pexels-zachtheshoota-1838640.jpg` berada satu folder dengan `index.html`.
3) Ubah konten teks sesuai kebutuhan brand/layanan.

## Kustomisasi Cepat
- Warna: atur di `:root` (var `--color-1..4`, `--text-primary/secondary`).
- Radius & spacing: `--radius`, `--spacing-*`.
- Intensitas glass: `--glass-bg`, `--glass-border`, `--glass-strong`.
- Ganti hero image: edit `src` pada `.hero-image`.
- Nonaktifkan efek partikel: hapus inisialisasi `createParticles()` di `<script>`.

## Kredit
- Font: Plus Jakarta Sans (Google Fonts).
- Gambar: `pexels-zachtheshoota-1838640.jpg` (sertakan atribusi sesuai lisensi).

## Deploy Cepat
- GitHub Pages / Vercel / Netlify: cukup unggah `index.html` dan file gambar.
- Tidak ada dependency build; murni HTML/CSS/JS.

