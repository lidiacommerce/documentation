---
description: >-
  Önceki adımlarda ürün veri modelinizi ve havuzunuzu hazırladınız. Bu sayfada
  ürünlerinizi Excel kullanarak Lidia PIM’e nasıl yükleyeceğinizi
  öğreneceksiniz.
icon: list-radio
---

# PIM'e ürün nasıl eklenir?

## :rocket:<mark style="color:$primary;background-color:purple;">Ürünlerinizi PIM'e Yükleyin</mark>

Ürün yükleme süreci, hazırladığınız veri modeline göre çalışır ve ürün bilgileri bu yapı üzerinden sisteme aktarılır. Excel şablonu, <mark style="background-color:purple;">veri şemasında tanımlanan alanlara göre</mark> oluşturulur ve yüklenen ürünler bu alanlara uygun şekilde sisteme işlenir. Bu sayede ürün verisi standart bir yapı içinde ilerler ve sistem tarafından doğru şekilde yönetilir.

#### :arrow\_forward:<mark style="color:$info;">Ürün Yükleme Öncesi Tamamlanması Gereken Adımlar</mark>

{% hint style="warning" %}
**Önemli**

Ürünlerinizi sisteme yüklemeden önce aşağıdaki yapıların hazır olduğundan emin olun. Eğer bu adımlardan herhangi biri henüz tamamlanmadıysa, ilgili dokümana giderek işlemi tamamlayabilirsiniz.
{% endhint %}

* [x] **1.Ürün veri şeması oluşturulmuş olmalıdır.**

