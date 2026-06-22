# 🛒 Kasva E-Commerce App

Kasva, Flutter ve Dart kullanılarak geliştirilmiş, modern UI/UX prensiplerine uygun, dinamik bir mobil e-ticaret uygulamasıdır. Proje, temiz kod mimarisi ve sürdürülebilir state yönetimi hedeflenerek inşa edilmiştir.

---

## 📱 Proje Tanıtım Videosu

Uygulamanın arayüzünü, akışını ve çalışan tüm özelliklerini detaylıca görmek için aşağıdaki bağlantıdan tanıtım videosunu izleyebilirsiniz:

[![Kasva Uygulama Tanıtımı](https://img.shields.io/badge/▶_Videoyu_İzle-Google_Drive-blue?style=for-the-badge&logo=googledrive)](https://drive.google.com/file/d/1B8I5l7YH8dpkWwI69D8i4MFzYFsJBIIU/view)

*(Alternatif olarak [buraya tıklayarak](https://drive.google.com/file/d/1B8I5l7YH8dpkWwI69D8i4MFzYFsJBIIU/view) direkt Google Drive üzerinden izleyebilirsiniz.)*

---

## ✨ Özellikler

* **Dinamik Ürün Listeleme & Detaylandırma:** Ürünlerin ana sayfada sergilenmesi, kategorilere göre ayrılması ve detaylı ürün kartları.
* **Sepet ve Favori Yönetimi:** Kullanıcıların ürünleri sepetlerine veya favori listelerine ekleyip çıkarabileceği akıcı sepet deneyimi.
* **Gelişmiş State Management:** Uygulama içi tüm veri akışı ve sepet durumları performanslı bir şekilde yönetilir.
* **Özelleştirilmiş UI Bileşenleri:** `Google Fonts` ve `Font Awesome` ikonları ile zenginleştirilmiş, göze hitap eden modern arayüz elementleri.
* **Özel Uygulama İkonu:** Projeye özel entegre edilmiş launcher icon desteği.

---

## 🛠️ Kullanılan Teknolojiler & Paketler

Projede kullanılan temel bağımlılıklar ve kütüphaneler şunlardır:

* **Framework:** [Flutter](https://flutter.dev/) (Dart)
* **State Management:** `provider` (Sürdürülebilir ve performanslı durum yönetimi için)
* **Tipografi:** `google_fonts` (Modern ve şık yazı tipleri için)
* **İkon Kütüphanesi:** `font_awesome_flutter` (Zengin sosyal medya ve arayüz ikonları)
* **Asset Yönetimi:** `flutter_launcher_icons` (Özelleştirilmiş uygulama açılış ikonu)

---

## 📂 Klasör Yapısı

Proje, kodun okunabilirliğini artırmak adına modüler bir yapıda kurgulanmıştır:

```text
lib/
├── models/          # Ürün, kullanıcı ve sepet veri modelleri
├── providers/       # Uygulama durumunu ve logic'leri yöneten Provider sınıfları
├── screens/         # Home, Detail, Cart, Favorites gibi ana ekranlar
├── widgets/         # Yeniden kullanılabilir, bağımsız UI bileşenleri
└── main.dart        # Uygulamanın başlangıç ve konfigürasyon noktası
