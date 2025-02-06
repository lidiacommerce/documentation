---
description: >-
  Bu ay boyunca Lidia platformunda fonksiyonellik ve kullanıcı deneyimini
  iyileştiren en son güncellemeleri ve geliştirmeleri keşfedin.
cover: ../../../.gitbook/assets/feb.png
coverY: 0
layout:
  cover:
    visible: true
    size: full
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Lidia 2.1.x sürüm notları

Bu ayki sürüm, Lidia platformunun çeşitli bileşenlerinde önemli güncellemeler içeriyor. Bu bileşenler arasında **Console, Merchant Console ve Ürün Bilgi Yönetimi (PIM) sistemleri** bulunuyor. Yapılan iyileştirmeler, iş akışlarını optimize etmeyi ve tüm platform kullanıcıları için daha akıcı bir deneyim sunmayı amaçlıyor.

{% hint style="info" %}
🔎 **Sürüm Kodları Hakkında**\
Bu belgede, Lidia platformunun farklı bileşenleri için sürüm kodlarını bulabilirsiniz:

* **LC:** Lidia Console – Ana yönetim konsoluna yönelik iyileştirmeler ve hata düzeltmeleri.
* **LMC:** Lidia Merchant Console – Satıcı araçları ve iş akışlarına özel güncellemeler.
* **LP:** Lidia PIM (Ürün Bilgi Yönetimi) – Ürün veri yönetimiyle ilgili geliştirmeler ve yeni özellikler.

Bu kodlar, platform genelindeki iyileştirmelerin hangi alanlara yönelik olduğunu takip etmenize yardımcı olur.
{% endhint %}

***

## **Sürüm 2.2.1 - 7 Ocak 2025**

### 📈 **Satış Yönetimi İyileştirmeleri** <a href="#satis-yonetimi-iyilestirmeleri" id="satis-yonetimi-iyilestirmeleri"></a>

#### Sipariş fatura bilgilerinde kesim tarihinin gösterilmesi Sürüm Tarihi: 07/01/2025 Sürüm Numarası: <mark style="color:purple;">LMC-2.1.1.1</mark>

Sipariş detayında bulunan fatura bilgileri alanında daha önceden fatura kesim tarihi bilgisi gösterilmiyordu. Bu geliştirme ile fatura yükleme işlemi sırasında fatura kesim tarihi bilgisinin alınması zorunlu kılınarak, sipariş detay sayfasındaki fatura bilgileri alanında gösterilmesi sağlanmıştır.

#### Teslimat iptal kayıtlarının gösterilmesi Sürüm Tarihi: 07/01/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.1.1.1</mark>

Yönetici tarafından gerçekleşen teslimat iptali sonrasında, tekrar kargoya verilen siparişlerin iptal kayıtları sipariş hareketlerinde gösterilmiyordu. Bu geliştirme ile siparişe ait tüm müdahaleler kayıt olarak gösterilmesi sağlanmıştır.

***

### 📈Satış Sonrası Hizmetler Güncellemeleri

#### Kargo iade barkod süresi geliştirmesi Sürüm Tarihi: 07/01/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.1.1.2 / LMC-2.1.1.2</mark>

Daha önce pazaryeri anlaşmalı kargo firmalarına iade için üretilen kargo barkodu geçerlilik süresi yasal olarak belirlenmiş 14 günlük süreyi kapsamayabiliyordu. Bu geliştirme ile kargo iade barkodunun geçerlilik süresi yasal düzenlemelere uygun olarak 7+7 şeklinde toplam 14 gün olacak şekilde güncellenmiştir. Böylece müşterilere 14 günlük yasal iade süresi sağlanmış ve süreç yasal gerekliliklere uygun hale getirilmiştir.

#### İptal ve iade detay ekranında barkod numarası gösterimi Sürüm Tarihi: 07/01/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.1.1.3</mark> 

Console panelinde sipariş detayındaki ürün satırlarında barkod numarası görüntülenmekteydi. Bu geliştirme ile iptal ve iade taleplerine ait detay ekranında da ürünlere ilişkin barkod numaralarının görüntülenmesi sağlanarak barkod bilgilerine her iki ekran üzerinden de erişim imkanı sunulmuştur.\


***

### 🌟Kullanıcı Deneyimi Geliştirmeleri

#### Giriş ekranlarının yenilenmesi Sürüm Tarihi: 07/01/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.1.1.4 / LMC-2.1.1.3</mark>

