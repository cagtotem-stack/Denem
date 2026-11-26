# DriveDash Golf Edition — Android proje paketi

Bu proje Volkswagen Golf 7 için 10 inç yatay Android 13 multimedya ekranına yönelik, ana ekran (HOME launcher) olarak seçilebilen bir Android uygulama iskeletidir.

## Şu anki özellikler
- BYD tarzı ferah cam kartlı tasarımın Golf 7'ye uyarlanmış sürümü
- Büyük saat ve tarih
- Google Maps / Yandex Navigasyon seçim ekranı
- Müzik, telefon, uygulama menüsü ve Android Ayarları kısayolları
- Android cihazdaki başlatılabilir uygulamaları listeleme
- HOME launcher intent filtresi
- 10 inç yatay ekran için esnek yerleşim

## Önemli sınırlar
- Bu teslimat kaynak proje ve tarayıcı önizlemesidir; burada Android SDK/Gradle derleme ortamı bulunmadığından imzalı APK üretilmedi.
- Araç hızı, yakıt, lastik basıncı, klima veya CANBUS verileri okunmaz. Ekrandaki araç resmi dekoratiftir.
- Hava durumu ve medya bilgisi canlı servis entegrasyonu henüz yapılmadı.
- Google Maps ve Yandex kısayolları cihazda ilgili uygulama kuruluysa uygulamayı açar; kurulu değilse web haritasına yönlendirir.

## Windows'ta APK oluşturma
1. Android Studio'yu kurun (Android SDK Platform 35 ve Android SDK Build-Tools).
2. Bu klasörü Android Studio ile `Open` seçeneğinden açın.
3. Gradle senkronizasyonunu tamamlayın.
4. `Build > Build Bundle(s) / APK(s) > Build APK(s)` seçin.
5. APK yolu: `app/build/outputs/apk/debug/app-debug.apk`
6. APK'yı USB bellekle teybe kopyalayıp kurun.
7. Kurulumdan sonra HOME tuşuna basıp `DriveDash Golf` seçin ve `Her zaman` deyin.

İlk kurulumda bilinmeyen kaynaklardan uygulama yükleme izni istenebilir. Sadece kendi oluşturduğunuz APK'yı kurun.
