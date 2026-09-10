# TTCore LINE Account Transfer

Primary token kullanarak kısa ömürlü bir QR kod oluşturan ve LINE hesabına yeni telefondan giriş/hesap aktarımı yapılmasını sağlayan masaüstü çözümüdür.

> Bu depo yalnızca ürün tanıtımı amacıyla hazırlanmıştır. Kaynak kod paylaşılmamaktadır.

## Ne işe yarar?

TTCore LINE Account Transfer, geçerli bir LINE primary token'ı doğrular ve tek kullanımlık bir QR oturumu oluşturur. Oluşturulan QR kod, yeni telefondaki resmi LINE uygulamasıyla taranarak giriş veya hesap aktarımı sürecinin tamamlanmasını sağlar.

## Özellikler

- Primary token doğrulama
- Kısa ömürlü ve tek kullanımlık QR kod üretimi
- Telefondan QR kod ile LINE hesabına giriş/hesap aktarımı
- Hesap adını doğrulama ekranında gösterme
- Aktarım durumunu anlık takip etme
- Başarılı, süresi dolmuş ve başarısız işlemler için anlaşılır durum mesajları
- Yerel web arayüzü
- Windows 10 ve Windows 11 desteği
- Kolay başlatma ve sade kullanım akışı
- Token, QR oturum bilgisi ve özel anahtarları uygulama loglarına yazmayan güvenlik yaklaşımı
- İşlem tamamlandığında veya süre dolduğunda geçici oturum verilerini bellekten temizleme

## Nasıl çalışır?

1. Kullanıcı, sahibi olduğu veya yönetme yetkisine sahip olduğu hesaba ait geçerli primary token'ı uygulamaya girer.
2. Uygulama token'ı doğrular ve hesaba özel, kısa ömürlü bir QR kod oluşturur.
3. Yeni telefonda resmi LINE uygulaması açılır.
4. **Giriş yap > QR kod ile giriş yap > QR kodu tara** adımları izlenir.
5. Ekrandaki QR kod telefonla taranır.
6. Telefon doğrulamasının ardından giriş/hesap aktarımı tamamlanır.

QR oturumları kısa sürelidir. Süre dolarsa yeni bir QR kod oluşturulmalıdır. Başarılı bir aktarım, önceki ana cihazdaki oturumu kapatabilir.

## Güvenlik ve sorumlu kullanım

- Primary token hiçbir zaman başka kişilerle paylaşılmamalıdır.
- Yalnızca size ait veya yönetmek için açıkça yetkilendirildiğiniz hesaplarda kullanılmalıdır.
- Uygulama yerel bilgisayarda çalışacak şekilde tasarlanmıştır.
- Primary token diske veya uygulama loglarına yazılmaz; işlem sırasında yalnızca bellekte tutulur.
- QR oturum verileri işlem tamamlandığında veya süre dolduğunda temizlenir.
- Bu proje LINE Corporation'ın resmi ürünü değildir ve LINE ile bağlantılı veya LINE tarafından desteklenmiş değildir.

## Satış ve lisanslama

Bu yazılımın kaynak kodu ve kullanım lisansı satışa sunulmuştur. Satın alma, fiyatlandırma, lisans kapsamı, kurulum ve teknik destek bilgileri için WhatsApp üzerinden iletişime geçebilirsiniz.

**WhatsApp:** [0546 805 65 12](https://wa.me/905468056512)

## Kaynak kod

Kaynak kod bu depoda yayımlanmamaktadır. Bu depo ürünün yeteneklerini ve çalışma şeklini genel hatlarıyla tanıtmak amacıyla hazırlanmıştır.

## Yasal not

Alıcı ve kullanıcı; ilgili hizmet koşullarına, yürürlükteki mevzuata ve hesap sahibinin açık yetkisine uygun hareket etmekten sorumludur.

