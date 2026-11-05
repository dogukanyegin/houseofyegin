# HOUSE OF YEGIN — YENİ ÇOK SAYFALI WEB SİTESİ

Bu sürüm, royalhouseofgeorgia.ge sitesinin **bilgi mimarisini ve bölüm akışını** örnek alır: üstte logo ve iki kademeli açılır menüler, geniş ana slayt, hane ve belge bölümleri, galeri, haberler, ayrı alt sayfalar, yan sütun, çok kolonlu alt bilgi. Referans sitenin kodu, metinleri, görselleri ve birebir görsel tasarımı kopyalanmamıştır.

## Kurulum
ZIP içindeki tüm dosyaları aynı dizin yapısıyla bir web sunucusuna yükleyin. `index.html` ana sayfadır. Diğer `.html` dosyaları doğrudan ziyaret edilebilir. 11 dil tüm sayfalarda dil menüsünden değiştirilir. Yerel geliştirme için `python -m http.server 8000` komutunu çalıştırıp `http://localhost:8000` açabilirsiniz.

## Belgeler
`documents/` içinde The Armorial Register sertifikası, sicil dökümü, şecere araştırması, Hane Tüzüğü ve Türkçe-İngilizce CV bulunur. Özel aile sicil numaraları içeren tam nüfus PDF'si yayımlanmaz.

## Soy ve heraldik notu
Kureyşan/GÜLİNO (10) matbu şecere ile 2026 nüfus kayıtları birbirinden ayrı anlatılır. 0773 numaralı sertifikadaki doğru, uzun çift-haç blazonu aynen aktarılmıştır. Tescil bir kraliyet veya soyluluk tevcihi değildir.

## Telif
Görseller ve belgeler, kullanıcının sağladığı materyallerden alınmıştır; özgün sahibi The Armorial Register olan armanın ve sertifikanın üçüncü kişilere ait telif hakları saklıdır. Araştırma PDF'sindeki matbu kitap şecere fotoğrafı için ayrıca yayın izni gerekip gerekmediği kontrol edilmelidir. Referans siteye ait hiçbir görsel/kaynak dosyası sitede kullanılmamıştır.

## Güncelleme
Diller `translations.js`, `translations-additions.js`, `translations-modern.js` içinde; tasarım `modern.css` içinde; menü, galeri ve slayt etkileşimi `modern.js` içindedir.

## GÜLİNO (10) özgün fotoğrafı (5 Kasım 2026)
Kullanıcının gönderdiği basılı şecere fotoğrafı `assets/gulino10-orijinal-secere.jpg` dosyasına görüntü yönü düzeltilerek eklenmiştir. Gönderilen orijinal dosya `documents/gulino10-kaynak-fotografi-orijinal.jpeg` konumunda korunur. `secere.html`, `seyyidlik.html`, `galeri.html`, `dosyalar.html` ve `index.html` sayfalarında gösterilir. Şecerenin matbu tarihî bağlantılarıyla resmî nüfus bağlantıları birleştirilmemiştir. Yeni etiketler `translations-photo.js` ile 11 dile çevrilmiştir. Fotoğrafın dayandığı basılı eserin telif hakları ilgili hak sahibine aittir.

## 5 Kasım 2026 — House of Yegin E-posta Kanalları
İletişim sayfası ve 14 sayfanın tamamının alt kısmında contact@houseofyegin.se, heraldry@houseofyegin.se, info@houseofyegin.se, office@houseofyegin.se adresleri yer alır. Bağlantılar doğrudan `mailto:` protokolü ile çalışır. 11 dil için kategori çevirileri `translations-emails.js` içindedir.
