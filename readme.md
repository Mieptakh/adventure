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
