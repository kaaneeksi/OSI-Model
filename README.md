# OSI (Open Systems Interconnection Model)

OSI modeli, ağ oluşturmada kullanılan temel bir modeldir. Bu model, ağ bağlantılı tüm cihazların veriyi nasıl göndereceğini, alacağını ve yorumlayacağını belirleyen bir çerçeve sağlar.

![osı](https://github.com/kaaneeksi/ISO-Model/blob/main/G%C3%B6rseller/%C4%B1so.svg)


## Application 

- Bu katman kullanıcıya bir Grafik Arayüzü sağlar (GUI). DNS, FTP, SSH gibi protokoller bu katmanda çalışır. 
- Kullanıcıların doğrudan etkileşimde bulunduğu katmandır.
- İnternet tarayıcıları, e-posta istemcileri ve diğer uygulamalar bu katmanda çalışır.
- Kullanıcının bilgisayarla doğrudan etkileşimde olduğu katmandır.

## Presentation 

- Bu katman, veri formatlarını çevirir ve şifreleme/dekripte işlemlerini yönetir.
- Veri formatlarını uygun hale getirir ve farklı cihazlar arasında veri alışverişini sağlar.

## Session Layer

- Bu katman, bilgisayarlar arasında oturumları yönetir.
- Oturum, bilgisayarlar arasında gerçekleşen bir konuşmayı temsil eder.
- Bağlantı kurma, veri alışverişi ve bağlantıyı sonlandırma gibi işlevleri içerir.

## Transport

- Bu katman, bilgisayarlar arasında veri transferini yönetir.
- Veri bütünlüğünü sağlar ve paketleri sıralar.
- TCP (Transmission Control Protocol) ve UDP (User Datagram Protocol) bu katmanda çalışır.

## Network

- Bu katman, bilgisayarların birbirleriyle iletişim kurmasını sağlar.
- IP adresleri kullanarak paketleri yönlendirir ve hedefe ulaştırır.
- Router'lar bu katmanda çalışır ve farklı ağlar arasındaki iletişimi sağlar.

## Data Link

- Bu katman, ağdaki cihazlar arasında doğrudan iletişimi sağlar.
- Frame adı verilen paketleri alır ve gönderir.
- Bu katmanda hata kontrolü ve akış kontrolü gibi temel işlevler bulunur.

## Physical Layer

- Bu katman, bilgisayarlar arasındaki gerçek bağlantıyı temsil eder.
- Kablolar, konektörler, elektrik sinyalleri ve diğer donanım özellikleri bu katmanda yer alır.
- Verinin fiziksel olarak nasıl gönderildiği ve alındığıyla ilgilenir.
