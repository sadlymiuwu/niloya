# Niloya

Pastel temalı, mobil uyumlu kişisel takip uygulaması.

## İçerik
- Cilt bakım rutini ve günlük işaretleme
- Regl başlangıç/bitiş, belirtiler ve notlar
- İlaç adı, kullanıcının girdiği doz ve tarih kaydı
- Günlük ruh hali, uyku, su ve aktivite kaydı
- JSON yedek dışa aktarma

## Telefona yükleme
Bu bir PWA'dır. Ana ekrana yükleme ve çevrimdışı kullanım için HTTPS üzerinden yayınlanmalıdır.
1. Bu klasörü bir HTTPS statik site barındırma hizmetine yükle.
2. Siteyi Safari/Chrome ile aç.
3. iPhone: Paylaş > Ana Ekrana Ekle. Android: tarayıcı menüsü > Uygulamayı yükle / Ana ekrana ekle.

## Gizlilik
Veriler tarayıcının localStorage alanında, cihazda saklanır. Sunucuya gönderilmez. Tarayıcı verileri temizlenirse kaybolabilir; Kayıtlar sekmesinden JSON yedeği al.

## Önemli
Bu uygulama tıbbi öneri veya ilaç hatırlatma/alarm sistemi değildir. İlaç kullanımında doktor/eczacı ve ürün etiketindeki talimatlara uy. Regl tahminleri veya tanı üretmez.
