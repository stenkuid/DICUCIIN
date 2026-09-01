# PRD — Website #3: DiCuciin

### Website Jasa Laundry & Perawatan Pakaian

**Platform:** Astro + Cloudflare  
**Project Type:** Local Service Business Website  
**Status:** PRD v1.0  

---

# 1. Product Overview

**DiCuciin** adalah bisnis jasa laundry yang membantu pelanggan mencuci dan merawat pakaian dengan layanan yang praktis, mudah, dan dapat diandalkan.

Website DiCuciin berfungsi sebagai:

* Digital storefront.
* Media informasi layanan.
* Media edukasi pelanggan.
* Kanal untuk mendapatkan order.
* Media pengenalan brand lokal.
* Landing page untuk Local SEO.

Fokus utama website adalah membuat pelanggan berpikir:

> **"Daripada ribet nyuci sendiri, mending DiCuciin."**

Website harus terasa **bersih, segar, praktis, dan friendly**.

---

# 2. Business Goal

## Primary Goal

Mendapatkan pelanggan laundry baru melalui website.

## Secondary Goals

* Meningkatkan awareness DiCuciin.
* Menjelaskan layanan laundry secara mudah.
* Membuat harga/estimasi layanan mudah ditemukan.
* Mendorong pelanggan menghubungi WhatsApp.
* Menampilkan lokasi outlet.
* Membangun trust terhadap kualitas laundry.
* Mendukung pencarian Google untuk laundry lokal.

---

# 3. Target Customer

## Primary Audience

Usia ±18–45 tahun:

* Mahasiswa.
* Anak kos.
* Pekerja kantoran.
* Pasangan muda.
* Keluarga kecil.
* Orang dengan aktivitas padat.

## Customer Problem

Pelanggan tidak selalu malas mencuci.

Masalah utamanya:

* Tidak punya waktu.
* Tidak ingin mencuci dan menjemur sendiri.
* Tidak punya mesin cuci.
* Tidak ingin repot menyetrika.
* Membutuhkan pakaian siap digunakan.
* Membutuhkan layanan yang praktis.

Website harus menjual **convenience**, bukan hanya jasa mencuci.

---

# 4. Brand Positioning

### Positioning Statement

> **DiCuciin — urusan cucian, biar kami yang kerjakan.**

Brand harus terasa:

* Friendly.
* Clean.
* Simple.
* Reliable.
* Helpful.
* Local.
* Modern.

Jangan membuat DiCuciin terlihat seperti perusahaan laundry industri besar.

---

# 5. Brand Personality

Nama **DiCuciin** harus menjadi bagian dari komunikasi brand.

Tone:

> Santai, ringan, dan dekat dengan bahasa sehari-hari.

Contoh komunikasi:

> **Cucian numpuk? DiCuciin aja.**

> **Kamu kerja. Kami yang nyuci.**

> **Biar waktumu dipakai buat hal yang lebih penting.**

Hindari copy yang terlalu formal seperti:

> "Kami menyediakan jasa pencucian pakaian dengan standar operasional profesional."

---

# 6. Unique Selling Proposition

USP utama:

### Practical

Pelanggan tidak perlu mengurus cucian sendiri.

### Clean

Fokus pada hasil pakaian yang bersih dan nyaman digunakan.

### Convenient

Proses order harus sederhana.

### Reliable

Pelanggan harus merasa aman menyerahkan pakaian kepada DiCuciin.

### Local

Dekat dengan pelanggan dan mudah dihubungi.

---

# 7. Website Objective

Dalam beberapa detik pengguna harus mengetahui:

1. DiCuciin adalah laundry.
2. Layanan apa yang tersedia.
3. Berapa estimasi harga.
4. Bagaimana cara order.
5. Di mana lokasinya.

CTA utama harus selalu mengarah pada:

**Order via WhatsApp**

atau channel order resmi bisnis.

---

# 8. Architecture Decision

## Recommended

**Astro Static + Cloudflare Pages**

Tidak menggunakan database untuk versi pertama.

Alasan:

* Informasi layanan bersifat statis.
* Harga dapat disimpan sebagai data lokal.
* Tidak membutuhkan login.
* Tidak membutuhkan dashboard.
* Order dapat diarahkan ke WhatsApp.
* Maintenance sangat rendah.

---

# 9. Technology Stack

* Astro.
* TypeScript.
* Native CSS.
* Minimal JavaScript.
* Cloudflare Pages.

Optional:

* Cloudflare Web Analytics.
* Cloudflare Turnstile jika contact form diperlukan.
* Cloudflare Workers hanya jika fitur backend muncul.

Tidak menggunakan:

* CMS besar.
* E-commerce framework.
* Heavy UI library.
* State management.
* Booking platform custom.

---

# 10. Sitemap

