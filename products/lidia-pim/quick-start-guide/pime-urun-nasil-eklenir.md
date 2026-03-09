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

{% hint style="danger" %}
Zorunlu alanlar **kırmızı renkle işaretlenir**.

Bu alanlar boş bırakılırsa ürün yükleme işlemi sırasında hata oluşur.
{% endhint %}

<div data-with-frame="true"><figure><img src="../../../.gitbook/assets/image (88).png" alt=""><figcaption></figcaption></figure></div>

>
