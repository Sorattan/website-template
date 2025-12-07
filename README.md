# Dent&Care Diş Kliniği Web Sitesi

Bu proje, **Dent&Care** isimli hayali bir diş kliniği için hazırlanmış, çok sayfalı ve responsive bir web sitesi tasarımıdır.

---

## Özellikler

### 👨‍💻 Kullanıcı Arayüzü (Front-End)

- **Ana Sayfa (`index.html`)**
  - Diş hizmetlerini tanıtan slider
  - Hızlı randevu ve çalışma saatleri alanı
  - Öne çıkan hizmetler, fiyat planı, hasta yorumları, hekimler
  - Ana sayfada son 5 duyurunun kart ve modal yapısıyla gösterimi

- **Hakkımızda (`about.html`)**
  - Kliniğin genel tanıtımı
  - Hizmet yaklaşımı ve kısa açıklamalar

- **Misyon & Vizyon (`misyon-vizyon.html`)**
  - Kliniğin misyon ve vizyonunun ayrı bir sayfada detaylı anlatımı

- **Hizmetlerimiz (`service.html`)**
  - İmplant, Ortodonti (Diş Teli), Diş Beyazlatma vb. hizmet kartları
  - Bazı hizmetler için `id` tanımlı anchor yapısı (slider’dan tıklayınca ilgili hizmete iner)

- **Hekimlerimiz (`team.html`)**
  - Doktor kartları, unvanları ve sosyal medya ikonları

- **Fiyatlandırma (`price.html`)**
  - Fiyat planları ve tedavi bazlı örnek ücretlendirmeler

- **Hasta Yorumları (`testimonial.html`)**
  - Slider içinde hasta referansları

- **Duyurular (`duyurular.html`)**
  - Tüm duyuruların tarih sırasına göre listelendiği sayfa
  - Ana sayfadaki duyurularla uyumlu içerik

- **Sayılarla Kliniğimiz (`sayilarla-klinik.html`)**
  - **Chart.js** ile hazırlanmış:
    - Yıllara göre hasta sayısı (bar chart)
    - Tedavi türlerinin oranları (doughnut chart)

- **Randevu Sayfası (`appointment.html`)**
  - Hizmet, doktor, tarih ve saat seçilen randevu formu

- **İletişim (`contact.html`)**
  - Klinik adresi, telefon ve e-posta bilgileri
  - **Şikâyet & Öneri Formu**
  - **Google Maps** üzerinden gömülü konum gösterimi

---

### 🛠 Yönetici Panelleri (Admin Arayüzleri)

Admin dosyaları `admin/` klasörü altında yer alır. Bu sayfalar yalnızca **arayüz tasarımı** içermektedir; sunucu tarafı kod (database, gerçek kayıt vb.) bulunmamaktadır.

- **Duyuru Yönetimi (`admin/admin-duyurular.html`)**
  - Yeni duyuru ekleme formu (tarih, başlık, özet, detay, ek dosya alanları)
  - Statik tablo ile mevcut duyuruların listelenmesi
<img width="2531" height="1231" alt="image" src="https://github.com/user-attachments/assets/738b58cf-b9e0-4507-8213-c9d032f98540" />
<br><br>

- **Hizmet Yönetimi (`admin/admin-hizmetler.html`)**
  - Hizmet adı, kategorisi, kısa & detaylı açıklama, fiyat, durum vb. alanlara sahip form
  - Anasayfada öne çıkarma seçeneği
  - Statik hizmet listesi tablosu
<img width="2529" height="1237" alt="image" src="https://github.com/user-attachments/assets/6755f5e5-af64-475d-a138-9be1e9fa6b1c" />
<br><br>

- **Sayılarla Klinik Verileri (`admin/admin-sayilarla-klinik.html`)**
  - Yıllara göre hasta sayısı verileri için düzenlenebilir tablo
  - Tedavi türlerinin yüzdesel dağılımını düzenlemek için form alanları
  - Bu verilerin, kullanıcı tarafındaki Chart.js grafiklerini beslediği varsayılır (tasarım mantığı)
<img width="1669" height="933" alt="image" src="https://github.com/user-attachments/assets/c5950a72-d95b-40e3-8dd0-d3429b64be1e" />

---

## Kullanılan Teknolojiler

- **HTML5**, **CSS3**
- **Bootstrap 5**
- **JavaScript**
- **jQuery**
- **Chart.js** (istatistik grafikleri için)
- **Owl Carousel** (slider/yorum alanları için)
- **TwentyTwenty / Before-After** kütüphanesi (bazı görsel karşılaştırmalar için)
- Hazır bir **dental klinik template** üzerinden özelleştirilmiş içerik (Türkçe metinler, sayfa eklemeleri, admin arayüzleri vb.)

---
