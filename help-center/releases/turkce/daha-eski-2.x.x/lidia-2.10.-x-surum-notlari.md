---
description: >-
  Bu ay boyunca Lidia platformunda fonksiyonellik ve kullanıcı deneyimini
  iyileştiren en son güncellemeleri ve geliştirmeleri keşfedin.
cover: ../../../../.gitbook/assets/2 (1).png
coverY: 0
---

# Lidia 2.10. x sürüm notları

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

## <mark style="color:purple;">**Sürüm 2.10**</mark>

### Yeni Geliştirmeler



### 🎯 Katalog **Yönetimi Geliştirmeleri**

#### Öne çıkan filtre ekleyebilme yeteneği ve filtre yönetimi deneyim iyileştirme çalışmaları Sürüm Tarihi: 23/10/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.10.1</mark>

Kategori, marka, özel liste ve satıcı detay sayfalarında yer alan filtre yönetimi modülü üzerinden filtreler ve seçenekler yönetilebiliyordu.\
Bu geliştirme ile birlikte filtre yönetimi sekmesindeki yapı daha kompakt bir arayüze taşınmış, ayrıca “öne çıkan filtre” tanımlama yeteneği eklenmiştir. Kullanıcılar, mevcut filtreler arasından öne çıkarılmasını istedikleri filtreleri artık öne çıkan filtreler alanında select aracılığıyla kolayca belirleyebilir. Bu sayede filtre yönetim süreci hem daha düzenli hale getirilmiş hem de sık kullanılan filtrelerin erişimi hızlandırılmıştır.



#### Ürün ve varyant detaylarına barkod bilgisinin eklenilmesi Sürüm Tarihi: 23/10/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.10.2</mark>

Ürün ve varyant detay ekranlarında grup kodu ve barkod bilgisi bulunmadığı için bilgi bütünlüğü eksik kalıyordu.Bu geliştirme ile ürün detaylarına grup kodu ve barkod alanları, varyant detaylarına ise grup kodu ve varyant kodu eklenmiştir<br>



### 🎯 Platform Altyapı **Geliştirmeleri**

#### Core framework dönüşümü Sürüm Tarihi: 23/10/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.10.3</mark>

Lidia platformunun ölçeklenebilirliğini artırmak, modüler yapıyı standartlaştırmak ve tüm bileşenlerin performansını optimize etmek amacıyla kapsamlı bir Core dönüşüm süreci tamamlanmıştır.\
Bu dönüşümle birlikte platformun temel çalışma mimarisi yeniden yapılandırılmış, servisler arası iletişim ve veri işleme süreçleri Lidia Core altyapısına taşınmıştır. Yeni yapı; daha yüksek işlem hızı, geliştirme ortamında bağımsız modül dağıtımı ve sürüm yönetiminde esneklik sağlayarak gelecek dönem geliştirmelerinin daha kararlı bir temel üzerinde ilerlemesine olanak tanır.



### 🎯 Medya Yönetimi **Geliştirmeleri**

#### Medya yöneticisinin yeni uygulama ile değiştirilmesi Sürüm Tarihi: 23/10/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.10.4</mark>

Önceki medya yöneticisi uygulamasında zaman zaman kararlılık ve performans sorunları yaşanıyordu.\
Bu geliştirme kapsamında, mevcut medya yöneticisi daha modern ve stabil bir plugin ile değiştirilmiştir.



### 🎯 Kampanya Yönetimi **Geliştirmeleri**

#### Toplu kupon tanımlarken müşteri bilgisi ile eşleştirilmesi Sürüm Tarihi: 23/10/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.10.5</mark>

Excel üzerinden toplu kupon kodu tanımlanırken müşteri ID bilgisiyle eşleştirme yapılamadığı için tanımlanan kuponlar doğrudan müşterilere atanamıyordu. Bu geliştirme ile toplu kupon tanımlama Excel formatına “Müşteri ID” sütunu eklenmiştir. Artık kullanıcılar Excel içeriğine müşteri ID bilgisini girerek kuponları ilgili müşterilerle doğrudan eşleştirebilir. Dosya sisteme aktarıldığında, belirtilen müşteri ID’leri sistemde tanımlı müşterilerle otomatik olarak eşleşir ve kupon kodları listede görüntülenir.



#### Sepet kampanyalarında ödeme kanalının bir koşul olarak tanımlanabilmesi Sürüm Tarihi: 23/10/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.10.6</mark>

