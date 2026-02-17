---
description: >-
  Bu ay boyunca Lidia platformunda fonksiyonellik ve kullanıcı deneyimini
  iyileştiren en son güncellemeleri ve geliştirmeleri keşfedin.
cover: ../../../.gitbook/assets/1 (1).png
coverY: 0
---

# Lidia 3.1.x sürüm notları

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

## <mark style="color:purple;">**Sürüm 3.1**</mark>

### Yeni Geliştirmeler

### 🎯 Platform Altyapı **Geliştirmeleri**

#### Core framework dönüşümü Sürüm Tarihi: 27/01/2026 Sürüm Numarası: <mark style="color:purple;">LMC-3.1.1</mark>

Lidia platformunun ölçeklenebilirliğini artırmak, modüler yapıyı standartlaştırmak ve tüm bileşenlerin performansını optimize etmek amacıyla kapsamlı bir Core dönüşüm süreci tamamlanmıştır.\
Bu dönüşümle birlikte platformun temel çalışma mimarisi yeniden yapılandırılmış, servisler arası iletişim ve veri işleme süreçleri Lidia Core altyapısına taşınmıştır. Yeni yapıda Lidia Merchant Console; daha yüksek işlem hızı, geliştirme ortamında bağımsız modül dağıtımı ve sürüm yönetiminde esneklik sağlayarak gelecek dönem geliştirmelerinin daha kararlı bir temel üzerinde ilerlemesine olanak tanır.



### 🎯 Katalog **Yönetimi Geliştirmeleri**

#### Varyant taşıma yeteneği Sürüm Tarihi: 27/01/2026 Sürüm Numarası: <mark style="color:purple;">LC-3.1.1</mark>

Bu geliştirme ile birlikte ürünlere ait varyantların farklı katalog yapıları veya havuzlar arasında taşınabilmesi desteklenmiştir. Lidia Console yöneticileri, mevcut varyant yapılarını yeniden oluşturmaya gerek kalmadan, ilgili varyantları hedef kataloğa güvenli ve kontrollü bir şekilde aktarabilir. Taşıma işlemi, Lidia Console’da varyant detaylarında yer alan ürün kodu değiştirme ekranları üzerinden adım adım gerçekleştirilir; bu sayede seçilen varyant, başka bir ürün kodu altında konumlandırılarak katalog yapısı bozulmadan yönetilebilir.



#### Varyant güncellemelerini havuza geri besleme yeteneği Sürüm Tarihi: 27/01/2026 Sürüm Numarası: <mark style="color:purple;">LC-3.1.2</mark>

Bu geliştirme ile varyant bazında yapılan güncellemelerin, ilgili veri havuzuna geri beslenmesi sağlanmıştır. Lidia Console’da varyant detaylarında yer alan havuzu geri besleme butonu üzerinden işlem tetiklenebilir; kısa süre içerisinde yapılan değişiklikler ilgili havuz verisine yansıtılır.\
Bu sayede farklı kaynaklardan veya ekranlar üzerinden yapılan güncellemelerin havuz verisiyle senkron kalması mümkün hale gelmiş, veri tutarsızlıklarının önüne geçilmiştir. Kullanıcılar, tüm süreçlerde güncel ürün ve varyant bilgilerine tekil ve güvenilir bir veri kaynağı üzerinden erişebilir.





### 🎯 Medya Yönetimi **Geliştirmeleri**

#### Medya yöneticisinin yeni uygulama ile değiştirilmesi Sürüm Tarihi: 05/01/2026 - 27/01/2026 Sürüm Numarası: <mark style="color:purple;">LP-3.1.1 - LMC-3.1.2</mark>

Önceki medya yöneticisi uygulamasında zaman zaman kararlılık ve performans sorunları yaşanıyordu.\
Bu geliştirme kapsamında, mevcut medya yöneticisi daha modern ve stabil bir plugin ile değiştirilmiştir.



### 🎯 Satıcı Yönetimi **Geliştirmeleri**

#### Satıcı yönetimi onaylama ve reddetme yetenekleri Sürüm Tarihi: 27/01/2026 Sürüm Numarası: <mark style="color:purple;">LC-3.1.3</mark>

Bu geliştirme ile satıcı yönetimi süreçlerine onaylama ve reddetme adımları eklenmiştir.\
Lidia Console yöneticileri, satıcı başvurularını kontrol ederek onaylayabilir veya gerekçesiyle birlikte reddedebilir. Bu iyileştirme sayesinde satıcı onboarding süreçleri daha kontrollü, izlenebilir ve standart bir yapıya kavuşturulmuştur.