> Veri şeması oluşturma adımlarını öğrenmek için → [Veri Şeması Nasıl Oluşturulur?](https://docs.lidiacommerce.com/products/lidia-pim/quick-start-guide/veri-semasi-nasil-olusturulur)

* [x] **2.Ürün özellikleri ve seçenekleri tanımlanmış olmalıdır.**

> Özellik ve seçenek tanımlama adımlarını öğrenmek için → [Özellik ve Seçenek nasıl tanımlanır?](https://docs.lidiacommerce.com/products/lidia-pim/quick-start-guide/ozellik-ve-secenek-nasil-tanimlanir)

* [x] **3.Tanımlanan özellik ve seçenekler veri şemasına eklenmiş olmalıdır.**

> Veri şeması alanlarını yapılandırma hakkında daha fazla bilgi için → [Özellikler ve seçenekler veri şemasına nasıl eklenir?](page-1.md#ozellikler-ve-secenekler-veri-semasina-nasil-eklenir)

* [x] **4.Ürün kategorisi oluşturulmuş ve veri şeması kategoriye bağlanmış olmalıdır.**

> Kategori ve veri şeması ilişkisi hakkında detaylar için → [Kategori Nasıl Oluşturulur?](page-2.md#kategori-nasil-olusturulur)

* [x] **5.İlgili kategoriye bağlı bir havuz oluşturulmuş olmalıdır.**

> Havuz oluşturma adımlarını görmek için → [Havuzları Anlayın ve Yönetin](page-2.md#havuzlari-anlayin-ve-yonetin)

\
Tüm bu adımlar tamamlandıysa artık ürünlerinizi Excel kullanarak sisteme yüklemeye hazırsınız.

#### :arrow\_forward:<mark style="color:$info;">Excel Şablonu Nasıl İndirilir?</mark>

Lidia PIM’de ürünlerinizi Excel dosyası kullanarak sisteme ekleyebilirsiniz. Bu yöntem sayesinde ister tek bir ürün girebilir, ister çok sayıda ürünü aynı anda toplu olarak yükleyebilirsiniz. Ürün bilgileri, havuzun bağlı olduğu veri şemasına göre oluşturulan Excel şablonu üzerinden sisteme aktarılır.

{% stepper %}
{% step %}
**Katalog > Havuzlar sayfasına gidin.**
{% endstep %}

{% step %}
**Ürün yüklemek istediğiniz havuzu bulun ve&#x20;**<mark style="background-color:purple;">**Ürünleri Yönet**</mark>**&#x20;butonuna tıklayarak havuz detay sayfasını açın.**&#x20;

> **Not:** Daha önce ürün yüklenmemiş bir havuzda, detay sayfasında boş bir liste görünümü ile karşılaşırsınız. Eğer havuza daha önce ürün yüklenmişse, bu ürünler havuz detay sayfasında liste halinde görüntülenir.&#x20;
{% endstep %}

{% step %}
**Ekranda yer alan&#x20;**<mark style="background-color:purple;">**İçeri Veri Aktar**</mark>**&#x20;butonuna tıklayın.**&#x20;
{% endstep %}

{% step %}
**Açılan pencerede&#x20;**<mark style="background-color:purple;">**Taslak Şemayı İndir**</mark>**&#x20;seçeneğini görecekiniz.**

<div align="left" data-with-frame="true"><figure><img src="../../../.gitbook/assets/image (87).png" alt="" width="375"><figcaption></figcaption></figure></div>

Bu seçeneğe tıklayarak Excel şablonunu indirebilirsiniz.

> Her havuz için oluşturulan Excel şablonu kendine özeldir. Şablon, havuzu oluştururken seçtiğiniz veri şeması ve bu veri şemasına eklediğiniz alanlara göre otomatik olarak oluşturulur. Bu nedenle farklı havuzlar için indirilen Excel şablonları farklı alan kombinasyonları içerebilir.
{% endstep %}
{% endstepper %}

#### :arrow\_forward:<mark style="color:$info;">Excel Dosyası Nasıl Doldurulur?</mark>

İndirdiğiniz Excel dosyası, ürün bilgilerini sisteme yüklemek için doldurmanız gereken alanları içerir. Dosya içinde her alanın ne anlama geldiğini ve hangi alanların zorunlu olduğunu görebilirsiniz.&#x20;

İndirdiğiniz Excel dosyası iki sayfadan oluşur:

1. **Şablon Bilgileri**
2. **Ürünler**

Her iki sayfa da ürün yükleme sürecinde farklı bir amaçla kullanılır.

***

:star:**Şablon Bilgileri Sayfası**

Excel dosyasındaki ilk sayfa Şablon Bilgileri sayfasıdır. Bu sayfa, Excel dosyasında dolduracağınız tüm alanlar hakkında bilgi içerir.

Bu sayfada:

* Alan adları
* Alan açıklamaları
* Alanların zorunlu veya opsiyonel olup olmadığı

gösterilir.

Sistem tarafından otomatik oluşturulan alanlarda alan açıklamaları hazır olarak gelir. Eğer veri şeması oluştururken kendi alanlarınız için açıklama eklediyseniz (örneğin özellik, seçenek, marka veya kategori alanları), bu açıklamalar da Excel dosyasında görüntülenir.

<div align="center" data-with-frame="true"><figure><img src="../../../.gitbook/assets/image (88).png" alt="" width="375"><figcaption></figcaption></figure></div>

> Televizyon örneği üzerinden ilerlediğimiz bu senaryoda **Marka** ve **Kategori** alanları için veri şeması oluşturulurken açıklama bilgisi eklenmiştir. Bu nedenle Excel dosyasında bu alanların **Alan Açıklaması** sütununun dolu olduğu görülür. Örneğe göz atmak için: [<mark style="color:$info;">Örnek Senaryo: Televizyon Ürünü için Veri Şeması Oluşturma</mark>](quick-start-guide.md#ornek-senaryo-televizyon-urunu-icin-veri-semasi-olusturma)
>
> Bu alanlar haricinde açıklaması dolu olan diğer alanlar ise **sistem tarafından otomatik olarak oluşturulan ve açıklaması sistem tarafından eklenen alanlardır**.

{% hint style="danger" %}
Zorunlu alanlar **kırmızı renkle işaretlenir**.

Bu alanlar boş bırakılırsa ürün yükleme işlemi sırasında hata oluşur.
{% endhint %}

<i class="fa-arrow-turn-down-right">:arrow-turn-down-right:</i> **Sistem Tarafından Eklenen Alanlar**

Excel dosyasında bazı alanlar <mark style="background-color:purple;">sistem tarafından otomatik</mark> olarak oluşturulur. Bu alanlar her havuz için standart olarak bulunur ve ürün yönetimi sürecinin doğru şekilde ilerlemesi için kullanılır.

<table><thead><tr><th valign="top">Zorunlu</th><th valign="top">Opsiyonel</th><th valign="top">Salt Okunur</th></tr></thead><tbody><tr><td valign="top"><p>Bu alanlardan aşağıdakiler <strong>zorunlu alanlardır</strong> ve ürün yükleme sırasında doldurulmaları gerekir:</p><p></p><ul><li><mark style="color:purple;">Ürün Adı</mark></li><li><mark style="color:purple;">Ürün Tekil Kodu</mark></li><li><mark style="color:purple;">Satıcı Eşya Kodu</mark></li><li><mark style="color:purple;">Grup Kodu</mark></li><li><mark style="color:purple;">Resim Kodu</mark></li><li><mark style="color:purple;">Ürün Durumu</mark></li><li><mark style="color:purple;">Havuz Durumu</mark></li></ul></td><td valign="top"><p>Bu alanlardan aşağıdakiler  <strong>opsiyoneldir</strong> ve ürünleri etiketlemek veya sınıflandırmak için kullanılabilir.</p><p></p><ul><li><mark style="color:purple;">Etiketler</mark></li><li><mark style="color:purple;">Rozetler</mark></li><li><mark style="color:purple;">Yönetsel Etiketler</mark></li><li><mark style="color:purple;">Diğer Etiketler</mark></li></ul></td><td valign="top"><p>Bu alanlardan aşağıdakiler  <strong>salt okunur</strong> yapıdadır ve kullanıcı tarafından düzenlenemez.</p><p></p><p></p><ul><li><mark style="color:purple;">Güncellenme Tarihi</mark></li><li><mark style="color:purple;">Oluşturulma Tarihi</mark></li></ul></td></tr></tbody></table>

***

:star:**Ürünler Sayfası**

Excel dosyasındaki ikinci sayfa Ürünler sayfasıdır. <mark style="background-color:purple;">Ürün bilgilerini gireceğiniz asıl sayfa</mark> burasıdır. Şablon Bilgileri sayfasında açıklamalarını gördüğünüz alanları, bu sayfada <mark style="background-color:purple;">ürün bazında</mark> doldurursunuz.

Ürünler sayfasında yer alan alanlar, ürün bilgilerini daha düzenli şekilde girebilmeniz için farklı başlıklar altında gruplanmıştır. Aşağıda bu başlıkların her birinin ne anlama geldiğini ve ürün girişinde nasıl kullanıldığını inceleyebilirsiniz.



* **Temel Bilgiler Alanları**

Temel Bilgiler alanı, ürünün sistemde tanımlanabilmesi için gerekli olan ana alanları içerir. Bu alanlar her havuz için sistem tarafından oluşturulur ve ürün kaydının oluşturulabilmesi için doldurulmaları gerekir.

Bu bölümde _**Ürün Adı, Ürün Tekil Kodu, Lidia Kodu, Satıcı Eşya Kodu, Grup Kodu ve Resim Kodu**_ alanları yer alır.

Ürün Adı, Ürün Tekil Kodu, Satıcı Eşya Kodu, Grup Kodu ve Resim Kodu alanlarının doldurulması gerekir. <mark style="color:$info;background-color:purple;">**Lidia Kodu**</mark> ise Lidia PIM sistemi tarafından otomatik olarak oluşturulduğu için kullanıcı tarafından doldurulmaz ve boş bırakılması gerekir.



* **Kategori ve Marka Alanları**

Kategori ve marka alanları, ürünün hangi kategori altında yer aldığını ve hangi markaya ait olduğunu belirlemek için kullanılır. <mark style="background-color:purple;">**Bu alanlar Excel dosyasında yalnızca veri şemasını oluştururken ilgili alanları veri şemasına eklediyseniz görünür.**</mark>

Bu alanların zorunlu olup olmaması veri şemasına eklerken zorunlu seçeneğini aktif edip etmemenize bağlıdır. Eğer bu alanlar veri şemasında zorunlu olarak tanımlandıysa, Excel dosyasında da doldurulmaları gerekir. Boş bırakılması durumunda ürün yükleme sırasında sistem hata verecektir.

* [x] Kategori ve marka alanlarında veri girmek için hücreye tıkladığınızda, sistemde tanımlı olan değerler arasından seçim yapabileceğiniz bir **seçim listesi** görüntülenir. Bu sayede ürün bilgileri sistemde tanımlı kategori ve marka değerleri ile uyumlu şekilde girilir.

> Televizyon örneğinde veri şemasını oluştururken **Kategori** ve **Marka** alanlarını da veri şemasına eklemiştik. Bu nedenle televizyon havuzu için Excel şablonunu indirdiğinizde, kategori ve marka alanlarının Excel dosyasında otomatik olarak oluşturulduğunu görebilirsiniz. Bu alanlarda hücreye tıkladığınızda, sistemde tanımlı kategori ve marka değerleri arasından seçim yapabilirsiniz.



* **Özellik ve Seçenek Alanları**

Veri şemasına eklediğiniz özellikler ve seçenekler, Excel dosyasında otomatik olarak sütunlar halinde oluşturulur. Bu alanlar ürünün teknik özelliklerini ve varyant bilgilerini temsil eder.

Bu alanların zorunlu olup olmaması, veri şemasına eklerken zorunlu seçeneğini aktif edip etmemenize bağlıdır. Zorunlu olarak tanımlanan alanların Excel dosyasında boş bırakılması ürün yükleme sırasında hata oluşmasına neden olur.

Özellik ve seçenek alanlarında da hücreye tıkladığınızda daha önce sistemde tanımlanan değerleri seçebileceğiniz bir **seçim listesi** görüntülenir.

> Televizyon örneğinde daha önce **Enerji Sınıfı, Garanti Süresi ve Model Yılı** gibi alanları özellik olarak; **Ekran Boyutu, Çözünürlük ve Panel Teknolojisi** gibi alanları ise seçenek olarak tanımlamıştık. Bu nedenle televizyon havuzu için Excel şablonunu indirdiğinizde, veri şemasına eklediğiniz bu özellik ve seçenek alanlarının Excel dosyasında otomatik olarak oluşturulduğunu görebilirsiniz.



* **Diğer Bilgiler Alanı**

Excel dosyasında ayrıca Diğer Bilgiler başlığı altında sistem tarafından otomatik olarak oluşturulan bazı alanlar yer alır. Bu bölümde _**Etiketler, Rozetler, Yönetsel Etiketler ve Diğer Etiketler**_ gibi alanlar bulunur. Bu alanların doldurulması zorunlu değildir ve ürünleri etiketlemek veya sınıflandırmak için kullanılabilir.

Aynı bölümde yer alan <mark style="background-color:purple;">**Ürün Durumu**</mark> <mark style="background-color:purple;"></mark><mark style="background-color:purple;">ve</mark> <mark style="background-color:purple;"></mark><mark style="background-color:purple;">**Havuz Durumu**</mark> alanları ise ürünün sistemde nasıl kaydedileceğini belirleyen önemli alanlardır.

* [x] Ürün Durumu alanı ürünün aktif veya pasif olup olmadığını belirler. Bu alanda **1 değeri ürünün aktif**, **0 değeri ise ürünün pasif** olduğunu ifade eder.
* [x] Havuz Durumu alanı ise ürünün havuz içindeki durumunu belirler. Bu alanda **1 değeri aktif havuzu**, **0 değeri pasif havuzu**, **-99 değeri ise ürünün sistemden silinmesini** ifade eder.

<table><thead><tr><th width="158.5185546875">Ürün Durumu</th><th width="153.40740966796875">Havuz Durumu</th><th>Sonuç</th></tr></thead><tbody><tr><td>1</td><td>1</td><td>Ürün havuzda aktif ve yayınlanmaya hazır</td></tr><tr><td>1</td><td>0</td><td>Havuz pasif olduğu için ürün yüklenemez</td></tr><tr><td>0</td><td>1</td><td>Ürün pasif olarak havuza eklenir, yayınlanamaz</td></tr><tr><td>0</td><td>0</td><td>Havuz pasif olduğu için ürün yüklenemez</td></tr><tr><td>-</td><td>-99</td><td>Ürün sistemden silinir</td></tr></tbody></table>

#### :arrow\_forward:<mark style="color:$info;">Ürün Yükleme İşlemi Nasıl Yapılır?</mark>

Excel dosyanızı hazırladıktan sonra ürünleri havuza yüklemek için aşağıdaki adımları izleyin.

{% stepper %}
{% step %}
**Katalog > Havuzlar sayfasına gidin.**
{% endstep %}

{% step %}
**Ürün yüklemek istediğiniz havuzu bulun ve&#x20;**<mark style="background-color:purple;">**Ürünleri Yönet**</mark>**&#x20;butonuna tıklayarak havuz detay sayfasını açın.**

<a href="https://pim.lidiacommerce.com/metadata/data-pools" class="button primary">Ürünleri Yönet</a>
{% endstep %}

{% step %}
**Sayfanın üst bölümünde yer alan "**<mark style="background-color:purple;">**Veriyi İçe Aktar"**</mark>**&#x20;butonuna tıklayın.**
{% endstep %}

{% step %}
**Açılan pencerede&#x20;**<mark style="background-color:purple;">**"Dosyayı yüklemek için tıklayın"**</mark>**&#x20;alanına tıklayın ve hazırladığınız dolu Excel dosyasını seçin.**

Bu alana yalnızca Excel formatında (.xlsx) dosya yükleyebilirsiniz.

Excel dosyasını yükleme işlemi üç adımda ilerler: _<mark style="color:purple;background-color:purple;">Yeni Excel Dokümanı Yükle → Veriyi Kontrol Et → Tamamlandı.</mark>_

<div align="left" data-with-frame="true"><figure><img src="../../../.gitbook/assets/image.png" alt="" width="210"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
**Excel dosyası yüklendikten sonra&#x20;**<mark style="background-color:purple;">**Yeni Excel Dokümanı Yükle**</mark>**&#x20;adımı tamamlanır,&#x20;**<mark style="background-color:purple;">**Devam Et**</mark>**&#x20;butonuna tıklayın ve bir sonraki adıma geçin.**
{% endstep %}

{% step %}
<mark style="background-color:purple;">**Veriyi Kontrol Et**</mark>**&#x20;adımında sistem kontrolünden geçilir, ardından&#x20;**<mark style="background-color:purple;">**Devam Et**</mark>**&#x20;butonuna tıklayın ve içe aktarımı onaylama adımına geçin.**
{% endstep %}

{% step %}
<mark style="background-color:purple;">**"İçe aktarımı onaylıyorum"**</mark>**&#x20;butonuna tıklayın.**

<div align="left" data-with-frame="true"><figure><img src="../../../.gitbook/assets/image (94).png" alt="" width="155"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
:tada:**Havuza ürün aktarımı tamamlandı**


{% endstep %}
{% endstepper %}



#### :arrow\_forward:<mark style="color:$info;">Olası Hatalar ve Çözüm Yolları</mark>



_<mark style="color:$info;">Veriyi Kontrol Et</mark>_ adımında sistem Excel dosyasındaki verileri kontrol eder. Eğer dosyada hata varsa işlem tamamlanmaz ve aşağıdaki uyarı görüntülenir:

<div align="left" data-with-frame="true"><figure><img src="../../../.gitbook/assets/image (89).png" alt="" width="375"><figcaption></figcaption></figure></div>

{% hint style="warning" %}
**İçe aktarım tamamlanamadı!**\
Excel ile içeri veri aktarımı tamamlanamadı. Lütfen Excel dökümanını kontrol ederek tekrar deneyiniz.
{% endhint %}





<figure><img src="../../../.gitbook/assets/image (92).png" alt=""><figcaption></figcaption></figure>



<figure><img src="../../../.gitbook/assets/image (93).png" alt=""><figcaption></figcaption></figure>







<figure><img src="../../../.gitbook/assets/image (95).png" alt=""><figcaption></figcaption></figure>



