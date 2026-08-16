# Giderim Aile

Ortak online gelir/gider uygulaması. Sen ve Zehra aynı hesabı kullanarak aynı kayıtları görebilirsiniz.

## Kurulum
1. Firebase'de proje oluştur.
2. Authentication > Sign-in method > Email/Password etkinleştir.
3. Firestore Database oluştur.
4. Web App ekle ve verilen config'i `firebase-config.example.js` içine yazıp dosyayı `firebase-config.js` adıyla kaydet.
5. `firestore.rules` içeriğini Firestore Rules'a koy.
6. Dosyaları GitHub repository'ye yükle.
7. GitHub Settings > Pages > Deploy from branch > main / root seç.
8. Oluşan Pages adresini sen ve Zehra telefondan açıp aynı hesapla giriş yapın.

Bu sürüm: ortak hesap, anlık Firestore senkronizasyonu, gelir/gider, kategori, açıklama, tarih, aylık görünüm ve silme içerir.