```text
/
├── /services
├── /pricing
├── /how-it-works
├── /about
├── /location
├── /contact
├── /faq
├── /robots.txt
└── /sitemap-index.xml
```

Jika konten masih sederhana, seluruh section dapat tetap berada pada homepage.

---

# 11. Homepage Structure

Urutan utama:

1. Navbar.
2. Hero.
3. Quick Service Selector.
4. Services.
5. Pricing.
6. Why DiCuciin.
7. How It Works.
8. Laundry Quality / Process.
9. Testimonial.
10. Location.
11. FAQ.
12. Final CTA.
13. Footer.

---

# 12. Navbar

### Logo

**DiCuciin**

Navigation:

* Home.
* Services.
* Pricing.
* How It Works.
* Location.

CTA:

**Cuciin Sekarang**

Mobile:

* Logo.
* Menu button.
* CTA order.

Navbar sticky dapat digunakan, tetapi tidak boleh mengambil terlalu banyak tinggi layar.

---

# 13. Hero Section

Hero harus langsung menyampaikan problem dan solusi.

### Headline

> **Cucian Numpuk? DiCuciin Aja.**

Supporting copy:

> Serahkan pakaian kotormu kepada kami dan gunakan waktumu untuk hal yang lebih penting.

CTA utama:

**Order Sekarang**

CTA kedua:

**Lihat Harga**

### Visual

Gunakan visual:

* Tumpukan pakaian bersih.
* Laundry basket.
* Pakaian yang baru dilipat.
* Mesin cuci sebagai supporting visual.

Visual harus memberikan kesan:

**fresh + clean + organized.**

---

# 14. Hero Design

Hero tidak boleh terlihat seperti website jasa laundry generik.

Konsep:

**Fresh Laundry × Friendly Local Brand**

Gunakan whitespace yang cukup.

Visual dapat berupa:

* Foto pakaian bersih.
* Circular graphic.
* Soft shapes.
* Minimal decorative elements.

Tidak menggunakan:

* Washing-machine 3D animation.
* Bubble animation berlebihan.
* Heavy video background.
* Excessive gradient.

---

# 15. Suggested Color Palette

### Fresh Blue

`#2F80ED`

### Aqua

`#56CCF2`

### Soft Cream

`#FFFDF7`

### Deep Navy

`#16324F`

### Fresh Green

`#6FCF97`

### White

`#FFFFFF`

Blue menjadi primary brand color.

Aqua memberikan asosiasi:

* Air.
* Kebersihan.
* Kesegaran.

Green digunakan sebagai success/accent color.

---

# 16. Typography

Heading:

* Bold.
* Rounded atau friendly.
* High impact.

Body:

* Clean sans-serif.
* Sangat readable.

Maksimal dua font family.

Heading harus memiliki personality tetapi tetap profesional.

---

# 17. Quick Service Selector

Setelah hero, tampilkan pilihan layanan.

Headline:

> **Butuh Dicuciin Apa?**

Cards:

### Cuci Kering

Untuk pakaian sehari-hari.

### Cuci + Setrika

Pakaian selesai dan siap digunakan.

### Setrika

Untuk pakaian yang sudah dicuci.

### Express

Untuk kebutuhan lebih cepat jika layanan tersedia.

CTA:

**Lihat Semua Layanan**

Layanan final harus mengikuti layanan aktual DiCuciin.

---

# 18. Services Section

Headline:

> **Laundry Tanpa Ribet**

Setiap service card:

* Icon/image.
* Service name.
* Short description.
* Estimasi pengerjaan.
* Price/starting price.
* CTA.

Contoh:

### Regular Laundry

Pakaian dicuci dan dikeringkan untuk penggunaan sehari-hari.

### Wash & Iron

Pakaian dicuci, dikeringkan, kemudian disetrika.

### Ironing

Pakaian dirapikan dan disetrika.

### Express Laundry

Layanan dengan pengerjaan lebih cepat apabila tersedia.

Jangan menjanjikan waktu pengerjaan yang belum ditetapkan bisnis.

---

# 19. Pricing Section

Pricing harus mudah dipindai.

Headline:

> **Simple Pricing. No Guessing.**

Contoh tabel:

| Service        | Starting From |
| -------------- | ------------: |
| Cuci Kering    |  Rp XX.XXX/kg |
| Cuci + Setrika |  Rp XX.XXX/kg |
| Setrika        |  Rp XX.XXX/kg |
| Express        |  Rp XX.XXX/kg |

Harga adalah placeholder sampai harga resmi tersedia.

Jika pricing dapat berubah, gunakan:

> **Mulai dari Rp XX.XXX/kg**

Tambahkan note:

> Harga dan ketentuan dapat berubah sesuai jenis layanan dan kebijakan outlet.

---

# 20. Price Transparency

Jangan menyembunyikan harga jika bisnis memang menyediakan pricing publik.

