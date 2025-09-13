# 🌄 **Panduan Penyetingan Website ASC Adventure**

> 📖 **Dokumen resmi panduan setup website**  
> Ikuti langkah-langkah berikut untuk menyiapkan website Anda hanya dalam beberapa menit 🚀  

---

## 🗂️ **1. Persiapan Awal**
Sebelum mulai, siapkan:
- ✅ **Nomor WhatsApp** (format internasional: `6281234567890`)  
- ✅ **Logo perusahaan** (PNG/JPG)  
- ✅ **Alamat email** bisnis  
- ✅ **Foto-foto kegiatan** untuk galeri  
- ✅ **Daftar paket pendakian / layanan** (harga, lama perjalanan, itinerary)  

---

## 🏢 **2. Ubah Data Perusahaan**
> Semua konfigurasi utama ada di file **`index.html`**

```js
window.ASC = {
  WHATSAPP_NUMBER: '6281234567890',
  COMPANY_NAME: 'ASC Adventure',
  EMAIL: 'hello@asc-adventure.example.com',
  ADDRESS: 'Jl. Pendaki No.1, Bandung, Indonesia',
  LOGO_URL: 'https://.../logo.png'
};

---

## 🎒 3. Tambah & Edit Paket Pendakian

Semua paket ditulis dalam daftar PACKAGES

{
  id: 'p-rinjani-3d',
  title_en: 'Rinjani Summit 3D/2N',
  price: 'IDR 2.500.000',
  days: '3 days / 2 nights',
  difficulty: 'Moderate - Challenging',
  features: ['Guide & porter', 'Tents & meals', 'Permits & transfers'],
  img: 'https://link-foto.jpg',
  itinerary: 'Day1: Trek to basecamp... Day2: Summit attempt... Day3: Return.'
}


🔑 Bagian yang bisa diubah:

title_en → Judul paket

price → Harga paket

days → Lama perjalanan

difficulty → Tingkat kesulitan

features → List fasilitas

img → Link foto paket

itinerary → Jadwal perjalanan

✨ Untuk menambah paket baru → copy-paste blok di atas lalu sesuaikan.

---

## 📝 4. Ubah Konten Teks Statis

📍 Lokasi teks di file index.html:

Tentang Kami → <section id="about">

Kenapa Pilih Kami? → di dalam #about

Safety & Process → <section id="safety">

Testimoni → <blockquote>

---

##🖼️ 5. Atur Galeri Foto

📍 Cari bagian <section id="gallery">
Format foto:

<figure data-img="URL_gambar_besar" data-caption="Judul Foto">
  <img src="URL_gambar_kecil" class="w-full h-40 object-cover">
</figure>


URL_gambar_besar → Foto ukuran besar

URL_gambar_kecil → Thumbnail foto kecil

data-caption → Judul / keterangan foto

---

## 📲 6. Booking via WhatsApp

Form booking sudah otomatis:

Isi nama, nomor WA, paket, tanggal

Klik Kirim via WhatsApp

Chat otomatis terbuka ke WA Anda 📩

⚠️ Pastikan WHATSAPP_NUMBER sudah benar.
🔗 Ada juga tombol Download Request → menyimpan detail booking .txt

---

## 📥 7. Download Itinerary

Tiap paket → tombol Download Itinerary

Menu atas → tombol Download All Itineraries
📂 Semua file dalam format .txt

---


## 🔍 8. Cek Website di Komputer

Klik kanan index.html → Open with Browser

Atau drag-drop ke browser (Chrome/Firefox/Edge)
✨ Website langsung tampil tanpa server tambahan

---

## 🌐 9. Publish Online (Opsional)

Pilihan hosting:

Gratis → GitHub Pages, Netlify, Vercel

Berbayar → cPanel (Niagahoster, Rumahweb, Hostinger, dll)

📤 Upload file index.html + logo/gambar untuk online

---

## 🗒️ 10. Ringkasan Cepat

 Ubah data perusahaan → di window.ASC

 Tambah/Edit paket → di PACKAGES

 Edit teks statis → langsung di HTML

 Tambahkan foto → di #gallery

 Simpan & cek di browser

 Upload ke hosting (opsional)

 ---

## ✨ Penutup

🎉 Website siap digunakan!
Klien dapat melihat paket, galeri, dan booking langsung via WhatsApp.

---

## 💡 Tips profesional:

Gunakan foto asli kegiatan

Pasang logo resmi

Tambahkan testimoni pelanggan

🌍 Selamat berkarya & sukses untuk bisnis petualangan Anda!