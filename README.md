# 🚀 Scanlation Toolkit V2.1 - All-in-One Studio

Scanlation (Manhwa/Manga) süreçlerinizi tarayıcı üzerinden, harici programlara (Photoshop, vb.) ihtiyaç duymadan yönetmenizi sağlayan **hepsi bir arada** çalışma istasyonu.

## 🛠️ Temel Özellikler

* **🎨 Renk Korumalı Levels Motoru:** Görüntüleri griye çevirmeden, RGB kanalları üzerinden dengeli temizlik (RAW Cleaning) yapar.
* **🧠 Akıllı Bölücü & Kesim Algoritması (Smart Split):** Webtoon bölümlerini dilimlerken panellerin tam ortadan kesilmesini engellemek için pikselleri otomatik tarar ve kesim çizgisini en yakın beyaz boşluğa kaydırır.
* **✂️ Canlı Tuval Kırpıcı (Photoshop Style Canvas Cropper):** Herhangi bir panele çift tıklayarak açılan ekranda, sarı kılavuz çizgilerini farenizle doğrudan aşağı-yukarı sürükleyerek kırpılacak alanı görsel üzerinden canlı ve hassas şekilde belirleyebilirsiniz.
* **🧩 Modüler Engine Mimarisi:**
    * **Panel Birleştirici:** Düzensiz panelleri ister manuel gruplayarak, ister **Otomatik Piksel Limiti** moduyla belirlediğiniz hedef yüksekliğe göre tek tıkla dikeyde birleştirir.
    * **Dönüştürücü (Converter) & Filtre Gücü Matrisi:** Yoğunluk çubukları (slider) sayesinde `Sharpen` (keskinleştirme) ve `Manga Threshold` (siyah-beyaz eşik griliği) filtrelerinin gücünü tamamen esnek olarak ayarlayabilirsiniz.
    * **Ardil Adlandırıcı:** Karışık isimlendirilmiş sayfaları `001`, `002` şeklinde sıralı ve basamak ayarlı olarak yeniden indeksler.
    * **Watermark Motoru:** PNG logolarınızı sayfaların üzerine toplu şekilde (ortalanmış veya dikey periyodik tekrar düzeninde) işler.
* **💾 Kalıcı Oturum (Auto-Save):** Tarayıcıyı kapatsanız bile çalışma havuzunuz `localStorage` sayesinde korunur.
* **⚡ Hızlı İş Akışı:**
    * **Ctrl+Z (Geri Al):** Hatalı işlemleri anında geri al.
    * **Klavye Kısayolları:** `g` (Grup), `z` (ZIP), `c` (Sıfırla) ve yön tuşları ile mouse kullanmadan çalış.
* **🖥️ Modern Arayüz:** JetBrains Mono fontu, A/B karşılaştırma çizgisini tek tıkla açıp kapatarak ön izleme panelinde **sonsuz kaydırma (scroll) özgürlüğü** sunan yapısı ve Tailwind CSS destekli göz yormayan karanlık mod.

## ⌨️ Klavye Kısayolları & Fare Etkileşimleri

| Kısayol / Eylem | İşlev |
| :--- | :--- |
| **G** | Seçili panellerden grup oluştur (Manuel Merger) |
| **Z** | ZIP olarak dışa aktar ve derle |
| **Ctrl + Z** | Yapılan son işlemi geri al (Undo) |
| **Çift Tık (Double Click)** | Işık masasındaki görsele canlı Photoshop tipi kırpıcıyı açar |
| **Shift + Sol Tık** | Birleştirici modunda çoklu sayfa aralığı seçimi |

## 📜 Sürüm Notları (V2.1.0 - Release)

Bu sürüm, **V2.0** "Studio Edition" mimarisinin üzerine tamamen editör konforu, gelişmiş otomasyon ve hassas filtreleme odaklı inşa edilmiştir.
- **Smart Split & Auto-Merger:** Webtoon editörleri için panel ortasından kesilmeleri önleyen akıllı boşluk yakalama algoritması ve otomatik piksel limitli birleştirme motoru entegre edildi.
- **Canlı Canvas Kırpma:** Kutuya sayı yazarak kırpma devri kapandı; sürükle-bırak kılavuz çizgileriyle görsel üzerinden canlı kesim sağlandı.
- **Filtre Yoğunluk Kontrolü:** Aç-kapa filtre mantığı ezilerek slider tabanlı dinamik `Sharpen` ve `Threshold` kontrol matrisine geçildi.
- **Ön İzleme Esnekliği:** A/B karşılaştırma çizgisi açılır-kapanır yapılarak büyük webtoon sayfalarında serbest dikey/yatay scroll (kaydırma) imkanı tanındı.

## 💻 Geliştirme

Bu proje saf **HTML, JavaScript (ES6+), JSZip ve Tailwind CSS** kullanılarak geliştirilmiştir. Herhangi bir sunucu tarafı bağımlılığı yoktur, tüm işlemler tarayıcınızda yerel (client-side) olarak gerçekleşir.

---

*Scanlation işlerini hızlandırmak için geliştirilmiştir.*

---

### 🌐 Canlı Uygulama & İndirme Seçenekleri
> 🚀 **Aracı tarayıcınızda canlı kullanmak için tıklayın:**  
> **[Uygulamayı Canlı Aç (GitHub Pages)](https://hickimse123.github.io/manhwa-panel-birlestirici/)**
>
> 💾 **İnternetsiz (Çevrimdışı) kullanmak için direkt bilgisayarınıza indirin:**  
> **[index.html Dosyasını Direkt İndir (Sağ Tıkla -> Farklı Kaydet)](https://raw.githubusercontent.com/hickimse123/manhwa-panel-birlestirici/main/index.html)**

---

![Uygulama Arayüzü](gruplama)

---
Created by **Hic Kimse** 🚀