Tujuannya:

* Mengurangi hesitation.
* Meningkatkan trust.
* Mengurangi pertanyaan repetitif melalui WhatsApp.

Namun jika harga sangat bergantung pada jenis pakaian, tampilkan:

**"Cek Harga"**

daripada mengarang harga.

---

# 21. Why DiCuciin

Headline:

> **Kenapa Harus DiCuciin?**

Gunakan 4 benefit.

### Hemat Waktu

Tidak perlu menghabiskan waktu mencuci dan menyetrika.

### Bersih & Rapi

Pakaian diprosos untuk siap digunakan kembali.

### Praktis

Order dan komunikasi dibuat sederhana.

### Mudah Dihubungi

Pelanggan dapat langsung menghubungi outlet.

---

# 22. Trust Section

Laundry membutuhkan trust tinggi karena pelanggan menyerahkan barang pribadi.

Tampilkan:

### Careful Handling

Pakaian diprosos dengan perhatian.

### Clear Process

Pelanggan mengetahui bagaimana layanan berjalan.

### Transparent Pricing

Harga dijelaskan dengan jelas.

### Customer Support

Ada channel untuk bertanya jika terjadi masalah.

Jangan menggunakan klaim:

* "100% tanpa risiko."
* "Tidak pernah kehilangan pakaian."
* "Paling terbaik di kota."

kecuali dapat dibuktikan.

---

# 23. How It Works

Section:

> **3 Langkah, Beres.**

### Step 1 — Order

Hubungi DiCuciin melalui WhatsApp atau channel resmi.

### Step 2 — Serahkan Cucian

Bawa pakaian ke outlet atau gunakan pickup apabila layanan tersedia.

### Step 3 — Ambil

Pakaian selesai diprosos dan siap digunakan.

Jika pickup/delivery belum tersedia, jangan menampilkannya sebagai fitur aktif.

---

# 24. Laundry Process

Visual storytelling:

**Receive → Sort → Wash → Dry → Iron → Ready**

Setiap tahap dijelaskan singkat.

### Receive

Pakaian diterima dan dicatat.

### Sort

Pakaian dipisahkan sesuai proses.

### Wash

Pakaian dicuci menggunakan proses yang sesuai.

### Dry

Pakaian dikeringkan.

### Iron

Jika termasuk layanan, pakaian disetrika.

### Ready

Pakaian siap dikembalikan.

Process section bertujuan membangun trust.

---

# 25. Laundry Care

Section edukasi ringan:

> **Setiap Pakaian Punya Cerita.**

Jelaskan bahwa beberapa pakaian membutuhkan penanganan berbeda.

Contoh:

* Delicate clothing.
* White clothing.
* Dark clothing.
* Special material.

Jangan mengklaim kemampuan menangani material tertentu sebelum layanan tersebut benar-benar tersedia.

---

# 26. Testimonial

Gunakan customer testimonials jika tersedia.

Format:

> “Cucian jadi nggak numpuk lagi. Tinggal antar, nanti tinggal ambil.”

**— Customer DiCuciin**

Gunakan testimonial asli setelah tersedia.

Untuk development, gunakan placeholder.

Jangan membuat review palsu lalu memasukkannya sebagai testimonial nyata.

---

# 27. Location Section

Headline:

> **Temukan DiCuciin Terdekat**

Informasi:

* Address.
* Opening hours.
* Phone.
* WhatsApp.
* Google Maps.

CTA:

**Get Directions**

Jika hanya memiliki satu outlet, fokus pada satu lokasi.

Jika nantinya memiliki beberapa outlet, struktur dapat berkembang menjadi location directory.

---

# 28. Contact / Order CTA

Section utama sebelum footer.

### Headline

> **Nggak Sempat Nyuci?**

Supporting copy:

> Kirim cucianmu ke DiCuciin dan biarkan kami yang mengurus sisanya.

CTA:

**Cuciin Sekarang**

Secondary:

**Tanya Dulu**

Primary CTA mengarah ke WhatsApp resmi.

---

# 29. WhatsApp Order Flow

Untuk versi awal tidak perlu membuat shopping cart.

Ketika user menekan:

**Cuciin Sekarang**

WhatsApp dapat dibuka dengan pre-filled message.

Contoh:

> Halo DiCuciin, saya ingin bertanya mengenai layanan laundry.

Untuk order lebih spesifik:

> Halo DiCuciin, saya ingin laundry. Bisa info harga dan prosesnya?

Nomor WhatsApp harus dimasukkan hanya setelah nomor resmi tersedia.

---

# 30. FAQ

Pertanyaan minimum:

### Berapa harga laundry?

Arahkan ke pricing.

### Berapa lama proses laundry?

Jawaban berdasarkan SLA aktual.

### Apakah menerima pakaian tertentu?