Daha önce yönetici paneli ve satıcı paneli giriş ekranları eski yapıda çalışmaktaydı. Bu geliştirme ile giriş ekranları yeni tasarıma ve altyapıya geçirilerek kullanıcı deneyimi iyileştirilmiş ve daha modern giriş süreci sağlanmıştır.

#### Navigasyon menüsünün yenilenmesi Sürüm Tarihi: 07/01/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.1.1.5 / LMC-2.1.1.4</mark>

Bu geliştirme ile navigasyon menüsü yeni tasarıma geçirilerek kullanıcı arayüzü modernize edilmiş, daha kullanıcı dostu ve erişilebilir bir menü yapısı sunulmuştur.

#### Tarayıcı logosunun güncellenmesi Sürüm Tarihi: 07/01/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.1.1.6 / LMC-2.1.1.5</mark>

Daha önce platformda tarayıcı logosu eski bir görsel ile temsil edilmekteydi. Bu geliştirme ile platformun yeni marka kimliğine uygun olarak tarayıcı logosu güncellenmiş, kullanıcıların platformu tarayıcı sekmelerinde daha kolay tanıyabilmesi ve modern bir görünüm elde edilmesi sağlanmıştır.\


***

## **Sürüm 2.1.2 -** 21 Ocak 2025

### 📈Satış Sonrası Hizmetler Geliştirmeleri

#### İade nedeni ve açıklama bilgilerinin görüntülenmesi Sürüm Tarihi: 21/01/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.1.2.1 - LMC-2.1.2.1</mark>

İade nedeni seçildiğinde, isteğe bağlı bir de açıklama yazıldığında, bu bilgiler admin panelde ve satıcı panelinde görüntülenmiyordu. Bu geliştirme ile iade nedeni ve açıklama alanlarının, talep detay ekranlarında doğru şekilde görüntülenmesi sağlandı.

***

### 🚚Teslimat Yönetimi İyileştirmeleri

#### Kargo etiketlerine sipariş numaralarının eklenmesi Sürüm Tarihi: 21/01/2025 Sürüm Numarası: <mark style="color:purple;">LMC-2.1.2.2</mark>

Partnerler, siparişlerini kargoya verirken oluşturdukları kargo etiketlerinde sadece gönderici ve alıcı bilgileri bulunmaktaydı. Sipariş numarası bu etiketlerde yer almıyordu. Bu geliştirme ile birlikte, partnerlerin oluşturduğu kargo etiketlerinde artık sipariş numarası da yer alacaktır. Böylece, kargo takibi sırasında siparişe daha kolay erişim sağlanabilecektir.

***

### 🌟Kullanıcı Deneyimi Geliştirmeleri

Yeni sol menü yapısı ve lisans tabanlı kullanıcı izinleri iyileştirmeleri\
Sürüm Tarihi: 21/01/2025\
Sürüm Numarası: <mark style="color:purple;">LC-2.1.2.2</mark>

Kullanıcıların yalnızca atanmış lisans kapsamları dahilindeki yeteneklere erişebilmelerini sağlamak amacıyla admin panelde lisans tabanlı kullanıcı izinleri iyileştirilmiştir. Bu geliştirme ile lisans türleri arasındaki ayrımlar netleştirilmiş ve daha verimli operasyonel süreçlere olanak tanımak için yeni sol menü yapısına geçilmiştir.

***

### 💬Sosyal Yetenekler Geliştirmeleri

#### Yorum ve puanlama ekranlarının aktifleştirilmesi Sürüm Tarihi: 21/01/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.1.2.3</mark>

Yorum ve puanlama ekranları etkinleştirildi, böylece platform müşterilerinin geri bildirimlerinin ve puanlamalarının görüntülenmesi sağlandı.

***

### 👥Kullanıcı Yönetimi Geliştirmeleri

#### Platform ve organizasyon rol ayrımı ile gelişmiş rol yönetimi Sürüm Tarihi: 21/01/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.1.2.4</mark>&#x20;

Platform genelindeki rolleri kuruluşa özgü rollerden ayırarak Roller sayfası yeniden tasarlandı. Bu geliştirme ile daha net rol yönetimi sağlanması, izin görünürlüğünün iyileştirilmesi ve daha yapılandırılmış bir erişim kontrol sistemi hedeflendi.



***

Bu güncellemeler, Lidia Platformu'nun işlevselliğini ve kullanılabilirliğini artırmak için tasarlanmıştır ve tüm kullanıcılar için daha sorunsuz ve verimli bir deneyim sunmayı hedeflemektedir. Gelecek ay daha fazla iyileştirme için bizi izlemeye devam edin!



\
\
