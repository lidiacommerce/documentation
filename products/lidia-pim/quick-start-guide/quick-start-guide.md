---
description: >-
  Lidia PIM’e hoş geldiniz. Bu rehber, ilk ürününüzü sisteme sorunsuz şekilde
  ekleyebilmeniz için gerekli temel adımlarda size yol göstermek amacıyla
  hazırlanmıştır.
icon: list-radio
---

# Veri şeması nasıl oluşturulur?

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

### :rocket:<mark style="color:$primary;background-color:purple;">Veri modelinizi inşa edin</mark>

Lidia PIM’de ürünlerinizi sorunsuz yönetebilmek için ilk ve en kritik adım veri şemasını doğru şekilde kurgulamaktır. Doğru yapılandırılmış bir veri şeması, benzer ürünleri düzenli bir yapı altında toplar ve ürün verisinin kategori bazında kontrollü ve sürdürülebilir şekilde ilerlemesini sağlar.

#### :arrow\_forward: <mark style="color:$info;">Veri Şeması Nedir?</mark>

Veri şeması, ürünleriniz için hangi bilgilerin tutulacağını ve bu bilgilerin hangi kurallara göre yönetileceğini belirleyen temel veri modelidir.

Basitçe ifade etmek gerekirse veri şeması:

* <mark style="background-color:purple;">ürün kartında hangi alanların görüneceğini belirler</mark>
* <mark style="background-color:purple;">bu alanların veri tipini tanımlar</mark>
* <mark style="background-color:purple;">hangi bilgilerin zorunlu olduğunu kontrol eder</mark>
* <mark style="background-color:purple;">benzer ürünlerin aynı yapıda yönetilmesini sağlar</mark>

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

> **Eşleştirme Anahtarı**, Lidia PIM ile Lidia Console’daki veri şemaları arasında alanların birbiriyle bağlanmasını sağlar.
>
> Müşteri hem **Lidia PIM** hem de **Lidia Console** kullanıyorsa, iki tarafta da ayrı veri şemaları bulunur.\
> Bu alan, PIM’de oluşturulan bir alanın Console’daki hangi alanla eşleşeceğini tanımlar.

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

***



{% columns %}
{% column %}
:new\_moon:<mark style="background-color:purple;">**Yeni Alan Ekle**</mark>

Bu ekran, ürün ve varyant verilerinin PIM içerisinde nasıl tutulacağını ve yayına nasıl taşınacağını belirleyen alanların tanımlandığı ekrandır.

<figure><img src="../../../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

#### <mark style="background-color:purple;">1. Temel Bilgiler</mark>

* **Alan Adı** _(Zorunlu)_\
  Oluşturulan alanın sistemde ve ürün ekranlarında görünecek adıdır.
* **Açıklama** _(Opsiyonel)_\
  Alanının ne amaçla kullanıldığını açıklamak için kullanılır.
* **Alan Türü** _(Zorunlu)_\
  Alanının sistemde nasıl davranacağını belirler.\
  Alan türü değerleri:\
  ![](<../../../.gitbook/assets/image (111).png>)
* **Alan Değeri** _(Koşullu – Zorunlu)_\
  Yalnızca Alan Türü = Özellik veya Seçenek olduğunda görüntülenir.\
  Bu alan, alanın hangi değer setiyle çalışacağını belirler.
* **Liste Ayracı** _(Opsiyonel)_\
  Bu alanın ön yüzde ürün listeleme ekranlarında ayıraç olarak kullanılıp kullanılmayacağını belirler. Açık olduğunda, alan değeri farklı olan ürünler listelemede ayrı itemlar olarak gösterilebilir.

> Örnek:\
> iPhone 12 – Siyah / Beyaz / Mavi renkleri listelemede ayrı ürünler gibi gösterilebilir.

* **Kilitli** _(Opsiyonel)_\
  Alan kilitlendiğinde, ürün ekranlarında düzenlenemez hale gelir.
