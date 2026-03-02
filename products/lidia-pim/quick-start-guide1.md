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
**Açılan pencerede&#x20;**<mark style="background-color:purple;">**alan bilgilerini**</mark>**&#x20;doldurun ve kaydedin.**
{% endstep %}
{% endstepper %}

Alan kaydedildiğinde veri şemasına eklenir ve ürün yapısında kullanılabilir hale gelir.

> &#x20;**Not:** İhtiyaca göre aynı şemaya <mark style="background-color:purple;">birden fazla alan</mark> ekleyebilirsiniz.

Yeni Alan Ekle butonuna tıkladığınızda açılan pencerede yer alan alanlar ve bu alanların veri tipleri aşağıda listelenmiştir.

<table><thead><tr><th width="155.1851806640625">Veri Tipi</th><th>Kullanım</th><th>Örnek Alan</th></tr></thead><tbody><tr><td><em>Text</em></td><td>Serbest metin girişi gereken alanlar</td><td><mark style="background-color:purple;">Alan Adı</mark>, Açıklama, Stil</td></tr><tr><td><em>Select</em></td><td>Önceden tanımlı seçeneklerden seçim yapılacak alanlar</td><td><mark style="background-color:purple;">Alan Türü</mark>, <mark style="background-color:purple;">Alan Değeri</mark>,  Alan (Eşleştirme), Veri Tipi, Nesne Alanı, Dil</td></tr><tr><td><em>Boolean</em></td><td>Açık/Kapalı veya Evet/Hayır kontrolü gereken alanlar</td><td>Liste Ayracı, Kilitli, Veri Tipi Eşleşsin, Zorunlu</td></tr><tr><td><em>Number</em></td><td>Sayısal değer girilmesi gereken alanlar</td><td>Sıralama, Minimum Aralık Değeri, Maksimum Aralık Değeri</td></tr></tbody></table>

Yeni Alan Ekle penceresinde aşağıdaki alanların doldurulması gerekir:

* <mark style="background-color:purple;">**Alan Adı**</mark> (_text_)
* <mark style="background-color:purple;">**Alan Türü**</mark> (_select_)
* <mark style="background-color:purple;">**Alan Değeri**</mark> (_select_)

Bu alanlar girilmeden alan kaydedilemez.

{% hint style="info" %}
**Alan Değeri**, yalnızca Alan Türü = **Özellik** veya **Seçenek** seçildiğinde görüntülenir ve bu durumda zorunludur.
{% endhint %}



{% columns %}
{% column %}
<figure><img src="../../.gitbook/assets/image (51).png" alt="Yeni Alan Ekle"><figcaption></figcaption></figure>
{% endcolumn %}

{% column %}
* **Açıklama** alanı opsiyoneldir; alanın kullanım amacını ürün yükleyen kullanıcıya açıklamak için önerilir.
* **Sıralama** alanı opsiyoneldir. Sayısal değer kabul eder ve alanın ekranda hangi sırada görüntüleneceğini belirler.
* **Minimum-Maksimum Aralık Değeri** opsiyoneldir. Sayısal aralık kısıtı gereken alanlarda alt ve üst limit tanımlamak için kullanılır.
* **Veri Tipi** alanı opsiyoneldir. Alanın sistemde hangi veri yapısına karşılık geleceğini tanımlamak için kullanılır.
* **Nesne Alanı** opsiyoneldir. Alanın hangi nesne ile ilişkilendirileceğini tanımlamak için kullanılır.
{% endcolumn %}
{% endcolumns %}

#### :arrow\_forward: <mark style="color:$info;">Alan Tipleri Nelerdir?</mark>

Veri şemasına alan eklerken seçilen **Alan Türü**, ilgili bilginin sistemde hangi yapı ile ilişkilendirileceğini belirler. Alan türünü, alanın ürün üzerindeki kullanım amacına göre seçmeniz önerilir.

<table><thead><tr><th width="160.55560302734375">Alan Türü</th><th>Açıklama</th></tr></thead><tbody><tr><td><strong>Özellik</strong></td><td>Fiyat veya stok değişimine neden olmayan ürün niteliklerini tutar. Örn. materyal, enerji sınıfı, teknik özellikler.</td></tr><tr><td><strong>Seçenek</strong></td><td>Fiyat veya stokta farklılık yaratan varyant bilgilerini tutar. Örn. renk, beden, depolama kapasitesi.</td></tr><tr><td><strong>Kategori</strong></td><td>Ürünün kategori yapısı ile ilişkilendirilmesini sağlar.</td></tr><tr><td><strong>Marka</strong></td><td>Ürünün marka bilgisi ile eşleşmesini sağlar.</td></tr><tr><td><strong>Referanslar</strong></td><td>Ürünün diğer kayıtlarla ilişkilendirilmesini sağlar.</td></tr></tbody></table>

**Özellik** veya **Seçenek** için önceden tanımlanan değerler, **Alan Değeri** alanında aşağıdaki veri tiplerini destekler: _<mark style="color:purple;">Metin, Tam Sayı, Ondalık Sayı, Ölçü, Tekil Kod, Tek Satır Metin, Uzun Metin, Zengin Metin, Tekli Seçim, Çoklu Seçim, Liste, Var/Yok, Tarih, E-posta, Tel No, URL, Fiyat, Yüzde, Süre, Resim, Dosya</mark>_. Bu sayede alan yapısını ihtiyaçlarınıza göre esnek şekilde özelleştirebilirsiniz.

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

Bir alanı <mark style="background-color:purple;">zorunlu</mark> olarak işaretlediğinizde, ürün oluşturma ve import işlemleri sırasında bu alanın doldurulması gerekir. Bu sayede eksik veri girişi engellenir ve ürün verisi daha kontrollü ilerler.

Bir alanı zorunlu yapmak için:

1. Veri şeması detay sayfasında ilgili alanı ekleyin veya düzenleyin.
2. Açılan pencerede <mark style="background-color:purple;">**Zorunlu**</mark> <mark style="background-color:purple;"></mark><mark style="background-color:purple;">seçeneğini aktif</mark> edin.
3. Değişiklikleri kaydedin.

Alan zorunlu olarak işaretlendiğinde, bu bilgi girilmeden ürün kaydedilemez veya import edilemez.

{% hint style="info" %}
&#x20;Çok fazla alanı zorunlu yapmak, ürün yükleme sürecini zorlaştırabilir. Zorunlu alanları **minimum** seviyede tutmanız önerilir.
{% endhint %}

#### :arrow\_forward: <mark style="color:$info;">Şema oluşturulmadan neden kategori/havuz oluşturulamaz?</mark>

Veri şeması, ürün verisinin hangi alanlar üzerinden yönetileceğini belirleyen temel yapıdır. Kategori ve havuz yapıları, ürünleri bu şemaya göre organize eder ve işler.

<mark style="background-color:purple;">Kategori teknik olarak veri şeması olmadan oluşturulabilir; ancak bu kategori taslak durumda kalır ve havuz oluşturma adımında seçilemez.</mark> Bunun nedeni, havuz ve ürün yapılarının çalışabilmesi için kategoriye bağlı bir veri şemasının bulunmasının gerekli olmasıdır.

Veri şeması tanımlandığında kategori artık havuz oluşturma sürecinde kullanılabilir.

> **Not:** Bu bağımlılık, ürün verisinin eksik veya tutarsız bir yapı ile ilerlemesini önlemek amacıyla uygulanır.

