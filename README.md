# Gastrofobi Android uygulaması

Bu klasör, `kadirbaykus/gastrofobi` web sitesine eklenmek üzere hazırlanmıştır. Android uygulaması siteyi WebView içinde açar; uygulamadaki web dosyaları `app/src/main/assets/` içindedir. Yemek fotoğrafları için internet bağlantısı gerekir.

## APK indirme

Bu klasörü depoya ekledikten sonra GitHub'da **Actions** sekmesine gidin. **Build Gastrofobi Android APK** iş akışının yeşil tikli çalışmasını açın. Sayfanın altındaki **Artifacts** bölümünden `gastrofobi-debug-apk` dosyasını indirin. İnen ZIP'in içindeki `app-debug.apk` dosyasını Android telefona aktararak kurabilirsiniz.

Bu debug APK test ve doğrudan telefona kurulum içindir; Google Play'de yayınlamak için ayrıca imzalı sürüm gerekir.