* **Sıralama** _(Opsiyonel)_\
  Alanların ürün ekranında hangi sırayla gösterileceğini belirler.\
  Sayısal bir değer alır. Küçük değerler üstte gösterilir.
* **Stil** _(Opsiyonel)_\
  Alan için ön yüzde veya arayüzde uygulanacak özel stil bilgisidir.\
  Gelişmiş kullanım senaryoları için opsiyoneldir.
{% endcolumn %}

{% column %}
#### <mark style="background-color:purple;">2. Validasyon Bilgileri</mark>

* **Veri Tipi Eşleşsin**\
  Alan için tanımlanan veri tipi ile girilen değerin uyumlu olmasını zorunlu kılar.

> Örnek:\
> Sayı beklenen bir alana metin girilmesini engeller.

* **Zorunlu** _(Opsiyonel)_\
  Bu alan işaretlendiğinde, ürün veya varyant yayına alınmadan önce bu alanın doldurulması gerekir.
* **Minimum Aralık Değeri** _(Opsiyonel)_\
  Sayısal alanlar için girilebilecek en düşük değeri belirler.
* **Maksimum Aralık Değeri** _(Opsiyonel)_\
  Sayısal alanlar için girilebilecek en yüksek değeri belirler.



#### <mark style="background-color:purple;">3. Eşleştirme (Mapping) Bilgileri</mark>

Bu bölüm, oluşturulan alanın değerinin sistemde hangi nesneye ve o nesnenin hangi alanına yazılacağını belirler.\
Alan, Veri Tipi ve Nesne Alanı bir bütün olarak değerlendirilmelidir.

* **Alan** _(Opsiyonel)_\
  Verinin hangi yapı üzerinden saklanacağını belirtir.\
  Genellikle 'Meta Verileri' olarak gelir.
*   **Veri Tipi** _(Opsiyonel)_

    Veri Tipi, girilen değerin sistemde hangi nesneye ait olduğunu belirtir.

_Veri tipi değerleri:_\
&#xNAN;_\[ Ürün Dokümanı ] \[ Ürün Doküman Etiketi ] \[ Kategori ] \[ Kategori Boyutu ] \[ Kategori Filtresi ]_ \
_\[ Kategori Filtre Seçeneği ] \[ Kategori Görseli ] \[ Kategori Ürünleri] \[ Kategori Özelliği ] \[ Kategori Etiketi ] \[ Kategori Tercümesi ] \[ Kategori Varyant Listesi ] \[ Marka ] \[ Marka Filtresi ] \[ Marka Filtre Seçeneği ] \[ Marka Görseli ] \[ Marka Ürünleri ] \[ Marka Özelliği ] \[ Marka Etiketi ] \[ Marka Tercümesi ] \[ Marka Varyant Listesi ] \[ Para Birimi ] \[ Para Birimi Tercümesi ] \[ Özel Liste Dokümanı ] \[ Özel Liste Doküman Görseli ] \[ Veri Akışı ] \[ Veri Akış Kategorisi ]_ \
_\[ Veri Akış Özel Listesi ] \[ Veri Akış Satış Etkinliği ] \[ Veri Akış Markası ] \[ Veri Havuzu ] \[ Veri Havuzu Etiketi ] \[ Veri Havuzu Özelliği ] \[ Veri Havuzu Ögesi ] \[ Veri Havuzu Öge Etiketi ] \[ Veri Havuzu Öge Alan Değeri ] \[ Veri Şeması ] \[ Veri Şema Kategorisi ] \[ Veri Şema Alanı ]_ \
_\[ Veri Şema Şablonu ] \[ Ambalaj ]_ \
_\[ Ambalaj Boyutu ] \[ Fiyat ] \[ Fiyat Listesi ] \[ Satış Etkinliği ] \[ Satış Etkinlik Etiketi ] \[ Satış Etkinlik Özelliği ] \[ Satış Etkinlik Ögesi ] \[ Varyant ] \[ Varyant Etiketi ]_ \
_\[ Varyant Özelliği ] \[ Varyant Tercümesi ] \[ Varyant Özellik Tercümesi ] \[ Varyant Seçenek Değeri ] \[ Garanti ]_

