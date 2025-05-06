---
description: >-
  Bu ay boyunca Lidia platformunda fonksiyonellik ve kullanıcı deneyimini
  iyileştiren en son güncellemeleri ve geliştirmeleri keşfedin.
cover: ../../../.gitbook/assets/7 (3).png
coverY: 0
---

# Lidia 2.3.x sürüm notları

Bu ayki sürüm, Lidia platformunun çeşitli bileşenlerinde önemli güncellemeler içeriyor. Bu bileşenler arasında **Console, Merchant Console, Ürün Bilgi Yönetimi (PIM) sistemleri** bulunuyor. Yapılan iyileştirmeler, iş akışlarını optimize etmeyi ve tüm platform kullanıcıları için daha akıcı bir deneyim sunmayı amaçlıyor.

{% hint style="info" %}
🔎 **Sürüm Kodları Hakkında**\
Bu dokümanda, Lidia platformunun farklı bileşenleri için sürüm kodlarını bulabilirsiniz:

* **LC:** Lidia Console – Ana yönetim konsoluna yönelik iyileştirmeler ve hata düzeltmeleri.
* **LMC:** Lidia Merchant Console – Satıcı araçları ve iş akışlarına özel güncellemeler.
* **LP:** Lidia PIM (Ürün Bilgi Yönetimi) – Ürün veri yönetimiyle ilgili geliştirmeler ve yeni özellikler.

Bu kodlar, platform genelindeki iyileştirmelerin hangi alanlara yönelik olduğunu takip etmenize yardımcı olur.
{% endhint %}

***

## <mark style="color:purple;">**Sürüm 2.3.1 - 4 Mart 2025**</mark>

### Yeni Geliştirmeler

### 🎯 **Lojistik Yönetimi Geliştirmeleri**

#### **MNG Kargo - Hizmet sağlayıcısı entegrasyonu** Sürüm Tarihi: 04/03/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.3.1.1 - LMC-2.3.1.1</mark>

Lidia lojistik hizmet sağlayıcıları arasında MNG Kargo mevcuttu fakat entegrasyonu güncel değildi. Bu geliştirme ile MNG Kargo entegrasyonu son hali ile güncellendi ve siparişler otomatik olarak aktarılabilir hale getirildi. Bu sayede satış yapan e-ticaret yöneticileri, MNG Kargo’yu teslimat profillerine ekleyebilir ve satıcılarının satış süreçlerinde pazaryeri anlaşmalı kargo olarak MNG Kargo'yu kullanmasını sağlayabilir.



### 🎯 **Sipariş Yönetimi Geliştirmeleri**

#### **Dışarı aktarma yeteneğinin eklenilmesi** Sürüm Tarihi: 04/03/2025 Sürüm Numarası: <mark style="color:purple;">LMC-2.3.1.2</mark>

Siparişler sayfasında siparişler listelenip görüntülenebiliyordu fakat seçili sipariş satırlarını dışarı aktarma özelliği mevcut değildi. Bu geliştirme ile seçili sipariş satırları, listelenen sütun bilgileri ile birlikte Excel formatında dışa aktarılabilir. Bu sayede belirli filtreler ile seçilen siparişler topluca seçilip dışarı aktarılabilir.

\


### İyileştirmeler

### 💡 **Sipariş Yönetimi İyileştirmeleri**

#### Eksik Fatura Bilgilendirmeleri Sürüm Tarihi: 04/03/2025 Sürüm Numarası: <mark style="color:purple;">LMC-2.3.1.3</mark>

Sipariş süreçlerinde fatura bilgileri eksik ise sistem tarafından herhangi bir uyarı verilmiyordu. Bu geliştirme ile eksik fatura bilgileri sistem tarafından kontrol edilerek kullanıcıya bildirim verilmeye başlandı. Bu sayede göndericiler eksik bilgileri tamamlayarak fatura süreçlerinde yaşanan hataları önleyebilmektedir.