### 🎯 Teslimat Yönetimi **Geliştirmeleri**

#### Teslimat taşıma belgesinin sticker olarak çıkartılabilmesi Sürüm Tarihi: 27/01/2026 Sürüm Numarası: <mark style="color:purple;">LMC-3.1.3</mark>

Bu geliştirme ile teslimatlara ait taşıma belgelerinin sticker formatında çıktı alınabilmesi sağlanmıştır.\
Bu sayede depo ve lojistik operasyonlarında paketleme süreçleri hızlandırılmış, taşıma belgelerinin fiziksel olarak ürünlere eklenmesi daha pratik hale getirilmiştir. Özellikle yüksek hacimli gönderimlerde operasyonel verimlilik artırılmıştır.





### İyileştirmeler

### 💡 **Satıcı Yönetimi İyileştirmeleri**

#### Satıcı yönetimi listeleme iyileştirmeleri Sürüm Tarihi: 27/01/2026 Sürüm Numarası: <mark style="color:purple;">LC-3.1.4</mark>

Bu iyileştirme ile satıcı yönetimi listeleme ekranında, satıcı ekleme sürecinin hangi adımda kaldığına dair durum bilgisi eklenmiştir. Daha önce listeleme ekranında satıcıların onboarding sürecindeki ilerleme durumu görüntülenemediğinden, kullanıcılar süreç takibinde ek aksiyonlar almak zorunda kalıyordu. Yapılan bu iyileştirme sayesinde platform yöneticileri, satıcıların ekleme ve onay süreçlerinde hangi aşamada bulunduğunu doğrudan listeleme üzerinden izleyebilir ve satıcı yönetimi operasyonlarını daha şeffaf ve kontrollü bir şekilde yürütebilir.



### 💡 **Kullanıcı Deneyimi İyileştirmeleri**

#### Tüm sayfaların yeni listeleme arayüzüne taşınması Sürüm Tarihi: 05/01/2026 - 27/01/2026 Sürüm Numarası: <mark style="color:purple;">LP-3.1.2 - LMC-3.1.4</mark>

Bu geliştirme kapsamında, Lidia PIM ve Lidia Merchant Console genelindeki tüm listeleme sayfaları yeni listeleme arayüzü altyapısına taşınmıştır.



#### Envanter listelemede fiyat aralığına göre filtreleme yeteneğinin eklenilmesi Sürüm Tarihi: 27/01/2026 Sürüm Numarası: <mark style="color:purple;">LC-3.1.5</mark>

Bu iyileştirme ile Lidia Console'daki envanter listeleme ekranına fiyat aralığına göre filtreleme yeteneği eklenmiştir. Kullanıcılar, belirledikleri minimum ve maksimum fiyat değerlerine göre ürünleri kolayca filtreleyerek ilgili envantere daha hızlı ulaşabilir. Bu geliştirme, özellikle geniş ürün listelerinde arama ve yönetim süreçlerini önemli ölçüde hızlandırır.



#### Ödeme kurallarında yeni koşul seçeneklerinin eklenilmesi Sürüm Tarihi: 27/01/2026 Sürüm Numarası: <mark style="color:purple;">LC-3.1.6</mark>

Bu geliştirme ile ödeme kuralları tanımlanırken kullanılabilecek koşul seçenekleri genişletilmiştir.\
Ödeme kuralı oluşturma sürecine ürün ve varyant bazlı koşul tanımlama yetenekleri eklenmiştir.\
Ayrıca ödeme kurallarında daha önce zorunlu olan kategori seçimi kaldırılmış, koşul alanı çoklu seçimi destekleyecek şekilde güncellenmiştir. Bu sayede platform yöneticileri, ödeme kurallarını ürün, varyant ve birden fazla kategori bazında daha esnek ve hedefli kurgulayabilir.



***

{% hint style="info" %}
### **Hata Düzeltmeleri**

* Core dönüşümünden kaynaklı PIM ve Merchant Console stabilizasyonu için çeşitli hatalar giderilmiştir.
{% endhint %}





Bu güncellemeler, Lidia ürün ailesinin gelişimini hızlandırmak, pazar ve müşteri ihtiyaçlarına uyum sağlamak ve sürdürülebilirliği artırmak için tasarlanmıştır. Tüm kullanıcılar için daha sorunsuz ve verimli bir deneyim sunmayı hedefliyoruz. Gelecek ay daha fazlası için bizi takip etmeye devam edin!



\
<br>
