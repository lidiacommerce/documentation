---
description: >-
  Bu ay boyunca Lidia platformunda fonksiyonellik ve kullanıcı deneyimini
  iyileştiren en son güncellemeleri ve geliştirmeleri keşfedin.
cover: ../../../.gitbook/assets/feb.png
coverY: 0
---

# Lidia 2.2.x sürüm notları

Bu ayki sürüm, Lidia platformunun çeşitli bileşenlerinde önemli güncellemeler içeriyor. Bu bileşenler arasında **Console, Merchant Console ve Ürün Bilgi Yönetimi (PIM) sistemleri** bulunuyor. Yapılan iyileştirmeler, iş akışlarını optimize etmeyi ve tüm platform kullanıcıları için daha akıcı bir deneyim sunmayı amaçlıyor.

{% hint style="info" %}
🔎 **Sürüm Kodları Hakkında**\
Bu dokümanda, Lidia platformunun farklı bileşenleri için sürüm kodlarını bulabilirsiniz:

* **LC:** Lidia Console – Ana yönetim konsoluna yönelik iyileştirmeler ve hata düzeltmeleri.
* **LMC:** Lidia Merchant Console – Satıcı araçları ve iş akışlarına özel güncellemeler.
* **LP:** Lidia PIM (Ürün Bilgi Yönetimi) – Ürün veri yönetimiyle ilgili geliştirmeler ve yeni özellikler.

Bu kodlar, platform genelindeki iyileştirmelerin hangi alanlara yönelik olduğunu takip etmenize yardımcı olur.
{% endhint %}

***

## **Sürüm 2.2.1 - 4 Şubat 2025**

### 🚀 **Hata Düzeltmeleri ve Fonksiyonel İyileştirmeler**

* Yeni eklenen değerlerin tüm seçeneklere dahil edilmemesi sorunu çözüldü.
* Şifre sıfırlama ve "Şifremi Unuttum" e-postalarının gönderilmemesi sorunu düzeltildi.
* Çözüm Merkezi sayfalarındaki giriş ekranı yönlendirme sorunu giderildi.
* "Şifremi Unuttum" yönlendirmelerinin giriş sayfasında eksik olması sorunu çözüldü.
* Satıcı detayları bölümündeki açılır menü görünümü düzeltildi.
* Ürün Envanteri Detayları'ndaki yanlış görüntülenme sorunu giderildi.
* Satıcı Detayları bölümüne filtre eklenememesi sorunu düzeltildi.
* İade kodunun e-posta ile gönderilmemesi sorunu çözüldü.
* Header menüsüne resim eklerken arama fonksiyonunun çalışmaması sorunu düzeltildi.
* Kategori filtre yönetiminde kategorilerin görünmemesi sorunu giderildi.
* Teslimat detaylarındaki kopyalama butonlarının çalışmaması sorunu düzeltildi.
* Filtrelere göre veri dışa aktarma sorunu çözüldü.
* Kullanıcıların yanlış şifre girildiğinde giriş ekranına yönlendirilmesi sorunu düzeltildi.
* Yeni eklenen değerlerin seçeneklerde hemen görüntülenmemesi sorunu giderildi.
* Teslimat profillerindeki tekrarlayan kayıt görünümü düzeltildi.

### 📈 **Satış Yönetimi İyileştirmeleri**

#### **Stopaj Uygulaması** Sürüm Tarihi: 02/04/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.2.1.1 - LMC-2.2.1.1</mark>

\
2025 yılı itibarıyla, e-ticaret işlemleri üzerinden aracılık hizmeti sağlayan platformların, satıcılara yapılan ödemelerden %1'lik bir stopaj kesintisi yapması gerekmektedir. Bu güncelleme ile, kesilen stopaj bilgisi platform genelinde net bir şekilde görüntülenmektedir.\
**Uygulanan Değişiklikler:**

* **Sipariş Detayları Sayfası**: Stopaj kesintisi, sipariş özeti kısmında açıkça gösterilmektedir.
* **Maliyet Tablosu (Satış Yönetimi Ekranı)**: Vergi kesintisi maliyet hesaplamalarına dahil edilmiştir.
* **Satış Raporları (Platform & Partner Panelleri)**: Stopaj kesintisi, dışa aktarılabilir (Excel) rapor formatlarına tam olarak dahil edilmiştir.
* **Operasyon, Maliyet ve Kampanya Raporları**: Stopaj kesintisi ve net ödeme detayları kapsamlı bir şekilde gösterilmektedir.

