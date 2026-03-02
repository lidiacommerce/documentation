---
description: >-
  Lidia PIM’e hoş geldiniz. Bu rehber, ilk ürününüzü sisteme sorunsuz şekilde
  ekleyebilmeniz için gerekli temel adımlarda size yol göstermek amacıyla
  hazırlanmıştır.
---

# Quick Start Guide

Ürün ekleme süreci belirli bir kurulum sırasını takip eder. Bu rehberde ilerledikçe:

* ürün veri modelinizi hazırlayacak,
* gerekli özellik ve seçenekleri tanımlayacak,
* ürün havuzunuzu oluşturacak
* ve ürünlerinizi içeri aktaracaksınız.

En sorunsuz deneyim için adımları sırayla tamamlamanız önerilir.

{% hint style="info" %}
**Başlamadan önce**

Gerekli kullanıcı yetkilerine sahip olduğunuzdan emin olun.
{% endhint %}

## :rocket:<mark style="color:$primary;background-color:purple;">Veri modelinizi inşa edin</mark>

Lidia PIM’de ürünlerinizi sorunsuz yönetebilmek için ilk ve en kritik adım veri şemasını doğru şekilde kurgulamaktır. Doğru yapılandırılmış bir veri şeması, benzer ürünleri düzenli bir yapı altında toplar ve ürün verisinin kategori bazında kontrollü ve sürdürülebilir şekilde ilerlemesini sağlar.

#### :arrow\_forward: <mark style="color:$info;">Veri Şeması Nedir?</mark>

Veri şeması, ürünleriniz için hangi bilgilerin tutulacağını ve bu bilgilerin hangi kurallara göre yönetileceğini belirleyen temel veri modelidir.

Basitçe ifade etmek gerekirse veri şeması:

* ürün kartında hangi alanların görüneceğini belirler
* bu alanların veri tipini tanımlar
* hangi bilgilerin zorunlu olduğunu kontrol eder
* benzer ürünlerin aynı yapıda yönetilmesini sağlar

Veri şeması sayesinde ürünleriniz rastgele değil, tanımlı ve kontrol edilen bir yapı içinde ilerler.

> **Örneğin** benzer ürünler için her seferinde yeni alanlar tanımlayıp yeni kural setleri oluşturmak yerine, oluşturduğunuz televizyon veri şemasını hem televizyon hem de HD televizyon ürünleri için kullanabilirsiniz. İhtiyaç duyduğunuz durumlarda ise bu ürün grupları için ayrı veri şemaları tanımlayarak her birini kendi alan ve kural yapısıyla yönetebilirsiniz.&#x20;

#### :arrow\_forward: <mark style="color:$info;">Neden Gereklidir?</mark>

Lidia PIM’de ürün verisinin sağlıklı ilerleyebilmesi için kategori, havuz ve ürün yapıları veri şemasına bağlı çalışır.

Veri şeması sayesinde:

* ürün verisi standart bir yapıda toplanır
* zorunlu alanlar kontrol altına alınır
* hatalı veya eksik veri girişleri önlenir
* ürün grupları kategori bazında doğru şekilde yönetilir

#### :arrow\_forward: <mark style="color:$info;">Veri Şeması Nasıl Oluşturulur?</mark>

{% stepper %}
{% step %}
#### Veri şeması sayfasına gidin

Şu yolu izleyin:\
<mark style="background-color:purple;">**Ayarlar > Katalog > Ürün Aileleri**</mark>\
Sonuç: Veri şeması boş liste ekranı açılır.
{% endstep %}

{% step %}
#### Yeni veri şeması oluşturun

<mark style="background-color:purple;">**Yeni Veri Şeması Ekle**</mark> butonuna tıklayın.\
Açılan pencerede:

* <mark style="background-color:purple;">**Veri Şeması Türü**</mark> alanı <mark style="background-color:purple;">varsayılan olarak</mark> <mark style="background-color:purple;"></mark>_<mark style="background-color:purple;">Ürün</mark>_ gelir
* <mark style="background-color:purple;">**Şema Adı**</mark> alanını doldurun
* <mark style="background-color:purple;">**Eşleştirme Anahtarı**</mark> alanını doldurun

Kaydet butonuna tıklayın.\
Sonuç: Veri şeması oluşturulur ve detay sayfasına yönlendirilirsiniz.
{% endstep %}
{% endstepper %}

#### :arrow\_forward: <mark style="color:$info;">Veri Şeması Alanları Nasıl Eklenir?</mark>

Veri şeması alanları, ürün kartında hangi bilgilerin toplanacağını belirleyen yapı taşlarıdır.&#x20;

{% stepper %}
{% step %}
**Oluşturduğunuz&#x20;**<mark style="background-color:purple;">**veri şemasının detay**</mark>**&#x20;sayfasını açın.**
{% endstep %}

{% step %}
<mark style="background-color:purple;">**Veri Şeması Alanları**</mark>**&#x20;sekmesine gidin.**
{% endstep %}

{% step %}
<mark style="background-color:purple;">**Yeni Alan Ekle**</mark>**&#x20;butonuna tıklayın.**
{% endstep %}

{% step %}
**Açılan pencerede alan bilgilerini doldurun ve kaydedin.**
{% endstep %}
{% endstepper %}

