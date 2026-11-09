# Kadrom — APK'yı bilgisayara hiçbir şey kurmadan alma

1. github.com'da ücretsiz hesap aç (varsa giriş yap).
2. Sağ üstte "+" > "New repository". Adı: kadrom. "Public" seç. "Create repository".
3. "uploading an existing file" bağlantısına tıkla.
4. Bu zip'i bilgisayarında aç; içindeki TÜM dosya ve klasörleri (".github" dahil) sürükleyip bırak.
   Not: ".github" klasörü gizli olabilir; görünmüyorsa Gezgin'de "Gizli öğeleri göster"i aç.
5. "Commit changes" bas.
6. Üstteki "Actions" sekmesine geç. "APK oluştur" çalışmaya başlar (3-6 dk).
7. Yeşil tik çıkınca işe tıkla, en altta "Artifacts" > "Kadrom-apk" indir. İçindeki app-debug.apk'yı telefona at ve kur
   (telefon "bilinmeyen kaynak" izni isteyebilir).

## İlanları güncellemek
veri/ilanlar.json dosyası güncellenince uygulama açılışta yeni ilanları internetten çeker.
APK'yı yeniden kurmaya gerek yok.

## Hata alırsan
Actions'ta kırmızı çarpı çıkarsa hatanın son 20 satırını Claude'a gönder.

Not: Bu "debug" APK telefona kurmak ve test için. Play Store için imzalı AAB ayrıca hazırlanacak.
