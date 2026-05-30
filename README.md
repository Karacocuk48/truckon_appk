# TruckOn App

Flutter ile geliştirilmiş, modern navigasyon sistemine sahip iOS ve Android uygulaması.

## Özellikler

- ✅ Bottom Navigation Bar (Alt Navigasyon)
- ✅ 3 Ana Sayfa (Home, Profile, Settings)
- ✅ Material Design
- ✅ iOS ve Android Uyumluluğu
- ✅ State Management

## Sayfalar

### 1. Ana Sayfa (Home Screen)
- Uygulamaya hoşgeldiniz mesajı
- Özellikler listesi
- Hızlı erişim kartları

### 2. Profil Sayfası (Profile Screen)
- Kullanıcı bilgileri
- Profil fotoğrafı
- Profil düzenleme butonu

### 3. Ayarlar Sayfası (Settings Screen)
- Bildirim ayarları (Toggle)
- Koyu mod ayarı
- Dil seçimi
- Sürüm bilgisi
- Çıkış butonu

## Kurulum

### Gereksinimler
- Flutter SDK (3.0.0 veya üzeri)
- Dart SDK
- iOS için: Xcode (macOS)
- Android için: Android Studio

### Adımlar

1. Repository'yi klonlayın:
```bash
git clone https://github.com/Karacocuk48/truckon_appk.git
cd truckon_appk
```

2. Bağımlılıkları yükleyin:
```bash
flutter pub get
```

3. Uygulamayı çalıştırın:
```bash
flutter run
```

## Proje Yapısı

```
tructon_appk/
├── lib/
│   ├── main.dart                 # Ana uygulama ve navigasyon
│   └── screens/
│       ├── home_screen.dart      # Ana sayfa
│       ├── profile_screen.dart   # Profil sayfası
│       └── settings_screen.dart  # Ayarlar sayfası
├── pubspec.yaml                  # Bağımlılıklar
└── README.md                     # Bu dosya
```

## Navigasyon Sistemi

Uygulama Bottom Navigation Bar kullanarak 3 ana sayfa arasında navigasyon sağlar:

1. **Ana Sayfa** 🏠 - Uygulamaya giriş ve özellikler
2. **Profil** 👤 - Kullanıcı profil bilgileri
3. **Ayarlar** ⚙️ - Uygulama ayarları

## Geliştirilecek Özellikler

- [ ] Drawer navigasyonu
- [ ] State management (Provider/Riverpod)
- [ ] Veritabanı entegrasyonu
- [ ] API entegrasyonu
- [ ] Push notifications
- [ ] Coğrafi konum
- [ ] Yerel depolama

## Lisans

Bu proje MIT lisansı altında lisanslanmıştır.

## İletişim

Sorunuz veya önerileriniz için lütfen issue açın.

---

**Geliştirici**: Karacocuk48
**Başlama Tarihi**: 2026