*   **Nesne Alanı** _(Opsiyonel)_

    Seçilen veri tipinin içindeki hedef alanı belirtir.

    Örnek: Name, TaxRate, ParentId, OptionValues, IntegrationCode, ShortDescription, LongDescription, ProductId, Type, Unit, Link, Options


{% endcolumn %}
{% endcolumns %}



#### :arrow\_forward: <mark style="color:$info;">Alan Tipleri Nelerdir?</mark>

Veri şemasına alan eklerken seçilen **Alan Türü**, ilgili bilginin sistemde hangi yapı ile ilişkilendirileceğini belirler. Alan türünü, alanın ürün üzerindeki kullanım amacına göre seçmeniz önerilir.

<table><thead><tr><th width="160.55560302734375">Alan Türü</th><th>Açıklama</th></tr></thead><tbody><tr><td><strong>Özellik</strong></td><td>Fiyat veya stok değişimine neden olmayan ürün niteliklerini tutar. </td></tr><tr><td><strong>Seçenek</strong></td><td>Fiyat veya stokta farklılık yaratan varyant bilgilerini tutar. </td></tr><tr><td><strong>Kategori</strong></td><td>Ürünün kategori yapısı ile ilişkilendirilmesini sağlar.</td></tr><tr><td><strong>Marka</strong></td><td>Ürünün marka bilgisi ile eşleşmesini sağlar.</td></tr><tr><td><strong>Referanslar</strong></td><td>Ürünün diğer kayıtlarla ilişkilendirilmesini sağlar.</td></tr></tbody></table>

**Özellik** veya **Seçenek** için önceden tanımlanan değerler, **Alan Değeri** alanında aşağıdaki veri tiplerini destekler: _<mark style="color:purple;">Metin, Tam Sayı, Ondalık Sayı, Ölçü, Tekil Kod, Tek Satır Metin, Uzun Metin, Zengin Metin, Tekli Seçim, Çoklu Seçim, Liste, Var/Yok, Tarih, E-posta, Tel No, URL, Fiyat, Yüzde, Süre</mark>_. Bu sayede alan yapısını ihtiyaçlarınıza göre esnek şekilde özelleştirebilirsiniz.

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

<div align="center" data-with-frame="true"><figure><img src="../../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure></div>

{% hint style="info" %}
&#x20;Çok fazla alanı zorunlu yapmak, ürün yükleme sürecini zorlaştırabilir. Zorunlu alanları **minimum** seviyede tutmanız önerilir.
{% endhint %}

#### :arrow\_forward: <mark style="color:$info;">Şema oluşturulmadan neden kategori/havuz oluşturulamaz?</mark>

Veri şeması, ürün verisinin hangi alanlar üzerinden yönetileceğini belirleyen temel yapıdır. Kategori ve havuz yapıları, ürünleri bu şemaya göre organize eder ve işler.

* [x] <mark style="background-color:purple;">Kategori teknik olarak veri şeması olmadan oluşturulabilir; ancak bu kategori taslak durumda kalır ve havuz oluşturma adımında seçilemez.</mark> Bunun nedeni, havuz ve ürün yapılarının çalışabilmesi için kategoriye bağlı bir veri şemasının bulunmasının gerekli olmasıdır.

Veri şeması tanımlandığında kategori artık havuz oluşturma sürecinde kullanılabilir.

> **Not:** Bu bağımlılık, ürün verisinin eksik veya tutarsız bir yapı ile ilerlemesini önlemek amacıyla uygulanır.

#### :arrow\_forward: <mark style="color:$info;">Örnek Senaryo: Televizyon Ürünü için Veri Şeması Oluşturma</mark>