#### Sipariş, Teslimat ve Talep Detayda Ürün Bilgilendirmeleri Sürüm Tarihi: 04/03/2025 Sürüm Numarası: <mark style="color:purple;">LMC-2.3.1.4</mark>

Sipariş detay sayfasında ürünlere ait barkod bilgisi mevcuttu fakat ürüne bağlı satıcı eşya kodu bilgisi mevcut değildi. Bu geliştirme ile sipariş, teslimat ve talep detaylarında ürünün hem barkodu hem de satıcı eşya kodu bilgileri eklenmiştir. Bu sayede göndericiler sipariş detaylarında ürünlere dair daha fazla bilgiye ulaşabilir.



## <mark style="color:purple;">**Sürüm 2.3.2 - 18 Mart 2025**</mark>

### Yeni Geliştirmeler

### 🎯 Raporlama ve dashboard yetenekleri

#### **Merchant Dashboard** Sürüm Tarihi: 18/03/2025 Sürüm Numarası: <mark style="color:purple;">LMC-2.3.2.1</mark>

Satıcılar sipariş ve satış verilerini sistem üzerinden takip edebiliyordu fakat özel bir dashboard bulunmuyordu. Bu geliştirme ile Merchant Dashboard oluşturularak satıcıların satış performanslarını görselleştirilmiş grafikler ile görüntüleyebilmesi sağlandı.&#x20;



### İyileştirmeler

### 💡 **Sipariş Yönetimi İyileştirmeleri**

#### Fatura yükleme modalında fatura numarası alanına karakter sınırı eklenilmesi Sürüm Tarihi: 18/03/2025 Sürüm Numarası: <mark style="color:purple;">LMC-2.3.2.2</mark>

Fatura yükleme sırasında fatura numarası alanına girilen karakter sayısı kontrol edilmediğinden veri tutarsızlıkları yaşanabiliyordu. Bu geliştirme ile fatura numarası alanına 16 karakterlik bir sınır eklenerek hatalı veri girişi önlendi. Bu sayede kullanıcılar, belirlenen sınır dahilinde fatura numarası girebilmekte ve fatura numarasında hatalı bilgi tutulması engellenmektedir.



#### Listeleme sayfalarında sütun değerlerinin kopyalanabilmesi Sürüm Tarihi: 18/03/2025 Sürüm Numarası: <mark style="color:purple;">LMC-2.3.2.3</mark>

Listeleme sayfalarında sütun değerleri yalnızca görüntülenebiliyor ancak doğrudan kopyalanamıyordu. Bu geliştirme ile listeleme sayfalarındaki sütun değerlerinin kopyalanabilmesi sağlandı. Bu sayede kullanıcılar, ilgili bilgileri hızlı ve pratik bir şekilde alıp farklı alanlarda kullanabilir.



### 💡 **Havuz Yönetimi İyileştirmeleri**

#### Havuzlara reddetme deneyimde açıklama alanının da eklenilmesi Sürüm Tarihi: 18/03/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.3.2.1</mark>

Havuzlarda reddetme işlemi sırasında yalnızca red nedenleri seçilebiliyordu ancak ek açıklama girme imkanı bulunmuyordu. Bu geliştirme ile red işlemi yapılırken hem red nedeni hem de açıklama girilebilecek hale getirildi. Bu sayede kullanıcılar, reddetme sebeplerini daha ayrıntılı ifade edebilir.





***

{% hint style="info" %}
### **Hata Düzeltmeleri**

* Lidia Merchant Console'da dışarı aktarılan envanter verileri düzenlendi.
{% endhint %}





Bu güncellemeler, Lidia ürün ailesinin gelişimini hızlandırmak, pazar ve müşteri ihtiyaçlarına uyum sağlamak ve sürdürülebilirliği artırmak için tasarlanmıştır. Tüm kullanıcılar için daha sorunsuz ve verimli bir deneyim sunmayı hedefliyoruz. Gelecek ay daha fazlası için bizi takip etmeye devam edin!



\
\
