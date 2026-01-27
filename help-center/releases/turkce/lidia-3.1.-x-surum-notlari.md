---
description: >-
  Bu ay boyunca Lidia platformunda fonksiyonellik ve kullanıcı deneyimini
  iyileştiren en son güncellemeleri ve geliştirmeleri keşfedin.
cover: ../../../.gitbook/assets/1.png
coverY: 0
---

# Lidia 3.1. x sürüm notları

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

{% hint style="info" %}
Eylül ayında planlanan sürüm geçişi, Lidia platformunun Core altyapı geçiş süreci nedeniyle ertelenmiştir. Bu kapsamda, Core geçişinin tamamlanmasının ardından Ekim ayında 2.10.x sürümü ile birlikte toplu deployment gerçekleştirilmiştir.
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





#### Ürün/Varyant güncellemelerini havuza geri besleme yeteneği Sürüm Tarihi: 27/01/2026 Sürüm Numarası: <mark style="color:purple;">LC-3.1.2</mark>







### 🎯 Medya Yönetimi **Geliştirmeleri**

#### Medya yöneticisinin yeni uygulama ile değiştirilmesi Sürüm Tarihi: 05/01/2026 - 27/01/2026 Sürüm Numarası: <mark style="color:purple;">LP-3.1.1 - LMC-3.1.2</mark>

Önceki medya yöneticisi uygulamasında zaman zaman kararlılık ve performans sorunları yaşanıyordu.\
Bu geliştirme kapsamında, mevcut medya yöneticisi daha modern ve stabil bir plugin ile değiştirilmiştir.



### 🎯 Satıcı Yönetimi **Geliştirmeleri**

#### Satıcı yönetimi onaylama ve reddetme yetenekleri Sürüm Tarihi: 27/01/2026 Sürüm Numarası: <mark style="color:purple;">LC-3.1.3</mark>







### 🎯 Teslimat Yönetimi **Geliştirmeleri**

#### Teslimat taşıma belgesinin sticker olarak çıkartılabilmesi Sürüm Tarihi: 27/01/2026 Sürüm Numarası: <mark style="color:purple;">LMC-3.1.3</mark>







### İyileştirmeler

### 💡 **Satıcı Yönetimi İyileştirmeleri**

#### Satıcı yönetimi listeleme iyileştirmeleri Sürüm Tarihi: 27/01/2026 Sürüm Numarası: <mark style="color:purple;">LC-3.1.4</mark>





### 💡 **Kullanıcı Deneyimi İyileştirmeleri**

#### Tüm sayfaların yeni listeleme arayüzüne taşınması Sürüm Tarihi: 05/01/2026 - 27/01/2026 Sürüm Numarası: <mark style="color:purple;">LP-3.1.2 - LMC-3.1.4</mark>

Bu geliştirme kapsamında, PIM genelindeki tüm listeleme sayfaları yeni listeleme arayüzü altyapısına taşınmıştır.



#### Envanter listelemede fiyat aralığına göre filtreleme yeteneğinin eklenilmesi Sürüm Tarihi: 27/01/2026 Sürüm Numarası: <mark style="color:purple;">LC-3.1.5</mark>





#### Ödeme kurallarında yeni koşul seçeneklerinin eklenilmesi Sürüm Tarihi: 27/01/2026 Sürüm Numarası: <mark style="color:purple;">LC-3.1.6</mark>





***

{% hint style="info" %}
### **Hata Düzeltmeleri**

* Core dönüşümünden kaynaklı Console stabilizasyonu için çeşitli hatalar giderilmiştir.
{% endhint %}





Bu güncellemeler, Lidia ürün ailesinin gelişimini hızlandırmak, pazar ve müşteri ihtiyaçlarına uyum sağlamak ve sürdürülebilirliği artırmak için tasarlanmıştır. Tüm kullanıcılar için daha sorunsuz ve verimli bir deneyim sunmayı hedefliyoruz. Gelecek ay daha fazlası için bizi takip etmeye devam edin!



\
<br>