Televizyon kategorisindeki ürünlerinizi <mark style="background-color:purple;">belirli bir kural seti ile, tutarlı ve kontrollü</mark> bir yapıda yayınlamak istediğinizi düşünün.

Bu yapılandırmayı sağlayabilmek için ilk adım, televizyon ürünlerine özel bir veri şeması oluşturmaktır.

{% stepper %}
{% step %}
**Ayarlar > Katalog > Ürün Aileleri yolunu izleyin.**
{% endstep %}

{% step %}
**Yeni Veri Şeması Ekle butonuna tıklayın.**

<table data-card-size="large" data-view="cards"><thead><tr><th></th><th data-hidden data-card-cover data-type="image">Cover image</th></tr></thead><tbody><tr><td><p>Açılan pencerede:<br><strong>Veri Şeması Türü:</strong> Ürün<br><strong>Şema Adı:</strong> Televizyon<br><strong>Eşleştirme Anahtarı:</strong> TV</p><p>Kaydet butonuna tıklayın. Veri şeması oluşturulur ve detay sayfasına yönlendirilirsiniz.</p></td><td data-object-fit="fill"><a href="../../../.gitbook/assets/image (52).png">image (52).png</a></td></tr></tbody></table>
{% endstep %}

{% step %}
**Alanları ekleyin.**<br>

<table data-card-size="large" data-view="cards" data-full-width="false"><thead><tr><th></th><th data-hidden data-card-cover data-type="image">Cover image</th></tr></thead><tbody><tr><td><ol><li>Veri şaması detay sayfası <strong>Temel Bilgiler</strong> alanı açık gelir.</li></ol></td><td data-object-fit="fill"><a href="../../../.gitbook/assets/Ekran görüntüsü 2026-03-03 144520.png">Ekran görüntüsü 2026-03-03 144520.png</a></td></tr><tr><td><ol start="2"><li>Veri şeması detay sayfası <strong>Veri Şeması Alanları</strong> açılır.<br><strong>Yeni Alan Ekle</strong> butonuna tıklanır.<br></li></ol></td><td data-object-fit="fill"><a href="../../../.gitbook/assets/Ekran görüntüsü 2026-03-03 213835.png">Ekran görüntüsü 2026-03-03 213835.png</a></td></tr><tr><td><p></p><ol start="3"><li><strong>Alan Adı:</strong> Marka<br><strong>Alan Türü:</strong> Marka<br><strong>Açıklama:</strong> Ürünün ait olduğu markayı seçiniz.<br><strong>Sıralama:</strong> 1<br><strong>Kilitli:</strong> Pasif<br><strong>Zorunlu:</strong> Aktif<br><strong>Veri Tipi:</strong> Marka</li></ol></td><td data-object-fit="contain"><a href="../../../.gitbook/assets/Ekran görüntüsü 2026-03-03 145748.png">Ekran görüntüsü 2026-03-03 145748.png</a></td></tr><tr><td><ol start="4"><li><p>Televizyon ürünlerim için gerekli <strong>alanları veri şemama ekledim</strong>. Bu alanlar sayesinde ürün bilgilerimi <strong>belirlediğim kural seti</strong> doğrultusunda yönetebilirim.</p><p>İhtiyaç duyduğum kadar alan ekledim, mevcut alanları düzenleyebilir ve istersem veri yapımı gereksinimlerime göre yeniden yapılandırabilirim.</p></li></ol></td><td data-object-fit="fill"><a href="../../../.gitbook/assets/Ekran görüntüsü 2026-03-03 214611.png">Ekran görüntüsü 2026-03-03 214611.png</a></td></tr></tbody></table>
{% endstep %}

{% step %}
:tada:**Veri şemanız başarıyla oluşturuldu.**

> **Not:** Oluşturduğunuz her veri şeması için sistem tarafından otomatik olarak bir havuz oluşturulur. Bu havuz, ilgili veri şemasına bağlı ürünlerin yönetileceği temel yapıyı temsil eder.
{% endstep %}
{% endstepper %}

