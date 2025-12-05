---
description: >-
  Bu ay boyunca Lidia platformunda fonksiyonellik ve kullanıcı deneyimini
  iyileştiren en son güncellemeleri ve geliştirmeleri keşfedin.
cover: ../../../.gitbook/assets/1 (5).png
coverY: 0
---

# Lidia 2.5.x sürüm notları

Bu ayki sürüm, Lidia platformunun çeşitli bileşenlerinde önemli güncellemeler içeriyor. Bu bileşenler arasında **Console, Merchant Console, Ürün Bilgi Yönetimi (PIM) sistemleri ve Lidia Commerce Engine**bulunuyor. Yapılan iyileştirmeler, iş akışlarını optimize etmeyi ve tüm platform kullanıcıları için daha akıcı bir deneyim sunmayı amaçlıyor.

{% hint style="info" %}
🔎 **Sürüm Kodları Hakkında**\
Bu dokümanda, Lidia platformunun farklı bileşenleri için sürüm kodlarını bulabilirsiniz:

* **LC:** Lidia Console – Ana yönetim konsoluna yönelik iyileştirmeler ve hata düzeltmeleri.
* **LMC:** Lidia Merchant Console – Satıcı araçları ve iş akışlarına özel güncellemeler.
* **LP:** Lidia PIM (Ürün Bilgi Yönetimi) – Ürün veri yönetimiyle ilgili geliştirmeler ve yeni özellikler.
* **LCE:** Lidia Commerce Engine - Lidia Commerce Engine'e eklenen mikroservis geliştirmeleri

Bu kodlar, platform genelindeki iyileştirmelerin hangi alanlara yönelik olduğunu takip etmenize yardımcı olur.
{% endhint %}

***

## <mark style="color:purple;">**Sürüm 2.5**</mark>

### Yeni Geliştirmeler

### 🎯 **Kupon Yönetimi Geliştirmeleri**

#### Birden fazla kategoriye bağlı kupon tanımlanabilmesi Sürüm Tarihi: 05/05/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.5.1.1</mark>

Daha önce yalnızca tek bir kategoriye bağlanabilen kuponlar, bu geliştirme ile birlikte birden fazla kategoriye eş zamanlı olarak tanımlanabilir hale getirilmiştir. Bu geliştirme ile kampanya kurgularının daha esnek yapılabilmesi sağlanmış, birden fazla kategoriye ait ürünlerde aynı kuponun geçerli olabilmesi mümkün hale getirilmiştir.



### 🎯 **Finans Yönetimi Geliştirmeleri**

#### Satıcı bazlı hakedişlerin hesaplanması ve gösterilmesi Sürüm Tarihi: 05/05/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.5.1.2</mark>

İlk olarak satıcıların belirlenen vade ve gün tercihine göre hakedişlerinin hesaplanması için şablonlar hazırlanmıştır ve ekipler arası iletişimler de sağlanarak bunların doğru hakedişe dahil edilen kırılımların doğru hesaplandığından emin olunmuştur. Bu geliştirme ile her bir satıcı için ayrı ayrı hesaplanan hakedişler console'da satıcı detayından görüntülenebilir. Hakediş dokümlerinde kesintilerin, kazançların detaylı kırılımları ve tutarları mevcuttur.



### 🎯 **Lojistik Yönetimi Geliştirmeleri**

#### **Hepsijet ve HepsiXL - Hizmet sağlayıcısı entegrasyonu** Sürüm Tarihi: 05/05/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.5.1.3</mark>

Lidia lojistik hizmet sağlayıcıları arasında Hepsijet ve HepsiXL entegrasyonu da mevcuttu fakat entegrasyonu güncel değildi. Bu geliştirme ile Hepsijet ve HepsiXL entegrasyonu son hali ile güncellendi ve siparişler otomatik olarak aktarılabilir hale getirildi. Bu sayede satış yapan e-ticaret yöneticileri, Hepsijet ve HepsiXL'ı  teslimat profillerine ekleyebilir ve satıcılarının satış süreçlerinde pazaryeri anlaşmalı kargo olarak Hepsijet ve HepsiXL entegrasyonunu kullanmasını sağlayabilir.



#### **MNG entegrasyonuna paket tipi bilgisinin de eklenilmesi** Sürüm Tarihi: 05/05/2025 Sürüm Numarası: <mark style="color:purple;">LCE-2.5.1.1</mark>

MNG Kargo entegrasyonunda, taşıma ve teslimat süreçlerinin daha doğru yönetilebilmesi amacıyla paket tipi bilgisi de entegrasyona eklenmiştir. Geliştirme, MNG kargonun gönderdiği, güncellenen entegrasyon dokümanlarına uygun şekilde gerçekleştirilmiştir.&#x20;



### 🎯 **Raporlama Geliştirmeleri**

#### Mikroservislerde audit log yapısının kurulması ve denetim raporlarının geliştirilmesi Sürüm Tarihi: 05/05/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.5.1.4 - LCE-2.5.1.2</mark>

Mikroservis mimarisi üzerinde gerçekleştirilen işlemlerin izlenebilirliğini artırmak amacıyla mevcut audit log yapısı üzerinde geliştirmeler yapılmıştır. Bu geliştirme ile organizasyon mikroservisi için gerçekleştirilen tüm aksiyonların audit log kayıtları tutulmakta; bu kayıtlar yalnızca yetkili rollere sahip kullanıcılar tarafından Lidia Console'daki denetim raporları ekranı üzerinden de görüntülenebilmektedir.



### 🎯 **Ürün Yönetimi Geliştirmeleri**

#### Ürün detay sayfalarının geliştirilmesi Sürüm Tarihi: 05/05/2025 Sürüm Numarası: <mark style="color:purple;">LMC-2.5.1.1</mark>

Lidia Merchant Console'da ürünler liste halinde detaylı şekilde görüntülenebilse de, her ürüne ait bir detay sayfası bulunmuyordu. Bu geliştirme ile birlikte ürünlerin detay sayfasına erişilebilir; satış, envanter, varyant ve medya gibi birçok bilgiye tekil ürün ekranları üzerinden ulaşılabilir.





### 🎯 **Talep Yönetimi Geliştirmeleri**



#### İade kodunun yenilenmesi yeteneği Sürüm Tarihi: 05/05/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.5.1.5</mark>

Bir iade talebi için iade barkod kodu oluşturulduktan sonra kodun süresi geçtiğinde yeni bir barkod kodu alınamıyordu. Bu durum, müşterilerin belirlenen süre içinde iadeyi teslim edememesi halinde süreci yönetmeyi zorlaştırıyordu. Bu geliştirme ile birlikte, iade barkod kodunun geçerlilik süresi dolduktan sonra yöneticiler talep detay ekranından yeni bir iade kodu üretebilirler. Böylece müşteri, iade teslimini zamanında gerçekleştiremezse, talebe bağlı olarak yönetici onun için yeni bir kod oluşturup müşteriye yeniden gönderebilir. Bu iyileştirme hem müşteri deneyimini artırmakta hem de iade sürecinde esneklik sağlamaktadır.

***



***

{% hint style="info" %}
### **Hata Düzeltmeleri**

* \-
{% endhint %}





Bu güncellemeler, Lidia ürün ailesinin gelişimini hızlandırmak, pazar ve müşteri ihtiyaçlarına uyum sağlamak ve sürdürülebilirliği artırmak için tasarlanmıştır. Tüm kullanıcılar için daha sorunsuz ve verimli bir deneyim sunmayı hedefliyoruz. Gelecek ay daha fazlası için bizi takip etmeye devam edin!



\
<br>
