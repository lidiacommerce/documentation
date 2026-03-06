---
description: >-
  Bu sayfada havuzun ne olduğunu, ne amaçla kullanıldığını ve nasıl
  oluşturulduğunu ayrıca kategori, veri şeması ve havuz arasındaki ilişkiyi
  öğreneceksiniz.
icon: list-radio
---

# Havuz nedir, nasıl yönetilir?

## :rocket:<mark style="color:$primary;background-color:purple;">Havuz'ları Anlayın ve Yönetin</mark>

Önceki sayfalarda ürün [veri şemasını](https://docs.lidiacommerce.com/products/lidia-pim/quick-start-guide/veri-semasi-nasil-olusturulur) oluşturduk ve ürün modelimizi [özellikler ile seçenekleri](https://docs.lidiacommerce.com/products/lidia-pim/quick-start-guide/ozellik-ve-secenek-nasil-tanimlanir) tanımlayarak hazırladık. Şimdi bu veri modelini kullanarak ürünleri yöneteceğimiz yapıyı inceleyelim.

#### :arrow\_forward:<mark style="color:$info;">Havuz Nedir?</mark>

**Havuz**, ürünlerin sistemde ilk kez oluşturulduğu ve yönetildiği çalışma alanıdır. Ürünler bu alana yüklenir ve ürün bilgileri burada kontrol edilir.

Ürünler havuza <mark style="background-color:purple;">Excel dosyaları veya entegrasyonlar</mark> (örneğin SAP) aracılığıyla yüklenebilir.\
Her havuz, belirli bir <mark style="background-color:purple;">kategoriye</mark> bağlıdır ve o kategori için tanımlanan <mark style="background-color:purple;">**veri şemasını**</mark> kullanır. Bu sayede ürünler platformda tanımlanan standart veri yapısına uygun şekilde oluşturulur ve yönetilir.

Başka bir ifadeyle havuz, ürünlerin doğru veri modeli ile sisteme yüklenmesini sağlayan başlangıç noktasıdır.

#### :arrow\_forward:<mark style="color:$info;">Havuz ne amaçla kullanılır?</mark>

Ürünleri sisteme yüklerken havuzu kullanırsınız. Ürün verileri bu alan içinde oluşturulur, düzenlenir ve kontrol edilir.

Havuz sayesinde:

* <mark style="background-color:purple;">ürünler doğru kategori altında yönetilir</mark>
* <mark style="background-color:purple;">ürün verisi tanımlanan veri şemasına uygun ilerler</mark>
* <mark style="background-color:purple;">ürün yükleme ve yönetim süreçleri daha düzenli hale gelir</mark>

> Örneğin televizyon ürünleri için oluşturduğunuz **Televizyon** kategorisine bağlı bir havuz kullanarak, televizyon ürünlerinizi ilgili veri modeli ile sisteme yükleyebilirsiniz.&#x20;

{% hint style="info" %}
**Önemli**: Yeni bir veri şeması oluşturduğunuzda, sistem otomatik olarak aynı isimde bir havuz oluşturur. Bu havuz, ilgili veri şemasına bağlı ürünlerin yönetileceği alan olarak kullanılır.
{% endhint %}

#### :arrow\_forward:<mark style="color:$info;">Havuz Oluşturmak İçin Neden Kategori Gereklidir?</mark>

Havuz oluştururken bir kategori seçmeniz gerekir. Bunun nedeni, havuz'un hangi ürün tipini yöneteceğini bilmesi gerektiğidir.

Kategori aynı zamanda hangi veri şemasının kullanılacağını da belirler.

Her kategori, kendisine bağlı bir **veri şeması** ile çalışır. Bu veri şeması ürünlerin hangi alanları içereceğini ve ürün verisinin nasıl yapılandırılacağını tanımlar. Havuz oluşturulduğunda sistem, seçilen kategoriye bağlı veri şemasını kullanarak ürünlerin bu yapıya uygun şekilde oluşturulmasını sağlar.

Başka bir ifadeyle:

_<mark style="color:purple;">Veri Şeması → Kategori → Havuz → Ürün</mark>_

Bu ilişki sayesinde ürünler doğru veri modeli ile oluşturulur.

{% hint style="info" %}
Eğer henüz bir veri şeması oluşturmadıysanız, [**Veri Şeması Nasıl Oluşturulur?**](https://docs.lidiacommerce.com/products/lidia-pim/quick-start-guide/veri-semasi-nasil-olusturulur) sayfasındaki adımları takip edebilirsiniz.
{% endhint %}

#### :arrow\_forward:<mark style="color:$info;">Kategori Nasıl Oluşturulur?</mark>

Kategori oluşturmak için aşağıdaki adımları izleyin:

{% stepper %}
{% step %}
<mark style="background-color:purple;">**Katalog > Kategoriler**</mark>**&#x20;sayfasına gidin.**
{% endstep %}

{% step %}
<mark style="background-color:purple;">**Kategori Ekle**</mark> **butonuna tıklayın.**

Açılan pencerede aşağıdaki alanları doldurun:

* **İsim (Zorunlu)**
* **Boyut**&#x20;
* **Veri Şeması**&#x20;
* **Üst Kategori**
* **Kod (Zorunlu)**

> Kategorinizi hiyerarşik bir yapıda oluşturmak istiyorsanız, **Üst Kategori (Opsiyonel)** alanından kategoriyi bağlamak istediğiniz üst kategoriyi seçebilirsiniz.

> :warning:Aynı pencerede <mark style="background-color:purple;">**Veri Şeması**</mark> alanı da yer alır. Bu alan seçilmeden kategori kaydedilebilir ve kategori oluşturulabilir. Ancak bu durumda kategori _<mark style="background-color:purple;">**taslak**</mark>_ statüsünde oluşturulur.
>
> Yeni bir kategori oluştururken veri şeması seçmeniz önerilir. Bu sayede kategori doğrudan ilgili veri modeli ile ilişkilendirilmiş olur. \
> Eğer veri şeması seçmeden taslak bir kategori oluşturduysanız, <mark style="background-color:purple;">kategori detay sayfasına</mark> giderek daha sonra **veri şeması** bağlayabilirsiniz.
{% endstep %}

{% step %}
🎉**Kategori başarıyla oluşturuldu.**
{% endstep %}
{% endstepper %}

#### :arrow\_forward:<mark style="color:$info;">Havuz Nasıl Oluşturulur?</mark>

Kategori oluşturma işlemini tamamladıktan sonra <mark style="background-color:purple;">havuz oluşturma</mark> adımına geçebilirsiniz.

Yeni bir havuz oluşturmak için aşağıdaki adımları izleyin:

{% stepper %}
{% step %}
<mark style="background-color:purple;">**Ayarlar > Katalog > Havuzlar**</mark>**&#x20;sayfasına gidin.**
{% endstep %}

{% step %}
<mark style="background-color:purple;">**Yeni Ürün Ailesi Ekle**</mark> **butonuna tıklayın.**

Açılan pencerede sistemde tanımlı kategoriler, varsa alt kategorileriyle birlikte listelenir.

Yeni bir ürün ailesi oluşturmak ve içerisine ürün ekleyebilmek için bir kategori seçmeniz gerekir.
{% endstep %}

{% step %}
**Bir kategori seçtikten sonra&#x20;**<mark style="background-color:purple;">**Devam Et**</mark>**&#x20;butonuna tıklayın.**
{% endstep %}

{% step %}
:tada:**Seçilen kategoriye bağlı olarak sistem, ürün eklemeye hazır&#x20;**<mark style="background-color:purple;">**boş bir havuz**</mark>**&#x20;oluşturur.**

Bu havuz içinde ürünlerinizi oluşturmaya veya yüklemeye başlayabilirsiniz.
{% endstep %}
{% endstepper %}







