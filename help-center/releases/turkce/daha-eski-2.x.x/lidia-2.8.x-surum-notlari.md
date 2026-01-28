---
description: >-
  Bu ay boyunca Lidia platformunda fonksiyonellik ve kullanıcı deneyimini
  iyileştiren en son güncellemeleri ve geliştirmeleri keşfedin.
cover: ../../../../.gitbook/assets/1 (8).png
coverY: 0
---

# Lidia 2.8.x sürüm notları

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

## <mark style="color:purple;">**Sürüm 2.8**</mark>

### Yeni Geliştirmeler

### 🎯 **Fatura Yönetimi Geliştirmeleri**

#### Yöneticilerin gönderici taraflı fatura yükleyebilmesi Sürüm Tarihi: 12/08/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.8.1.1 - LMC-2.8.1.1</mark>

Önceki süreçte faturalar yalnızca satıcılar tarafından sisteme yüklenebiliyordu. Bu geliştirme ile yöneticiler de gönderici taraflı iade faturalarını ilgili iade kodu ile yükleyebilir. Gönderici yöneticinin onun tarafına yüklediği iade faturalarını fatura merkezinde görüntüleyebilir.



#### Faturaların yükleyici ve taraf bilgileri ile filtrelenebilmesi Sürüm Tarihi: 12/08/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.8.1.2 - LMC-2.8.1.2</mark>

Fatura listelerinde, yüklemeyi yapan kişi ve fatura taraf bilgileri ile filtreleme yapılabilmesi sağlanmıştır. Bu geliştirme ile yöneticiler, faturaları yükleyen tarafı (ör. satıcı, yönetici) ve faturanın yüklendiği tarafı dikkate alarak daha hızlı ve doğru arama yapabilir.



#### Faturaların yüklendiği alan bilgilerinin listelemede görüntülenmesi ve erişilebilmesi Sürüm Tarihi: 12/08/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.8.1.3</mark>&#x20;

Listeleme ekranlarında faturaların hangi alan (ör. sipariş, iade) üzerinden yüklendiğine dair bilgi eklenmiştir. Bu sayede kullanıcılar, fatura kaynağına dair bilgilere doğrudan erişebilir ve kayıtların doğruluğunu daha kolay kontrol edebilir.





### 🎯 **Raporlama Geliştirmeleri**

#### Stopaj tahsilat raporunun yöneticiler tarafından alınabilmesi Sürüm Tarihi: 12/08/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.8.1.4</mark>

Bu geliştirme ile yöneticilerin, platformdaki satıcıların stopaj tahsilat bilgilerini içeren özet rapor ile tüm platform genelindeki stopaj kesintilerinin detaylı olarak takip edilebileceği raporu, doğrudan “Raporlar” başlığı altından alabilmesi sağlanmıştır.





### 🎯 **Ödeme Yönetimi Geliştirmeleri**



#### Peşinat tutarı belirleyerek ödeme kuralı tanımlanabilmesi Sürüm Tarihi: 12/08/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.8.1.5</mark>

Ödeme kuralları belirlerken kategori, marka, satıcı ve fiyat gibi koşullar tanımlanabiliyordu. Bu geliştirme ile ödeme kurallarında peşinat tutarı da koşul olarak tanımlanabilmektedir. Bu sayede yöneticiler, siparişlerde belirli bir miktarın ön ödeme olarak alınmasını zorunlu kılabilir.&#x20;





### 🎯 **Güvenlik Geliştirmeleri**



#### Çift faktörlü doğrulamanın aktifleştirilmesi Sürüm Tarihi: 12/08/2025 Sürüm Numarası: <mark style="color:purple;">LP-2.8.1.1</mark>

Lidia PIM'de, giriş güvenliğini artırmak amacıyla SMS yoluyla çift faktörlü doğrulama (MFA) aktifleştirilmiştir. Kullanıcılar, giriş yaparken kullanıcı adı ve şifre bilgilerini girdikten sonra cep telefonlarına gönderilen tek kullanımlık doğrulama kodunu girerek sisteme erişebilecektir.





### İyileştirmeler

### 💡 **Kullanıcı Deneyimi İyileştirmeleri**

#### İçeriklerin yeniden eskiye göre sıralanması Sürüm Tarihi: 12/08/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.8.1.6</mark>

İçerik listelerinde sıralama mantığı değiştirilerek, varsayılan olarak en yeni içeriklerin en üstte listelenmesi sağlanmıştır. Bu sayede kullanıcılar en güncel verilere daha hızlı ulaşabilir.













***

{% hint style="info" %}
### **Hata Düzeltmeleri**

* \-
{% endhint %}





Bu güncellemeler, Lidia ürün ailesinin gelişimini hızlandırmak, pazar ve müşteri ihtiyaçlarına uyum sağlamak ve sürdürülebilirliği artırmak için tasarlanmıştır. Tüm kullanıcılar için daha sorunsuz ve verimli bir deneyim sunmayı hedefliyoruz. Gelecek ay daha fazlası için bizi takip etmeye devam edin!



\
<br>
