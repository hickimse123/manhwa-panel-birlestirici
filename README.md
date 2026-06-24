# 🚀 Scanlation Studio V3.0 - All-in-One Workstation

[![Sürüm](https://img.shields.io/badge/version-3.0.0-blueviolet.svg?style=flat-canvas)](https://github.com/hickimse123/manhwa-panel-birlestirici/)
[![Lisans](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/hickimse123/manhwa-panel-birlestirici/)
[![Performans](https://img.shields.io/badge/Performance-Hardware--Accelerated-orange)](https://github.com/hickimse123/manhwa-panel-birlestirici/)

Scanlation (Manga/Manhwa/Webtoon) süreçlerinizi tarayıcı üzerinden, harici programlara (Photoshop, vb.) ihtiyaç duymadan yönetmenizi sağlayan **hepsi bir arada** profesyonel çalışma istasyonu. 

**v3.0.0 Çirdek Performans Güncellemesi** ile birlikte, ağır görsel işleme ve dikey ayırma (splitter) algoritmaları tamamen **Web Workers** ve **OffscreenCanvas** mimarisine taşınmıştır. Bu sayede 50+ sayfalık yüksek çözünürlüklü projeler, tarayıcı arayüzünde en ufak bir donma veya kasma yaşanmadan tamamen asenkron olarak işlenebilir.

---

## ✨ Temel Özellikler

### 🖼️ Görsel İşleme & Gelişmiş Editör Yetenekleri
* **🎨 Renk Korumalı Levels Motoru:** Görüntüleri griye çevirmeden, RGB kanalları üzerinden dengeli temizlik (RAW Cleaning) yapar.
* **🎛️ Filtre Gücü Matrisi:** Yoğunluk çubukları (slider) sayesinde `Sharpen` (keskinleştirme), `Manga Threshold` (siyah-beyaz eşik griliği) ve yeni eklenen **Denoise (Median/Gaussian gürültü azaltma)** filtrelerinin gücünü esnekçe ayarlayın.
* **⚡ Auto Levels (Auto Fix):** Tek tıkla histogram analizi yaparak en optimum siyah ve beyaz noktalarını otomatik hesaplar. Multi-page serilerde büyük kolaylık sağlar.
* **✂️ Canlı Tuval Kırpıcı (Photoshop Style):** Herhangi bir panele çift tıklayarak açılan ekranda; üst, alt, sağ ve sol kılavuz çizgilerini farenizle canlı ve hassas şekilde sürükleyerek 4 yönlü kırpma yapabilirsiniz.
* **📐 Geometrik Esneklik:** Sağ tık menüsü veya kırpma modalı üzerinden tek tıkla Yatay Çevir, Dikey Çevir veya 90° Döndür işlemlerini uygulayın.

### 🧩 Modüler Engine Mimarisi & Bölümleme
* **🧠 Akıllı Bölücü (Smart Split & Preview):** Webtoon bölümlerini dilimlerken panellerin ortadan kesilmesini engellemek için pikselleri tarar ve kesim çizgisini en yakın beyaz boşluğa kaydırır. Üstelik artık kesim çizgilerini **kesik çizgili kılavuzlarla önizleyebilirsiniz**.
* **↔️ Yatay Ayırıcı & Birleştirici (Spread Mode):** Yan yana duran iki paneli ortadan ikiye bölebilir (Yatay Split) veya tam tersi, manga çift sayfalarını yan yana yatay bir kanvasta birleştirebilirsiniz.
* **📦 Panel Birleştirici (Merger):** Düzensiz panelleri ister manuel gruplayarak, ister **Otomatik Piksel Limiti** moduyla belirlediğiniz hedef yüksekliğe göre dikeyde birleştirir. Grupları yukarı/aşağı taşıyabilir ve `G-1` yerine `Bölüm 1` gibi özelleştirebilirsiniz.

### 📁 Akıllı Dosya & Havuz Yönetimi
* **🔀 Sürükle-Bırak Sıralama:** Dosya adlarına bağımlı kalmadan, görselleri grid üzerinde sürükleyip bırakarak (drag-to-reorder) serbestçe sıralayın.
* **🤐 Arşivden Doğrudan Okuma:** `.zip` uzantılı ham bölümleri `JSZip` entegrasyonu sayesinde doğrudan sisteme yükleyin.
* **➕ Mevcut Havuza Ekleme:** Aktif çalışmayı ve önbelleğe alınmış işlemleri bozmadan, seansın sonuna yeni sayfalar enjekte edin.
* **🔍 Canlı Arama & Tekil Silme:** Dosya adına göre gerçek zamanlı arama yapın; hatalı yüklenen görselleri tüm havuzu bozmadan üzerlerindeki (X) butonuyla tek tek silin.

### 💧 Filigran (Watermark) & Kimlik
* **🎯 Köşe Konumlandırma Matrisi:** PNG logolarınızı sayfaların üzerine toplu şekilde ortalanmış, dikey periyodik veya köşelere (Sağ-Alt, Sol-Üst vb.) hizalayarak basın.
* **✍️ Gelişmiş Metin Filigranı:** Logo yerine ya da ek olarak yazı (takım adı, URL, tarih) basma seçeneği; font, boyut, renk ve opaklık ayarlarıyla birlikte.

### 📤 Otomasyon & Çıktı Optimizasyonu
* **🔁 Filtre Makro/Preset Sistemi:** Sık kullandığınız filtre kombinasyonlarını kaydedip tek tıkla yeni bölümlere uygulayın ya da "Filtrele -> Böl -> Yeniden Adlandır" şeklinde zincirleme otomasyonlar tanımlayın.
* **📐 Hedef Piksel Ölçekleme:** Export esnasında görseller için sabit hedef genişlik (örn. 1200px, 800px) belirleyin. Format seçimini (`WebP`, `JPEG`, `PNG`) ve kalite slider'ını tüm modüllerde esnekçe kullanın.
* **📊 Boyut Tahmini & Tekil İndirme:** Derleme butonuna basmadan önce çıkacak ZIP boyutunu öngörün. İhtiyacınız halinde grid üzerinden sadece tek bir işlenmiş sayfayı sağ tıkla indirin.

---

## 🎹 Klavye Kısayolları & Fare Etkileşimleri

Arayüzün sağ alt köşesindeki **`?`** butonuna tıklayarak veya kısayolları kullanarak fareye dokunmadan çalışabilirsiniz:

| Kısayol / Eylem | İşlev |
| :--- | :--- |
| **G** | Seçili panellerden grup oluştur (Manuel Merger) |
| **Z** | ZIP olarak dışa aktar ve derle |
| **Ctrl + Z** | Yapılan son işlemi geri al (Undo - Son 10 İşlem) |
| **Ctrl + Shift + Z** / **Ctrl + Y** | Geri alınan işlemi ileri sar (Redo destekli gelişmiş stack) |
| **Ctrl + A** | Grid üzerindeki tüm görselleri tek seferde seç |
| **Çift Tık (Double Click)** | Işık masasındaki görsele canlı 4 yönlü kırpıcıyı açar |
| **Shift + Sol Tık** | Birleştirici modunda çoklu sayfa aralığı seçimi |

## 🛠️ Teknik Mimari & Geliştirme

Bu proje saf **HTML, JavaScript (ES6+), JSZip ve Tailwind CSS** kullanılarak geliştirilmiştir. Herhangi bir sunucu tarafı bağımlılığı yoktur, tüm işlemler tarayıcınızda yerel (client-side) olarak gerçekleşir.



                      [ UI / Live DOM ] (Süper Akıcı Arayüz)
                             │      ▲
            Görsel Verisi    │      │  İşlenmiş Piksel Verisi
            & Komutlar       ▼      │
             ┌────────────────────────────────────────┐
             │       Web Workers (Arka Plan)          │
             │  ────────────────────────────────────  │
             │   • Ağır Filtre Algoritmaları          │
             │   • OffscreenCanvas Rendering          │
             │   • Histogram & Auto Levels Analizi    │
             └────────────────────────────────────────┘

## 🚀 Canlı Uygulama & İndirme Seçenekleri

> 🚀 **Aracı tarayıcınızda canlı kullanmak için tıklayın:** > **[Uygulamayı Canlı Aç (GitHub Pages)](https://hickimse123.github.io/manhwa-panel-birlestirici/)**
>
> 💾 **İnternetsiz (Çevrimdışı) kullanmak için direkt bilgisayarınıza indirin:** > **[index.html Dosyasını Direkt İndir (Sağ Tıkla -> Farklı Kaydet)](https://raw.githubusercontent.com/hickimse123/manhwa-panel-birlestirici/main/index.html)**

---

![Uygulama Arayüzü](gruplama)

---
Created by **Hic Kimse** 🚀
