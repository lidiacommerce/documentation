---
description: >-
  Bu ay boyunca Lidia platformunda fonksiyonellik ve kullanıcı deneyimini
  iyileştiren en son güncellemeleri ve geliştirmeleri keşfedin.
cover: ../../../.gitbook/assets/1.png
coverY: 0
---

# Lidia 3.2.x sürüm notları

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

### 🎯 Platform Altyapı **Geliştirmeleri**

#### Core framework dönüşümü Sürüm Tarihi: 17/02/2026 Sürüm Numarası: <mark style="color:purple;">LP-3.2.1</mark>

Lidia platformunun ölçeklenebilirliğini artırmak, modüler yapıyı standartlaştırmak ve tüm bileşenlerin performansını optimize etmek amacıyla kapsamlı bir Core dönüşüm süreci tamamlanmıştır.\
Bu dönüşümle birlikte platformun temel çalışma mimarisi yeniden yapılandırılmış, servisler arası iletişim ve veri işleme süreçleri Lidia Core altyapısına taşınmıştır. Yeni yapıda Lidia PIM; daha yüksek işlem hızı, geliştirme ortamında bağımsız modül dağıtımı ve sürüm yönetiminde esneklik sağlayarak gelecek dönem geliştirmelerinin daha kararlı bir temel üzerinde ilerlemesine olanak tanır.



### 🎯 Çoklu Dil **Geliştirmeleri**

#### Almanca uygulama dil desteğinin eklenilmesi Sürüm Tarihi: 17/02/2026 Sürüm Numarası: <mark style="color:purple;">LP-3.2.2</mark>

Bu geliştirme kapsamında Lidia PIM uygulamasına Almanca (DE) dil desteği eklenmiştir.\
Bu güncelleme ile birlikte uygulama artık İngilizce (EN), Türkçe (TR) ve Almanca (DE) olmak üzere üç dilde kullanılabilmektedir.





### İyileştirmeler

### 💡 **Güvenlik İyileştirmeleri**

#### Şifremi hatırla butonunun kaldırılması ve şifre politikalarının değiştirilmesi Sürüm Tarihi: 17/02/2026 Sürüm Numarası: <mark style="color:purple;">LMC-3.2.1</mark>

Bu geliştirme kapsamında kullanıcı hesap güvenliğini artırmak amacıyla “Şifremi hatırla” özelliği kaldırılmış ve platform genelinde güçlü parola politikaları devreye alınmıştır. Artık şifreler en az 11 karakter uzunluğunda olacak şekilde, en az bir büyük harf, bir küçük harf, bir rakam ve bir özel karakter içerecek biçimde oluşturulmalıdır. Şifreler belirli aralıklarla periyodik olarak değiştirilir; bu süre varsayılan olarak 60 gün olarak tanımlanmış olup, sistem tarafından konfigüre edilebilir. Ayrıca son beş şifrenin yeniden kullanılması engellenmiş, üç başarısız giriş denemesi sonrasında hesabın geçici olarak 15 dakika kilitlenmesi kuralı eklenmiştir.









***

{% hint style="info" %}
### **Hata Düzeltmeleri**

* Core dönüşümünden kaynaklı PIM ve Merchant Console stabilizasyonu için çeşitli hatalar giderilmiştir.
{% endhint %}





Bu güncellemeler, Lidia ürün ailesinin gelişimini hızlandırmak, pazar ve müşteri ihtiyaçlarına uyum sağlamak ve sürdürülebilirliği artırmak için tasarlanmıştır. Tüm kullanıcılar için daha sorunsuz ve verimli bir deneyim sunmayı hedefliyoruz. Gelecek ay daha fazlası için bizi takip etmeye devam edin!



\
<br>
