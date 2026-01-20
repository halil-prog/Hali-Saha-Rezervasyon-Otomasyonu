# ⚽ Halı Saha Rezervasyon Sistemi

WordPress tabanlı futbol sahası rezervasyon otomasyonu - *Dokuz Eylül Üniversitesi Bitirme Projesi (2025)*

---

## 🎯 Problem & Çözüm

### ❌ Problem
- Manuel kağıt/defter takibi → Çift rezervasyon hataları
- Sadece telefonla sipariş → 7/24 erişim yok
- Kapora takibi zor → Ödeme kayıpları
- Mevcut hazır çözümler *karmaşık takvim senaryolarını* ve *dinamik fiyatlandırmayı* desteklemiyor

### ✅ Çözüm
Hazır eklentiler yerine *Core PHP ve MySQL ile custom rezervasyon motoru* geliştirdik.

---

## 🔥 Teknik Özellikler

### 1️⃣ Custom Booking Engine (Core PHP)
Hazır WordPress eklentileri multi-saha ve saat bazlı dinamik fiyatlandırmayı desteklemediği için:
- ✅ Sıfırdan rezervasyon algoritması
- ✅ Veritabanı tasarımı (MySQL)
- ✅ Çakışma önleme (double-booking prevention)
- ✅ Boş saat tespiti (real-time availability check)

### 2️⃣ Stripe API Entegrasyonu
- Kapora ödemesi otomasyonu
- Provizyon (authorization) işlemleri
- Güvenli ödeme akışı

### 3️⃣ SMTP Mail Automation
- Rezervasyon onay/iptal bildirimleri
- Otomatik mail tetikleme
- Müşteri ve işletmeci bilgilendirme

### 4️⃣ Admin Panel
- Rezervasyon yönetimi (onayla/reddet)
- Dinamik fiyat güncelleme
- Çalışma saati ayarları

---

## 🛠️ Tech Stack

*Backend:*
- Core PHP (custom rezervasyon motoru)
- MySQL (veritabanı tasarımı)

*Entegrasyonlar:*
- Stripe API (ödeme sistemi)
- SMTP Protocol (mail automation)

*Altyapı:*
- WordPress (CMS framework)
- HTML5, CSS3, JavaScript

---

## 💡 Teknik Zorluklar & Çözümler

### Zorluk 1: Çakışma Önleme
*Problem:* Aynı saat için birden fazla rezervasyon
*Çözüm:* MySQL transaction locks + unique constraints

### Zorluk 2: Dinamik Fiyatlandırma
*Problem:* Hafta içi/hafta sonu farklı ücret
*Çözüm:* Custom pricing engine (tarih/saat bazlı hesaplama)

### Zorluk 3: Real-time Availability
*Problem:* Boş saatleri anlık gösterme
*Çözüm:* AJAX + MySQL query optimization

---

## 📂 Proje Dökümanları

Projenin teknik detaylarını içeren sunum ve poster dosyaları:
* [Proje Posteri (PDF)](https://github.com/halil-prog/Hali-Saha-Rezervasyon-Otomasyonu/blob/main/HALI%20SAHA%20REZEERVASYON%20POSTERI%CC%87.pdf)
* [Proje Web sitesinden ekran görüntüleri (PDF)](https://github.com/halil-prog/Hali-Saha-Rezervasyon-Otomasyonu/blob/main/sunumumuz.pdf)

---

## 📚 Öğrendiklerim

✅ Custom veritabanı tasarımı (normalization, indexing)  
✅ Payment gateway entegrasyonu (Stripe)  
✅ Email automation (SMTP)  
✅ Booking algoritmaları (conflict detection)  
✅ Real-time data synchronization

---

## 👥 Geliştirici Ekibi

*Halil Kanatlı* - Backend Developer (rezervasyon motoru, Stripe API, veritabanı)  
*Göktuğ Özdemir* - Frontend Developer

---

## 🎓 Proje Bağlamı

Dokuz Eylül Üniversitesi | Bilgisayar Programcılığı  
Bitirme Projesi - 2025
