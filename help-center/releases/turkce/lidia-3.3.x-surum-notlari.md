---
description: >-
  Bu ay boyunca Lidia platformunda fonksiyonellik ve kullanıcı deneyimini
  iyileştiren en son güncellemeleri ve geliştirmeleri keşfedin.
---

# Lidia 3.3.x sürüm notları

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



## <mark style="color:purple;">**Sürüm 3.2**</mark>

### Yeni Geliştirmeler

### 🎯 Ürün Varyant Yönetimi Geliştirmeleri

#### Varyant İlişkisi Güncelleme Yeteneği ve Havuz Senkronizasyon Sürüm Tarihi: 11/03/2026 Sürüm Numarası: <mark style="color:purple;">LP-3.3.1</mark>

Bu geliştirme kapsamında Lidia PIM’de yayınlanmış ürünlere ait varyant ilişkilerinin daha esnek şekilde yönetilebilmesi sağlanmıştır.\
Daha önce değiştirilemeyen Grup Kodu / Ürün Kodu alanı artık varyant detayı üzerinden güncellenebilir hale getirilmiştir. Böylece yanlış ürün grubuna bağlı varyantlar doğru ürün altında yeniden konumlandırılabilmektedir.

Ayrıca varyant detayında yapılan değişikliklerin havuz verisi ile senkron kalmasını sağlamak amacıyla “Verilerle Havuzu Geri Besle” aksiyonu eklenmiştir. Bu aksiyon sayesinde yapılan güncellemeler kontrollü şekilde ürün havuzuna yansıtılabilmektedir.





### İyileştirmeler

### 💡 Havuz Yönetimi İyileştirmeleri

#### Havuz yayınlama doğrulama deneyimi iyileştirmesi Sürüm Tarihi: 11/03/2026 Sürüm Numarası: <mark style="color:purple;">LP-3.2.4</mark>

Bu geliştirme kapsamında Lidia PIM havuz ekranında ürün yayınlama süreci daha şeffaf ve yönlendirici hale getirilmiştir.\
Yayınlama işlemi öncesinde sistem tarafından otomatik doğrulama çalıştırılarak yayınlanabilir ve yayınlanamaz ürün sayıları kullanıcıya açık şekilde gösterilmektedir.\
Yayınlanamayan ürünler için neden bazlı açıklamalar sunulmakta ve kullanıcıya tam yayınlama, kısmi yayınlama veya eksik bilgileri tamamlayarak tekrar deneme seçenekleri sağlanmaktadır.

Bu iyileştirme ile birlikte kullanıcıların yayınlama sürecindeki hataları hızlı şekilde tespit etmesi ve operasyonu kesintiye uğratmadan yönetmesi hedeflenmiştir.





***

{% hint style="info" %}
### **Hata Düzeltmeleri**

* Core dönüşümünden kaynaklı PIM ve Merchant Console stabilizasyonu için çeşitli hatalar giderilmiştir.
{% endhint %}



Bu güncellemeler, Lidia ürün ailesinin gelişimini hızlandırmak, pazar ve müşteri ihtiyaçlarına uyum sağlamak ve sürdürülebilirliği artırmak için tasarlanmıştır. Tüm kullanıcılar için daha sorunsuz ve verimli bir deneyim sunmayı hedefliyoruz. Gelecek ay daha fazlası için bizi takip etmeye devam edin!