Jelaskan jenis pakaian yang diterima.

### Apakah tersedia express?

Jawab berdasarkan layanan aktual.

### Apakah tersedia pickup/delivery?

Hanya tampilkan jika tersedia.

### Bagaimana jika pakaian saya rusak/hilang?

Tampilkan kebijakan resmi bisnis.

### Bagaimana cara order?

Arahkan ke WhatsApp atau outlet.

FAQ dapat menggunakan native `<details>` agar JavaScript tidak diperlukan.

---

# 31. Policies

Karena laundry menangani barang pelanggan, website sebaiknya memiliki informasi kebijakan.

Minimal:

* Service policy.
* Claim policy.
* Operating policy.

Jika bisnis memiliki aturan:

* Batas waktu klaim.
* Pakaian yang tidak diterima.
* Risiko material tertentu.
* Ketentuan pencucian.

Tampilkan secara jelas dan tidak menggunakan bahasa hukum yang terlalu rumit.

---

# 32. About Section

Headline:

> **We Handle The Laundry. You Handle Life.**

Copy:

> DiCuciin hadir untuk membantu orang-orang yang ingin menghemat waktu dari urusan cucian. Kami membuat proses laundry lebih sederhana, mudah dipahami, dan nyaman untuk pelanggan sehari-hari.

Copy final dapat disesuaikan dengan sejarah bisnis sebenarnya.

---

# 33. Local SEO

Primary keyword:

* laundry [kota].
* jasa laundry [kota].
* laundry kiloan [kota].
* laundry dekat saya.
* cuci pakaian [kota].
* laundry murah [kota].
* laundry express [kota] jika layanan tersedia.

Location harus menggunakan lokasi bisnis aktual.

---

# 34. Metadata

Homepage title:

**DiCuciin — Laundry Praktis & Bersih**

Local version:

**DiCuciin — Laundry [City]**

Meta description:

> Cucian numpuk? DiCuciin aja. Temukan layanan laundry, harga, lokasi, dan cara order dengan mudah.

---

# 35. Structured Data

Gunakan:

**LocalBusiness**

Jika layanan utama memang laundry, schema dapat menggunakan kategori bisnis yang paling relevan dan valid.

Properties:

* name.
* description.
* address.
* telephone.
* openingHours.
* image.
* url.
* priceRange.

Jangan menambahkan informasi yang tidak tersedia.

---

# 36. Open Graph

Implement:

* `og:title`
* `og:description`
* `og:image`
* `og:type`
* `og:url`

Social preview menggunakan foto pakaian bersih atau laundry environment yang menarik.

---

# 37. Image Strategy

Prioritas visual:

1. Clean folded clothes.
2. Laundry process.
3. Staff/service.
4. Laundry equipment.
5. Storefront.
6. Customer experience.

Image requirements:

* AVIF/WebP.
* Responsive sizes.
* Explicit dimensions.
* Lazy-load non-critical images.
* Hero image prioritized.

Avoid generic stock imagery apabila foto bisnis asli tersedia.

---

# 38. Mobile UX

Laundry customers kemungkinan besar datang dari smartphone.

Prioritas:

* CTA WhatsApp mudah ditemukan.
* Pricing mudah dibaca.
* Address mudah diakses.
* Button besar.
* Service cards tidak terlalu padat.
* No horizontal scrolling.

Optional:

**Sticky bottom mobile CTA**

Contoh:

**💬 Order via WhatsApp**

Jika digunakan, pastikan tidak menutupi konten.

---

# 39. Responsive Design

### Mobile

`<768px`

### Tablet

`768px–1023px`

### Desktop

`≥1024px`

Gunakan responsive CSS sederhana.

---

# 40. Animation

Allowed:

* Button hover.
* Card hover.
* Subtle image reveal.
* Navigation transition.

Avoid:

* Animated water bubbles.
* Constant moving clothes.
* Parallax.
* Video backgrounds.
* Excessive scroll effects.

---

# 41. Accessibility

Requirements:

* Semantic HTML.
* Correct heading hierarchy.
* Keyboard navigation.
* Visible focus state.
* Proper contrast.
* Accessible mobile menu.
* Descriptive alt text.
* Buttons with clear labels.

CTA seperti:

**"Klik di sini"**

harus dihindari.

Gunakan:

**"Order via WhatsApp"**

---

# 42. Performance Requirements

Target:

**Lighthouse Performance ≥90**

**SEO ≥95**

**Accessibility ≥90**

Core Web Vitals:

* LCP ≤2.5s.
* CLS ≤0.1.
* INP ≤200ms.

JavaScript harus minimal.

---

# 43. Cloudflare Requirements

Deployment:

**Cloudflare Pages**

Architecture:

```text
Astro
  ↓
Static Build
  ↓
dist/
  ↓
Cloudflare Pages
```

