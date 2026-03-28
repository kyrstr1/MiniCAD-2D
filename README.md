# 🧰 Mini CAD PRO

Tarayıcı üzerinde çalışan, hafif ve pratik bir **2D teknik çizim uygulaması**.  
Çizim, ölçülendirme ve temel CAD işlemlerini hızlıca yapabilmen için tasarlandı.

---

## 🌐 Canlı Demo

👉 https://kyrstr1.github.io/MiniCAD-2D/

---

## 🚀 Özellikler

### ✏️ Çizim Araçları
- Düz çizgi çizme
- Dikdörtgen çizme
- Grid (ızgara) sistemi ile hizalama (snap)
- Kesik çizgi (---) desteği

### 📏 Ölçülendirme Sistemi
- İki nokta arası ölçü alma
- Ölçü değerini manuel düzenleme
- Ölçü tipleri:
  - Normal (mm)
  - Çap (Ø)
  - Yarıçap (R)
- Ölçü çizgisinin objeden uzaklığını ayarlama (**offset sistemi**)

### 🛠️ Düzenleme
- Objeleri silme
- Ölçüleri düzenleme paneli
- Dinamik ölçü güncelleme

### 🔍 Görünüm
- Mouse wheel ile zoom (yakınlaştırma / uzaklaştırma)
- Snap destekli çizim
- Canlı çizim önizleme

### 📤 Export
- Çizimi **PNG olarak dışa aktarma**

---

## 🎮 Kullanım

### Araçlar
- **Çizgi:** Düz çizgi çizer
- **Dikdörtgen:** Dikdörtgen oluşturur
- **Ölçü:** İki nokta arasında ölçü alır
- **Sil:** Tıklanan objeyi veya ölçüyü siler
- **Kesik:** Çizgileri kesik (---) yapar
- **Export:** Çizimi indirir

---

## 🖱️ Kontroller

- Sol tık: Çizim başlat / bitir
- Mouse hareketi: Çizim yönü
- Mouse wheel: Zoom
- Ölçü üzerine tık: Düzenleme paneli açılır

---

## ⚙️ Ölçü Paneli

Ölçüye tıkladığında açılır:

- **Uzunluk:** Manuel değer gir
- **Offset:** Ölçünün objeden uzaklığı
- **Ø / R:** Ölçü tipi seçimi
- **Kaydet:** Değişiklikleri uygular

---

## 🧠 Teknik Detaylar

- Vanilla JavaScript (framework yok)
- HTML5 Canvas kullanıldı
- Grid snapping algoritması
- Geometrik hesaplamalar:
  - Mesafe (distance)
  - Normal vektör (ölçü offset için)
- Transform (scale) ile zoom sistemi

---

## 🎯 Amaç

Bu proje:
- CNC / teknik resim mantığını öğrenmek
- Basit bir CAD sisteminin nasıl çalıştığını anlamak
- Web tabanlı mühendislik araçları geliştirmek

için geliştirilmiştir.

---

## 🔮 Geliştirme Planı

- Nesne seçme & taşıma
- Snap to endpoint / midpoint
- Gerçek teknik ölçü okları
- DXF export (CNC uyumlu)
- Katman (layer) sistemi

---


## 👨‍💻 Geliştirici

**Mehmet Kayra Satır**

- Web tabanlı mühendislik araçları geliştiriyor

---

## ⭐ Not

Bu proje küçük ama güçlü bir başlangıçtır.  
İleride **tam teşekküllü web tabanlı CAD sistemine** dönüşebilir.