Önceki sürümlerde satın alma veya sepet kampanyalarında ödeme kanalına göre ödül tanımlama özelliği bulunmuyordu. Bu geliştirme ile yöneticiler, kampanya oluştururken seçtikleri ödeme kanallarını koşul olarak belirleyebilir ve bu kanallara özel indirimler tanımlayabilir hale gelmiştir. Böylece müşteriler, seçtikleri ödeme yöntemine göre sepetlerindeki ürünlerde geçerli olan indirimli tutar üzerinden ödeme gerçekleştirebilir.





### 🎯 Satıcı Yönetimi **Geliştirmeleri**

#### Satıcıların merkezileştirilmesi ve farklı satıcı türlerinin de kayıt edilebilmesi Sürüm Tarihi: 23/10/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.10.7</mark>

Lidia Console’daki satıcı kayıt süreci yalnızca fiziksel satıcılar üzerinden yürütülüyordu. Bu geliştirme ile satıcı ekleme deneyimi yeniden yapılandırılmış, kayıt adımlarında satıcı katalog türü bilgisi alınarak satıcıdan talep edilecek alanlar konfigüre edilebilir hale getirilmiştir.\
Artık dijital, dijital & fiziksel veya yalnızca fiziksel satıcı türleri sisteme tanımlanabilir. Ayrıca sol menüde yer alan satıcı listesi ve başvuru alanları yeniden düzenlenmiş, “Başvurular” ve “Satıcı Listesi” sekmeleri ayrı tab’ler olarak ayrıştırılmıştır. Başvurular doğrudan kullanıcı arayüzü (UI) üzerinden alınabildiği için, manuel başvuru ekleme deneyimi kaldırılmıştır.



### 🎯 Teslimat Yönetimi **Geliştirmeleri**

#### Teslimat listelemenin zenginleştirilmesi Sürüm Tarihi: 23/10/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.10.8</mark>

Teslimat listeleme sayfalarında yalnızca temel sipariş bilgileri ve teslimat numaraları görüntülenebiliyor, detaylı bilgilere erişmek için kullanıcıların teslimat detay ekranına gitmeleri gerekiyordu. Bu geliştirme ile teslimat listeleme ekranı genişletilerek, her teslimata ait ürün bilgileri, takip numarası, gönderici ve alıcı bilgileri, teslimat tarihleri ve kargo profili gibi bilgiler doğrudan listede görüntülenebilir hale getirilmiştir.\
Ayrıca yeni eklenen “Hızlı Görüntüle” butonu sayesinde kullanıcılar, teslimat kartı üzerinden tıklama ile detaylı bilgileri drawer yapısında ön izleme olarak görüntüleyebilir veya isterlerse detay sayfasına yönlenebilir.





### İyileştirmeler

### 💡 **Güvenlik İyileştirmeleri**

#### Şifremi hatırla butonunun kaldırılması ve şifre politikalarının değiştirilmesi Sürüm Tarihi: 23/10/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.10.9</mark>

Bu geliştirme kapsamında kullanıcı hesap güvenliğini artırmak amacıyla “Şifremi hatırla” özelliği kaldırılmış ve platform genelinde güçlü parola politikaları devreye alınmıştır. Artık şifreler en az 11 karakter uzunluğunda olacak şekilde, en az bir büyük harf, bir küçük harf, bir rakam ve bir özel karakter içerecek biçimde oluşturulmalıdır. Şifreler belirli aralıklarla periyodik olarak değiştirilir; bu süre varsayılan olarak 60 gün olarak tanımlanmış olup, sistem tarafından konfigüre edilebilir. Ayrıca son beş şifrenin yeniden kullanılması engellenmiş, üç başarısız giriş denemesi sonrasında hesabın geçici olarak 15 dakika kilitlenmesi kuralı eklenmiştir.



### 💡 **Kullanıcı Deneyimi İyileştirmeleri**

#### Tüm sayfaların yeni listeleme arayüzüne taşınması Sürüm Tarihi: 23/10/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.10.10</mark>

Bu geliştirme kapsamında, platform genelindeki tüm listeleme sayfaları yeni listeleme arayüzü altyapısına taşınmıştır.





***

{% hint style="info" %}
### **Hata Düzeltmeleri**

* Core dönüşümünden kaynaklı Console stabilizasyonu için çeşitli hatalar giderilmiştir.
{% endhint %}





Bu güncellemeler, Lidia ürün ailesinin gelişimini hızlandırmak, pazar ve müşteri ihtiyaçlarına uyum sağlamak ve sürdürülebilirliği artırmak için tasarlanmıştır. Tüm kullanıcılar için daha sorunsuz ve verimli bir deneyim sunmayı hedefliyoruz. Gelecek ay daha fazlası için bizi takip etmeye devam edin!



\
<br>