Tidak membutuhkan Worker runtime untuk website versi pertama.

---

# 44. Bundle Policy

Harus:

* Menggunakan static generation.
* Menghindari dependency besar.
* Menghindari UI framework jika tidak diperlukan.
* Menghindari animation library.
* Menghindari unnecessary client components.
* Menghapus dependency yang tidak digunakan.

Jika suatu saat Worker digunakan, bundle server-side harus dianalisis sebelum deployment dan dijaga di bawah batas compressed bundle yang berlaku.

---

# 45. Recommended Project Structure

```text
src/
├── components/
│   ├── Navbar.astro
│   ├── Button.astro
│   ├── ServiceCard.astro
│   ├── PriceTable.astro
│   ├── StepCard.astro
│   ├── FAQItem.astro
│   └── Footer.astro
│
├── sections/
│   ├── Hero.astro
│   ├── ServiceSelector.astro
│   ├── Services.astro
│   ├── Pricing.astro
│   ├── WhyDiCuciin.astro
│   ├── HowItWorks.astro
│   ├── LaundryProcess.astro
│   ├── CareSection.astro
│   ├── Testimonials.astro
│   ├── Location.astro
│   ├── FAQ.astro
│   └── FinalCTA.astro
│
├── layouts/
│   └── BaseLayout.astro
│
├── pages/
│   ├── index.astro
│   ├── services.astro
│   ├── pricing.astro
│   ├── how-it-works.astro
│   ├── about.astro
│   ├── location.astro
│   ├── contact.astro
│   ├── faq.astro
│   ├── robots.txt.ts
│   └── sitemap-index.xml.ts
│
├── data/
│   ├── business.ts
│   ├── services.ts
│   ├── pricing.ts
│   └── faq.ts
│
├── styles/
│   └── global.css
│
└── assets/
```

---

# 46. Data Architecture

Business content harus dipisahkan dari UI.

### Service

```text
service
├── slug
├── name
├── description
├── price
├── unit
├── turnaround
├── features
└── available
```

### Business

```text
business
├── name
├── address
├── phone
├── whatsapp
├── email
├── openingHours
├── mapsUrl
└── socialLinks
```

Tujuannya agar informasi bisnis dapat diubah tanpa mengubah component.

---

# 47. Analytics

Gunakan:

**Cloudflare Web Analytics**

Track:

* Page views.
* Service clicks.
* Pricing interactions.
* WhatsApp clicks.
* Directions clicks.

Events:

```text
click_service
click_pricing
click_whatsapp
click_direction
```

Tidak memasang banyak analytics provider.

---

# 48. Security

Website static memiliki attack surface kecil.

Jika contact form ditambahkan:

* Input validation.
* Rate limiting.
* Spam protection.
* Cloudflare Turnstile jika diperlukan.
* Jangan menyimpan data pelanggan tanpa kebutuhan.

Tidak menggunakan database pada Phase 1.

---

# 49. Out of Scope

Tidak termasuk:

* Customer login.
* Customer dashboard.
* Laundry order tracking.
* Online payment.
* Automated pickup routing.
* Inventory management.
* Staff dashboard.
* Admin CMS.
* Loyalty system.
* Database.
* Native mobile app.

---

# 50. Future Expansion

## Phase 2

* Pickup & delivery request.
* Online order form.
* Automated WhatsApp order.
* Promo system.
* Multiple outlet support.

## Phase 3

Jika volume bisnis membutuhkan:

* Cloudflare Workers.
* D1.
* R2.
* Admin dashboard.
* Order tracking.

Architecture Phase 1 harus tetap sederhana agar ekspansi nantinya tidak membutuhkan rebuild total.

---

# 51. Acceptance Criteria

## Brand

* [ ] Nama DiCuciin mudah diingat.
* [ ] Tone friendly dan casual.
* [ ] Visual terasa clean.
* [ ] Tidak terlihat seperti template laundry generik.

## Conversion

* [ ] CTA Order terlihat di hero.
* [ ] CTA WhatsApp tersedia.
* [ ] Pricing mudah ditemukan.
* [ ] Location mudah ditemukan.
* [ ] Cara order mudah dipahami.

## Services

* [ ] Semua layanan aktif ditampilkan.
* [ ] Harga dapat ditemukan.
* [ ] Estimasi pengerjaan dapat ditemukan jika tersedia.
* [ ] Tidak ada klaim layanan yang belum tersedia.

## SEO

* [ ] LocalBusiness schema.
* [ ] Metadata.
* [ ] Canonical.
* [ ] Sitemap.
* [ ] Robots.
* [ ] Open Graph.
* [ ] Location keywords.

## Technical

* [ ] Astro static build berhasil.
* [ ] Cloudflare Pages compatible.
* [ ] Minimal JavaScript.
* [ ] No unnecessary dependencies.
* [ ] Images optimized.
* [ ] No broken links.
* [ ] No console errors.

