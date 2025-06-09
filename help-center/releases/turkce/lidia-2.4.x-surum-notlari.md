---
description: >-
  Bu ay boyunca Lidia platformunda fonksiyonellik ve kullanıcı deneyimini
  iyileştiren en son güncellemeleri ve geliştirmeleri keşfedin.
cover: ../../../.gitbook/assets/2 (3).png
coverY: 0
---

# Lidia 2.4.x sürüm notları

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

## <mark style="color:purple;">**Sürüm 2.4**</mark>

### Yeni Geliştirmeler

### 🎯 **Lojistik Yönetimi Geliştirmeleri**

#### **Adet bazında teslimat yaratma ve iptal etme yeteneğinin geliştirilmesi** Sürüm Tarihi: 08/04/2025 Sürüm Numarası: <mark style="color:purple;">LMC-2.4.1.1</mark>

Teslimat yaratırken adet bazında kırılım fonksiyonel olarak yapılabiliyor olsa da Lidia Merchant Console üzerinden deneyimde  eksiklikler vardı. Bu geliştirme ile teslimat yaratma deneyiminin daha esnek bir şekilde yönetilebilmesi amacıyla teslimat yaratma ve iptal etme işlemlerinde adet bazlı yönetme deneyimi geliştirilmiştir. Bu kapsamda:

* Sipariş içerisindeki ürünler için parça parça teslimat oluşturulabilir hale gelmiştir.
* Sipariş içinde ürünler yine adet bazında seçilerek iptal edilebilmektedir. İptal nedeni ve açıklaması zorunlu alandır, kayıt altına alınır.
* Geliştirme, özellikle büyük hacimli ve çok ürünlü siparişlerde daha etkin sevkiyat planlaması sağlamayı hedeflemektedir.

Bu geliştirme ile birlikte manuel müdahale gerektiren senaryoların azaltılması ve teslimat süreçlerinde kontrol esnekliğinin artırılması sağlanmıştır.



### 🎯 **Sipariş Yönetimi Geliştirmeleri**

#### **Vade farkı bilgisinin kaldırılması** Sürüm Tarihi: 08/04/2025 Sürüm Numarası: <mark style="color:purple;">LMC-2.4.1.2</mark>

Sipariş detaylarında yer alan ancak operasyonel süreçlerde kullanılmayan **vade farkı bilgisi**, kullanıcılar için kafa karışıklığı yarattığı ve iş akışlarına katkı sağlamadığı nedeniyle sipariş hesap dokümü bölümünden kaldırılmıştır.





### 🎯 **Hedef Yönetimi Geliştirmeleri**

#### **Hedef saat ve tarih aralığının seçilebilmesi** Sürüm Tarihi: 15/04/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.4.1.5</mark>

Hedef tanımlama süreçlerinde yalnızca gün ve saat bazlı seçim yapılabiliyor, saat bazında detaylı bir planlama mümkün olamıyordu. Bu geliştirme ile birlikte, kullanıcıların hedefleri saat ve tarih aralığına göre daha hassas bir şekilde tanımlayabilmesi sağlanmıştır.&#x20;





### İyileştirmeler

### 💡 **Sipariş Yönetimi İyileştirmeleri**

#### Aynı siparişteki farklı teslimatların takibinin kolaylaştırılması Sürüm Tarihi: 08/04/2025 Sürüm Numarası: <mark style="color:purple;">LMC-2.4.1.3 - LC-2.4.1.6</mark>

Bir siparişe ait birden fazla teslimatın oluşturulabildiği senaryolarda, teslimatların takibi kullanıcılar açısından karmaşık hale gelebiliyordu. Bu iyileştirme ile birlikte aynı sipariş içerisindeki farklı teslimatların daha kolay izlenebilmesini sağlayacak arayüz ve deneyim güncellemeleri yapılmıştır. Bu geliştirme ile sipariş detay ekranına gelen kullanıcılar, aynı siparişe ait diğer teslimatları gruplu şekilde görüntüleyebilir,  her teslimatın ön bilgisi (örneğin: tarih, durum, ürün adedi) kolayca görülebilir ve kullanıcı, ilgilendiği teslimatın detayına hızlıca yönlendirilerek süreç takibini daha verimli bir şekilde gerçekleştirebilir.





### 💡 **Kullanıcı Deneyimi İyileştirmeleri**

#### Breadcrumbs navigasyonunun tüm sayfalara eklenilmesi Sürüm Tarihi: 08/04/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.4.1.1</mark>

Kullanıcıların bulundukları sayfanın hiyerarşik konumunu daha net bir şekilde görebilmesi ve platform içerisinde daha kolay yönlenebilmesi amacıyla, tüm sayfalara breadcrumbs (iz navigasyonu) yapısı eklenmiştir.



### 💡 **Katalog Yönetimi İyileştirmeleri**

#### Özel listeye ürün eklerken hata için validasyon ekranlarının düzenlenmesi Sürüm Tarihi: 08/04/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.4.1.2</mark>

Özel listeye ürün ekleme sürecinde kullanıcıların karşılaştığı hata mesajları ve doğrulama ekranları, yeterince bilgi içermediği  için kullanıcı deneyimini olumsuz etkileyebiliyordu. Bu iyileştirme ile birlikte, özel liste işlemleri sırasında oluşan hatalar daha net başlıklar ve açıklamaları halinde görüntülenebilmektedir.&#x20;



### 💡 **Talep Yönetimi İyileştirmeleri**

#### Teslim edilen birden fazla ürün için adet bazında iade yaratma deneyiminin kontrol edilmesi Sürüm Tarihi: 15/04/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.4.1.3</mark>

Teslimatı tamamlanmış birden fazla ürün içeren siparişlerde, adet bazında iade yaratma sürecinde adet seçiminde hata alınabiliyordu.  Bu geliştirme ile kullanıcılar, iade sürecinde hangi ürünlerin kaç adeti için iade açtığını daha net görebilir ve sistem tarafından yönlendirilen hatasız bir işlem akışı ile iade oluşturabilir.&#x20;



#### İade onay ve red deneyiminin iyileştirilmesi Sürüm Tarihi: 15/04/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.4.1.4</mark>

İade taleplerinin onaylanması veya reddedilmesi sürecinde kullanıcıların karşılaştığı yönlendirme eksiklikleri, işlem adımlarının anlaşılmasını zorlaştırabiliyordu. Bu iyileştirme ile birlikte, iade sürecinin onay ve red adımlarına yönelik arayüz ve deneyim güncellemeleri yapılmıştır.





***

{% hint style="info" %}
### **Hata Düzeltmeleri**

* Teslimatlarda kargo takip kodunun yansımaması&#x20;
* Merchant Console'daki iptal siparişlerin gösterim hataları
{% endhint %}





Bu güncellemeler, Lidia ürün ailesinin gelişimini hızlandırmak, pazar ve müşteri ihtiyaçlarına uyum sağlamak ve sürdürülebilirliği artırmak için tasarlanmıştır. Tüm kullanıcılar için daha sorunsuz ve verimli bir deneyim sunmayı hedefliyoruz. Gelecek ay daha fazlası için bizi takip etmeye devam edin!



\
\