### 🌟 **Kullanıcı Deneyimi İyileştirmeleri**

#### **Özel Hata Sayfaları Uygulaması** Sürüm Tarihi: 02/04/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.2.1.2 - LMC-2.2.1.2</mark>

\
Bu sürümde, kullanıcı deneyimini içinyaygın hata sayfaları tasarlandı ve geliştirildi:

* **404 - Sayfa Bulunamadı**: Açık bir mesaj ve ana sayfaya veya önceki sayfaya dönmek için navigasyon seçenekleri içerir.
* **500 - Dahili Sunucu Hatası**: Anlamlı bir mesaj ve ana sayfaya veya önceki sayfaya yönlendirme seçenekleri sunar.
* **Oops!** : Genel bir hata sayfası, ana sayfaya veya önceki sayfaya yönlendirme seçenekleriyle.

<div><figure><img src="../../../.gitbook/assets/Master (6).png" alt=""><figcaption><p>Sunucu Hatası</p></figcaption></figure> <figure><img src="../../../.gitbook/assets/Master (5).png" alt=""><figcaption><p>500 Error</p></figcaption></figure> <figure><img src="../../../.gitbook/assets/Master (4).png" alt=""><figcaption><p>404 Error</p></figcaption></figure></div>

#### **Tarayıcı Sekmesi Yapısı İyileştirmeleri** Sürüm Tarihi: 02/04/2025 Sürüm Numarası: <mark style="color:purple;">LMC-2.2.1.3</mark>

Tarayıcı sekmesi yapısı, daha iyi bir navigasyon sağlamak amacıyla iyileştirilmiştir. Örneğin, sekme artık mevcut sayfayı ve ardından platform adını gösteriyor (örneğin, Home | Lidia Partner), bu da kullanıcıların platformdaki konumlarını daha kolay takip etmelerini sağlıyor.

### 🚚 **Teslimat Yönetimi Geliştirmeleri**

#### Gelişmiş Teslimat Hareketleri Sürüm Tarihi: 02/04/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.2.1.3 - LMC-2.2.1.4</mark>

Gönderi hareket bilgileri sisteme dahil edilerek, kullanıcıların daha ayrıntılı takip yapabilmesi sağlanmıştır.

* **Ayrıntılı Gönderi Durum Bilgisi**: Daha açıklayıcı durum güncellemeleri eklenmiştir.
* **Durum Zaman Damgası**: Her durum güncellemesinin tam zamanı artık görüntülenmektedir.
* **Son İşlem Yapılan Konum**: Gönderinin işlendiği son konum artık sisteme dahil edilmiştir.

***

## **Sürüm 2.2.2 - 18 Şubat 2025**

### 🚀 **Hata Düzeltmeleri ve Fonksiyonel İyileştirmeler**

* Tüm listelemelerde silinen öğelerin listelenmesi ile ilgili sorunlar giderildi.

### 📁 Katalog Yönetimi Geliştirmeleri

#### **İçerisinde Ürün Olan Kategorilerin Yönetimi** Sürüm Tarihi: 02/18/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.2.2.1</mark>

İçerisinde ürün olan bir kategori silinmek istendiğinde sistem buna izin vermemektedir. Bu durum kullanıcılar tarafından daha anlaşılır olması için; kategori silme işlemi sırasında eğer kategorinin içerisinde ürün varsa aşağıdaki görseldeki gibi uyarı modalı gösterilmesi sağlanmıştır.

<figure><img src="../../../.gitbook/assets/console.nevade.com_metadata_categories.png" alt=""><figcaption></figcaption></figure>

***

#### **Havuza Reddedilenler Alanının Eklenmesi** Sürüm Tarihi: 02/18/2025 Sürüm Numarası: <mark style="color:purple;">LMC-2.2.2.1</mark>

Ürün havuzu görünümüne "Reddedilenler" sekmesi eklendi. Satıcılar artık reddedilen ürünleri ayrı bir sekmede görüntüleyebilir.&#x20;



<figure><img src="../../../.gitbook/assets/partner.nevade.com_metadata_datapoolitems_5966.png" alt=""><figcaption></figcaption></figure>

***

Bu güncellemeler, Lidia Platformu'nun işlevselliğini ve kullanılabilirliğini artırmak için tasarlanmıştır ve tüm kullanıcılar için daha sorunsuz ve verimli bir deneyim sunmayı hedeflemektedir. Gelecek ay daha fazla iyileştirme için bizi izlemeye devam edin!



\
\
