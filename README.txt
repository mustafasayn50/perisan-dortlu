PERİŞAN DÖRTLÜ – GitHub Pages paketi

PAKET İÇERİĞİ
- index.html: uygulama
- manifest.json: ana ekrana ekleme bilgileri
- apple-touch-icon.png: iPhone ana ekran ikonu (180x180)
- icon-192.png ve icon-512.png: PWA ikonları
- sw.js: çevrimdışı önbellek

GITHUB PAGES YAYINLAMA
1. GitHub'da yeni bir repository oluştur (ör. perisan-dortlu).
2. Bu klasördeki TÜM dosyaları repository ana dizinine yükle. index.html alt klasörde kalmamalı.
3. Repository > Settings > Pages bölümüne gir.
4. Build and deployment altında Deploy from a branch seç.
5. Branch: main, Folder: /(root) seçip Save'e bas.
6. GitHub'ın verdiği https://KULLANICI.github.io/perisan-dortlu/ adresini Safari'de aç.
7. Safari Paylaş > Ana Ekrana Ekle.

ÖNEMLİ – MEVCUT SKORLARI KORUMA
Tarayıcıdaki localStorage kayıtları alan adına bağlıdır. Netlify'dan GitHub Pages'e geçince kayıtlar otomatik taşınmaz. Eski Netlify uygulamasındaki Arşiv sekmesinden Yedeği indir özelliğini kullanıp JSON yedeğini yeni GitHub Pages uygulamasında Arşiv > Yedeği yükle ile içe aktar. Önce eski Netlify sürümüne bu yedekleme özelliği eklenip yayınlanmalı; aksi hâlde eski uygulamada bu düğme görünmez.

UYGULAMA ÖZELLİKLERİ
- Dört ayrı skor alanı ve CM/AM takım toplamları
- Düşük toplamlı takımın CM veya AM olarak gösterilmesi
- El kaydetme, düzenleme, silme ve geri alma
- Oyun arşivi ve arşivden geri yükleme
- JSON yedek dışa/içe aktarma
- Ana ekrana ekleme ikonu ve çevrimdışı önbellek
