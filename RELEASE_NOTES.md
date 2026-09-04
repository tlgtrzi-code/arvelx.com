# RVLX Kasa v3.0.6

Yayın tarihi: 2026-09-04

## Bu sürümde neler var

### Yapılandırılabilir para birimleri
- Ana sayfa, Ön Ödemeli Satış ve Komisyon Hesaplama için ayrı para birimi grupları
- Bayrak ve kur kodu tek seçim: tıklayınca hem isim hem bayrak değişir
- İsimlendirme ekranından para birimi adı düzenlenebilir
- Premium rapor, matematik kontrol Excel’i ve kasa aktarım etiketleri seçime uyar
- Canlı kur çekimi, seçilen sağlayıcı kodunu kullanır (etiketi değil)

### Modüler alan genişletmesi
- Kasa raporu satır etiketleri (`Açılış Kasa`, `Nakit Ciro`, `Toplam Ciro` vb.) yeniden adlandırılabilir
- Gün işlemleri şeridine tek tıkla **Varsayılana Dön**
- Türkçe büyük/küçük harf dönüşümü (İ/I) Excel ve arayüzde bozulmaz

### Diğer
- Alan yapılandırma, kasa aktarım ve hatırlatma yüzeylerinde tutarlılık düzeltmeleri
- İstemci JS birleştirmesi ve paket doğrulama zinciri 3.0.6 ile hizalandı

## Kurulum

Windows: `RVLX_Kasa_Setup.exe`  
Doğrulama: aynı yayındaki `SHA256SUMS.txt`

Önceki kurulumdaki ayarlar ve lisans önbelleği korunur (`%APPDATA%\RVLX Kasa`).

## RVLX Kasa v3.0.2

- Gemini API anahtar havuzu artık yapılandırmadaki tüm anahtarları kullanır (ilk 3 ile sınırlı değil).
- Raf analizinde AI zenginleştiremese bile okunan ürünler kaybolmaz.
- Komisyon fotoğrafı kartvizit zorunluluğu olmadan çalışır (fatura, not, belge).
- Anahtar hataları sınıflandırılır; model/istek hatalarında gereksiz anahtar tüketimi engellenir.
- Kurulum ve paket doğrulama adımları güçlendirildi.

## RVLX Kasa v3.0.1

- Lisans sistemi ve lisans geri kazanım akışı iyileştirildi.
- Mobil PIN erişimi eklendi.
- Yerel ağ güvenliği güçlendirildi.
- Mobil QR bağlantısı eklendi.
- Raf ve taksi fotoğraf işlemleri iyileştirildi.
- AI destekli raf analizinde belirsizlik kontrolü geliştirildi.
- Paket boyutu ve release içeriği optimize edildi.
