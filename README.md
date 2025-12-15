# ⚽ Halı Saha Rezervasyon ve Yönetim Otomasyonu

**Dokuz Eylül Üniversitesi - Bilgisayar Programcılığı Bitirme Projesi**

Bu proje, halı saha işletmelerinin rezervasyon süreçlerini dijitalleştirmek, manuel hataları ortadan kaldırmak ve müşteri deneyimini artırmak amacıyla geliştirilmiş uçtan uca bir web otomasyonudur.

---

## 🎯 Projenin Amacı ve Çözüm

**🔴 Problem**
Geleneksel halı saha işletmeciliğinde süreçler kağıt/defter üzerinde yürür. Bu durum çift rezervasyon hatalarına, kapora takibinin zorluğuna ve sadece telefonla sipariş alınabilmesine neden olur.

**🟢 Çözüm**
Manuel yürüyen bu süreci, **otomatik ve çevrim içi yönetilebilir** bir hale getirdik. Hem işletme hem de müşteri için zaman, para ve güvenlik tasarrufu sağlayan bir sistem kurduk.

---

## 🔥 Temel Özellikler

### 1. 📩 Otomatik E-Posta Bildirim Sistemi (SMTP)
Sistem, rezervasyon durumlarında tarafları anlık olarak bilgilendirir. "Rezervasyon Onaylandı" veya "İptal Talebi" mailleri, işlem yapıldığı anda otomatik olarak gönderilir.

### 2. 📅 Akıllı Rezervasyon Modülü
Kullanıcı tarih seçtiğinde, sistem veritabanından yalnızca **boş saatleri** çeker. Dolu saatler pasif hale gelir, böylece çakışma (double-booking) engellenir.

### 3. 💳 Güvenli Online Ödeme (Stripe)
Rezervasyonun kesinleşmesi için kapora ödemesi **Stripe API** altyapısı ile güvenli bir şekilde tahsil edilir.

### 4. 🔐 İşletmeci Yönetim Paneli
İşletmeciler kendilerine özel panelden:
* Gelen rezervasyon taleplerini görüntüleyebilir.
* Talepleri **"Onayla"** veya **"Reddet"** butonları ile yönetebilir.
* Saatlik ücretleri güncelleyebilir ve çalışma saatlerini ayarlayabilir.

---

## 🛠 Kullanılan Teknolojiler

Bu proje MVC mimarisine uygun olarak şu teknolojilerle geliştirilmiştir:

* **Backend:** PHP
* **Veritabanı:** MySQL
* **Altyapı:** WordPress
* **Arayüz (Frontend):** HTML5, CSS3, JavaScript
* **Ödeme Servisi:** Stripe API
* **Form & Kod:** WPCode, WPForms

---

## 📄 Proje Dokümanları
Projenin teknik detaylarını içeren sunum ve poster dosyaları:
* [Proje Posteri (PDF)](https://github.com/halil-prog/Hali-Saha-Rezervasyon-Otomasyonu/blob/main/HALI%20SAHA%20REZEERVASYON%20POSTERI%CC%87.pdf)
* [Proje Web sitesinden ekran görüntüleri (PDF)](https://github.com/halil-prog/Hali-Saha-Rezervasyon-Otomasyonu/blob/main/sunumumuz.pdf)

---

## 👥 Proje Ekibi
* **Geliştirici:** Halil Kanatlı
* **Geliştirici:** Göktuğ Özdemir