Alan kaydedildiğinde veri şemasına eklenir ve ürün yapısında kullanılabilir hale gelir.

> &#x20;**Not:** İhtiyaca göre aynı şemaya birden fazla alan ekleyebilirsiniz.

#### :arrow\_forward: <mark style="color:$info;">Alan Tipleri Nelerdir?</mark>

Yeni Alan Ekle butonuna tıkladığınızda açılan pencerede yer alan alanların veri tipleri ve kullanım amaçları aşağıda listelenmiştir.

<table><thead><tr><th width="155.1851806640625">Veri Tipi</th><th>Kullanım</th><th>Örnek Alan</th></tr></thead><tbody><tr><td><em>Text</em></td><td>Serbest metin girişi gereken alanlar</td><td><mark style="background-color:purple;">Alan Adı</mark>, Açıklama, Stil</td></tr><tr><td><em>Select</em></td><td>Önceden tanımlı seçeneklerden seçim yapılacak alanlar</td><td><mark style="background-color:purple;">Alan Türü</mark>, <mark style="background-color:purple;">Alan Değeri</mark>,  Alan (Eşleştirme), Veri Tipi, Nesne Alanı, Dil</td></tr><tr><td><em>Boolean</em></td><td>Açık/Kapalı veya Evet/Hayır kontrolü gereken alanlar</td><td>Liste Ayracı, Kilitli, Veri Tipi Eşleşsin, Zorunlu</td></tr><tr><td><em>Number</em></td><td>Sayısal değer girilmesi gereken alanlar</td><td>Sıralama, Minimum Aralık Değeri, Maksimum Aralık Değeri</td></tr></tbody></table>

* Veri şemasına alan eklerken seçilen **Alan Türü**, ilgili bilginin sistemde hangi yapı ile ilişkilendirileceğini belirler. Alan türünü, alanın ürün üzerindeki kullanım amacına göre seçmeniz önerilir.

<table><thead><tr><th width="160.55560302734375">Alan Türü</th><th>Açıklama</th></tr></thead><tbody><tr><td><strong>Özellik</strong></td><td>Fiyat veya stok değişimine neden olmayan ürün niteliklerini tutar. Örn. materyal, enerji sınıfı, teknik özellikler.</td></tr><tr><td><strong>Seçenek</strong></td><td>Fiyat veya stokta farklılık yaratan varyant bilgilerini tutar. Örn. renk, beden, depolama kapasitesi.</td></tr><tr><td><strong>Kategori</strong></td><td>Ürünün kategori yapısı ile ilişkilendirilmesini sağlar.</td></tr><tr><td><strong>Marka</strong></td><td>Ürünün marka bilgisi ile eşleşmesini sağlar.</td></tr><tr><td><strong>Referanslar</strong></td><td>Ürünün diğer kayıtlarla ilişkilendirilmesini sağlar.</td></tr></tbody></table>

{% hint style="info" %}
Doğru alan türünü seçmek, ürün verisinin sistem içinde doğru şekilde işlenmesi için önemlidir.
{% endhint %}

#### :arrow\_forward: <mark style="color:$info;">Minimum önerilen alanlar nelerdir?</mark>

Ürünlerin katalogda doğru konumlanabilmesi ve temel seviyede yönetilebilmesi için veri şemasında bazı alanların tanımlanması önerilir. Minimum seviyede aşağıdaki yapı ile başlanması yeterlidir:

* **Marka (Marka)** — Ürünün doğru marka ile eşleşmesini ve filtrelenmesini sağlar.
* **Kategori (Kategori)** — Ürünün katalogda doğru konuma yerleşmesini sağlar.
* **Kısa Açıklama (Özellik)** — Listeleme ve özet alanlarında ürünün hızlı anlaşılmasını destekler.
* **Uzun Açıklama (Özellik)** — Ürün detay sayfasında zengin içerik sunulmasını sağlar.

İhtiyaç duyulması halinde veri modelinizi **Seçenek** (varyant oluşturan alanlar) ve **Referanslar** (ilişkili ürünler vb.) ile genişletebilirsiniz.

> **Not:** Veri şemasına minimum alan seti ile başlayıp kullanım ihtiyaçlarına göre yeni alanlar eklemeniz önerilir.

#### :arrow\_forward: <mark style="color:$info;">Zorunlu alan nasıl tanımlanır?</mark>

Bir alanı zorunlu olarak işaretlediğinizde, ürün oluşturma ve import işlemleri sırasında bu alanın doldurulması gerekir. Bu sayede eksik veri girişi engellenir ve ürün verisi daha kontrollü ilerler.

Bir alanı zorunlu yapmak için:

1. Veri şeması detay sayfasında ilgili alanı ekleyin veya düzenleyin.
2. Açılan pencerede **Zorunlu** seçeneğini aktif edin.
3. Değişiklikleri kaydedin.

Alan zorunlu olarak işaretlendiğinde, bu bilgi girilmeden ürün kaydedilemez veya import edilemez.

⚠️ Çok fazla alanı zorunlu yapmak, ürün yükleme sürecini zorlaştırabilir. Zorunlu alanları minimum seviyede tutmanız önerilir.