## Performance

* [ ] Lighthouse Performance ≥90.
* [ ] SEO ≥95.
* [ ] Accessibility ≥90.
* [ ] Core Web Vitals optimized.

---

# 52. Implementation Blueprint

## Website Goal

Membangun website laundry lokal yang membuat pelanggan merasa:

> **"Laundry jadi gampang. Tinggal DiCuciin."**

## Architecture

**Astro Static + Cloudflare Pages**

## Sitemap

```text
/
├── /services
├── /pricing
├── /how-it-works
├── /about
├── /location
├── /contact
├── /faq
├── /robots.txt
└── /sitemap-index.xml
```

## Design Direction

**Fresh Laundry × Friendly Local Brand**

Karakter:

* Clean.
* Fresh.
* Casual.
* Friendly.
* Trustworthy.
* Practical.

## Core Components

* Navbar.
* Hero.
* Service Card.
* Pricing Table.
* Why DiCuciin.
* Process.
* FAQ.
* Location.
* WhatsApp CTA.
* Footer.

## Technical Requirements

* Astro static generation.
* TypeScript.
* Native CSS.
* Minimal JavaScript.
* Data-driven services.
* Local SEO.
* LocalBusiness schema.
* Sitemap.
* Robots.
* Open Graph.
* Optimized images.
* Cloudflare Pages compatibility.

---

# 53. Antigravity Execution Plan

## Prompt 1 — Analysis

Antigravity harus:

* Membaca PRD DiCuciin.
* Menentukan architecture Astro.
* Menentukan component hierarchy.
* Menentukan service/pricing data structure.
* Menentukan SEO structure.
* Menentukan conversion flow.
* Menentukan image strategy.
* Membuat implementation checklist.

Tidak boleh menambahkan fitur baru.

---

## Prompt 2 — Build

Instruksi:

> You are a senior full-stack engineer. Build the DiCuciin local laundry website according to the provided PRD. Use Astro static generation, reusable components, data-driven service and pricing content, minimal client-side JavaScript, optimized responsive images, and Cloudflare Pages compatibility. The experience must feel clean, friendly, practical, and conversion-focused. Do not invent services, prices, policies, locations, or features that are not provided.

Implement:

* Homepage.
* Services.
* Pricing.
* How It Works.
* About.
* Location.
* FAQ.
* Contact CTA.
* WhatsApp CTA.
* Local SEO.
* Structured data.
* Responsive UI.

---

## Prompt 3 — Optimization

Antigravity harus memeriksa:

### Build

* Production build.
* Type checking.
* Broken links.
* Console errors.

### Performance

* Image optimization.
* JavaScript reduction.
* CSS optimization.
* Bundle analysis.
* Core Web Vitals.

### SEO

* Metadata.
* Canonical.
* LocalBusiness schema.
* Sitemap.
* Robots.
* Open Graph.

### Conversion

* Hero CTA.
* WhatsApp CTA.
* Pricing visibility.
* Location CTA.
* Mobile sticky CTA jika digunakan.

### Cloudflare

* Static output.
* Pages compatibility.
* Dependency audit.
* No unnecessary Worker runtime.
* Deployment readiness.

Output akhir:

**Deployment-ready Astro project.**

---

# 54. Final Product Definition

DiCuciin v1 adalah website jasa laundry lokal yang mengubah persepsi laundry dari sekadar:

**"tempat mencuci pakaian"**

menjadi:

**"cara paling praktis untuk menghilangkan urusan cucian dari hidup pelanggan."**

Customer journey:

**Problem → Solution → Service → Price → Trust → Location → Order**

Prioritas:

**Convenience > Trust > Pricing > CTA > Local SEO > Performance**

**Database:** Tidak diperlukan.

**Backend:** Tidak diperlukan.

**Framework:** Astro.

**Hosting:** Cloudflare Pages.

**Primary CTA:** Order via WhatsApp.

**Core Message:**
**"Cucian numpuk? DiCuciin aja."**

---

# AI DEVELOPMENT & DESIGN CONTROL PROTOCOL

## Project Protocol

This document defines the mandatory operating rules for all AI agents working on this project.

All instructions in this file must be read and followed before modifying any project file.

The primary purpose of this protocol is to preserve approved design states, prevent unintended redesigns, control AI modifications, and provide a predictable command system for development.

---

# 1. CORE PRINCIPLE

The AI agent must treat the existing approved project state as valuable and protected.

The AI must NEVER assume that an existing implementation should be improved, modernized, refactored, redesigned, simplified, or replaced unless the user explicitly requests it.

When the user's request is narrow, the modification must remain narrow.

The AI must preserve:

- Existing approved layouts
- Existing visual hierarchy
- Existing typography
- Existing spacing
- Existing colors
- Existing images
- Existing responsive behavior
- Existing interactions
- Existing functionality

unless explicitly instructed otherwise.

---

# 2. PROTOCOL PRIORITY

When interpreting instructions, use the following priority order:

1. Explicit user instruction
2. Active protocol command
3. Locked component rules
4. Approved checkpoint rules
5. Existing project implementation
6. General design or coding preferences

The AI must not override a higher-priority instruction with a lower-priority assumption.

---

# 3. BEFORE EVERY MODIFICATION

Before modifying any file, the AI must:

1. Read this `PROTOCOL.md`.
2. Identify the active protocol command.
3. Identify the exact component or files that need modification.
4. Check whether the target component is locked.
5. Preserve all unrelated components.
6. Avoid modifying files that are outside the requested scope.

The AI must NOT begin a broad redesign simply because a requested change affects part of the page.

---

# 4. MINIMAL CHANGE PRINCIPLE

The AI must make the smallest reasonable modification necessary to fulfill the user's request.

The AI must NOT:

- Rewrite unrelated components.
- Refactor unrelated code.
- Change the design system.
- Replace existing layouts without permission.
- Change typography without permission.
- Change spacing without permission.
- Replace images without permission.
- Change colors without permission.
- Modify responsive behavior outside the requested scope.
- Remove functionality unless explicitly requested.

If a requested modification can be completed by changing one component, the AI must not rewrite the entire page.

---

# 5. DESIGN PRESERVATION RULE

Existing design is considered protected by default.

The AI must NOT interpret requests such as:

- "Improve this"
- "Make this better"
- "Fix this"
- "Add this feature"

as permission to redesign unrelated sections.

If the request does not explicitly request redesign, preserve the existing visual appearance.

---

# 6. EXACT RESTORATION RULE

When restoring a previous state, the AI must restore the exact known implementation.

The AI must NOT:

- Recreate the design from memory.
- Generate a similar design.
- Approximate the previous layout.
- Improve the previous version.
- Modernize the previous version.
- Combine the previous design with the current design.

Restoration means restoring the previous code state as accurately as possible.

The AI must always prefer:

1. Git history
2. Git commit
3. Git diff
4. Existing backup
5. Explicit checkpoint reference

The AI must never guess the previous implementation if an exact source is available.

---

# 7. PROTOCOL COMMAND SYSTEM

Commands beginning with `/` are protocol commands.

Protocol commands must be interpreted according to this document.

The AI must execute the command according to its definition.

The AI must not reinterpret the meaning of a protocol command.

---

# 8. /REVERSE

## Purpose

Undo the latest unapproved modification.

## Execution Rules

When `/REVERSE` is activated:

1. Identify the latest modification made for the current task.
2. Identify all files affected by that modification.
3. Restore those files to their exact state before that modification.
4. Preserve all older approved changes.
5. Do not redesign anything.
6. Do not generate an alternative implementation.
7. Do not improve the restored version.
8. Do not modify unrelated files.

The AI must treat `/REVERSE` as:

"Restore the exact previous state."

The AI must NOT interpret `/REVERSE` as:

"Create something similar to the previous design."

After restoration, stop modifying the project unless the user provides another instruction.

---

# 9. /CHECKPOINT [NAME]

## Purpose

Create a named approved state.

Example:

`/CHECKPOINT homepage-v1`

When activated:

1. Identify the current project state.
2. Record the checkpoint name.
3. Record the relevant files associated with the checkpoint.
4. Record the purpose of the checkpoint.
5. Treat this state as an approved reference.

A checkpoint should preferably correspond to a Git commit whenever possible.

---

# 10. /RESTORE [NAME]

## Purpose

Restore a previously approved checkpoint.

Example:

`/RESTORE homepage-v1`

When activated:

1. Locate the exact checkpoint.
2. Identify its associated files or Git commit.
3. Restore the exact code state.
4. Do not reinterpret the design.
5. Do not merge the checkpoint with experimental changes unless explicitly requested.

The checkpoint is the source of truth.

---

# 11. /LOCK [COMPONENT]

## Purpose

Protect an approved component from modification.

Example:

`/LOCK HERO`

When a component is locked, the AI must NOT modify:

- Layout
- HTML structure
- CSS styling
- Typography
- Spacing
- Colors
- Images
- Animations
- Responsive behavior
- Component logic

unless explicitly instructed.

Example:

`/LOCK HERO`

means the Hero section must remain unchanged.

---

# 12. /UNLOCK [COMPONENT]

## Purpose

Remove protection from a previously locked component.

Example:

`/UNLOCK HERO`

Only after this command may the AI freely modify the specified component according to the user's instructions.

Unlocking one component does not unlock other components.

---

# 13. /STRICT

## Purpose

Enable strict modification mode.

When `/STRICT` is active:

- Modify only explicitly requested components.
- Modify only files required to complete the request.
- Do not refactor unrelated code.
- Do not redesign unrelated sections.
- Do not optimize unrelated components.
- Do not modify the design system.
- Do not make "helpful" visual changes.
- Preserve all existing behavior unless explicitly instructed otherwise.

The AI must prioritize precision over creativity.

---

# 14. /DESIGN-ONLY

## Purpose

Allow visual modifications while protecting application functionality.

The AI may modify:

- Layout
- Typography
- Spacing
- Colors
- Visual hierarchy
- Animation
- Responsive styling

The AI must NOT modify:

- Business logic
- API integrations
- Routing
- Data structures
- Application logic

unless explicitly requested.

---

# 15. /CODE-ONLY

## Purpose

Modify functionality while preserving the visual design.

When `/CODE-ONLY` is active, the existing visual design must remain unchanged.

The AI must NOT modify:

- Layout
- Typography
- Colors
- Spacing
- Images
- Animation
- Visual hierarchy

unless explicitly requested.

---

# 16. /WA

## Purpose

Activate the WhatsApp Floating Action Button protocol.

When `/WA` is activated:

1. Add a floating WhatsApp contact button.
2. Position it appropriately without obstructing important UI.
3. Use fixed positioning.
4. Ensure responsive behavior.
5. Ensure mobile safe-area compatibility.
6. Ensure the button is touch-friendly.
7. Use the existing design language.
8. Do not redesign the page.
9. Do not modify unrelated sections.
10. Do not change existing layout structure.

The WhatsApp button must be implemented as an isolated component whenever practical.

---

# 17. /REMOVE-WA

Remove the WhatsApp floating button and all directly associated implementation.

Do not modify unrelated components.

---

# 18. /SCOPE [COMPONENT OR FILE]

## Purpose

Restrict all modifications to a specific scope.

Example:

`/SCOPE HERO`

or:

`/SCOPE src/components/Hero.astro`

When active:

The AI may only modify the specified component or file.

Any required modification outside the scope must first be identified and explained.

The AI must not silently modify files outside the active scope.

---

# 19. /FREEZE-DESIGN

## Purpose

Freeze the entire visual design.

When active, the AI may modify functionality but must preserve the exact visual appearance.

The AI must NOT change:

- Layout
- Typography
- Spacing
- Colors
- Images
- Animations
- Component positioning

unless explicitly instructed.

---

# 20. /EXPERIMENT

## Purpose

Allow experimental changes without treating them as approved.

Experimental changes must be considered temporary.

The AI must:

1. Avoid modifying locked components.
2. Avoid modifying unrelated files.
3. Keep changes isolated whenever possible.
4. Clearly identify experimental files.
5. Preserve the ability to reverse the experiment.

Experimental work must not automatically replace an approved checkpoint.

---

# 21. APPROVAL SYSTEM

A modification becomes an approved reference only when the user explicitly approves it.

Examples:

- `APPROVED`
- `/CHECKPOINT homepage-v2`
- "This version is approved."
- "Keep this design."

Until explicit approval is given, major design modifications should be considered experimental.

---

# 22. DO NOT GUESS RULE

If the AI does not know which previous version the user means, the AI must NOT invent or recreate a design.

The AI must:

1. Inspect Git history.
2. Inspect recent changes.
3. Inspect checkpoints.
4. Inspect available project history.

Only if no previous state exists should the AI ask the user for clarification.

The AI must never silently guess.

---

# 23. CHANGE REPORT

After completing a modification, the AI must provide a concise report containing:

### Modified

List modified files.

### Preserved

List important components intentionally left unchanged.

### Protocol

State which protocol commands were active.

### Reversal

Explain how the change can be reversed.

The report should remain concise.

---

# 24. STOP CONDITION

After successfully completing the requested task, the AI must stop.

The AI must NOT continue with:

- Additional redesign
- Optional improvements
- Unrequested refactoring
- Additional feature development
- Visual experimentation

unless explicitly requested.

Completion means completion.

---

# 25. DEFAULT SAFE MODE

If no explicit protocol command is provided, the AI must operate in:

`SAFE MODE`

SAFE MODE rules:

- Preserve existing design.
- Preserve existing functionality.
- Make minimal modifications.
- Do not redesign unrelated components.
- Do not refactor unrelated code.
- Do not replace approved implementation.
- Prefer isolated changes.
- Treat ambiguity as a reason to inspect project history, not as permission to guess.

---

# 26. FINAL OPERATING INSTRUCTION

The AI agent must follow this principle:

"Preserve first. Modify second. Never redesign without permission. Never guess a previous state when an exact state can be restored."

The existing project is the source of truth.

User-approved checkpoints are protected states.

Protocol commands must be followed literally.

Precision is more important than creativity.
