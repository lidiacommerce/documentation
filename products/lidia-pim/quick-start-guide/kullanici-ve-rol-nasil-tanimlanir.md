---
description: >-
  Bu sayfada Lidia PIM’de kullanıcı ve rol tanımlama sürecini, kullanıcı ekleme
  adımlarını ve rol atamaları ile erişim yetkilerinin nasıl yönetildiğini
  öğreneceksiniz.
icon: list-radio
---

# Kullanıcı ve Rol nasıl tanımlanır?

### :rocket:<mark style="color:$primary;background-color:purple;">Kullanıcı ve Rol Yetkilerini Yönetin</mark>

Lidia PIM’de kullanıcı yetkileri roller aracılığıyla yönetilir. Sistem içerisinde varsayılan olarak gelen roller bulunur ve ihtiyaçlarınıza göre yeni roller tanımlanabilir. Roller için erişilebilecek alanlar ile görüntüleme ve düzenleme yetkileri konfigüre edilebilir. Yeni kullanıcı oluştururken kullanıcıya bir rol atanarak sistemdeki erişim yetkileri belirlenir.

#### :arrow\_forward:<mark style="color:$info;">Rol nedir, ne işe yarar?</mark>

Rol, bir kullanıcının Lidia PIM içinde hangi ekranlara erişebileceğini ve hangi işlemleri yapabileceğini belirleyen yetki tanımıdır.

Kısaca, rol yapısı şu soruların cevabını verir:

* Kullanıcı hangi modülleri görebilir?
* Hangi sayfalara erişebilir?
* Hangi işlemleri yapabilir?
* Hangi işlemleri yapamaz?

{% hint style="info" %}
**Tüm kullanıcıların aynı yetkiye sahip olması gerekmez**

Ürün verisini yöneten bir kullanıcı ile yalnızca içerik kontrolü yapan bir kullanıcının erişim ihtiyacı farklı olabilir. Bu nedenle kullanıcılar, görevlerine uygun roller ile sisteme tanımlanır.
{% endhint %}

Lidia PIM içerisinde sistem tarafından tanımlı bazı <mark style="background-color:purple;">varsayılan roller</mark> bulunur. Bu roller, kullanıcıların sistemde hangi alanlara erişebileceğini ve bu alanlarda hangi yetkilere sahip olacağını belirler. Yetkiler temel olarak <mark style="background-color:purple;">**görüntüleme**</mark> ve <mark style="background-color:purple;">**düzenleme**</mark> olmak üzere iki seviyede tanımlanır.

* **Sistem tarafından tanımlı roller:**

<table><thead><tr><th width="244.44439697265625">Rol Adı</th><th width="436.266845703125">Rol Açıklaması</th></tr></thead><tbody><tr><td><mark style="color:purple;"><strong>Guest</strong></mark></td><td>Sisteme sınırlı erişimi olan kullanıcı rolüdür. Genellikle yalnızca belirli alanları görüntüleme yetkisine sahiptir ve düzenleme yetkisi bulunmaz.</td></tr><tr><td><mark style="color:purple;"><strong>OrganizationUser</strong></mark></td><td>Organizasyon içinde temel kullanıcı rolüdür. Yetkili olduğu modüllerde verileri görüntüleyebilir ve görev kapsamına göre sınırlı düzenleme işlemleri yapabilir.</td></tr><tr><td><mark style="color:purple;"><strong>OrganizationAdmin</strong></mark></td><td>Organizasyon seviyesinde yönetim yetkilerine sahip roldür. Kullanıcıları, rolleri ve organizasyon içindeki erişimleri yönetebilir.</td></tr><tr><td><mark style="color:purple;"><strong>OrganizationOwner</strong></mark></td><td>Organizasyonun en yüksek yetkili rolüdür. Organizasyon ayarlarını yönetebilir, kullanıcı ve rol yetkilerini düzenleyebilir ve tüm modüllere tam erişime sahiptir.</td></tr><tr><td><mark style="color:purple;"><strong>CustomerSuccess</strong></mark></td><td>Platform sağlayıcı ekipleri için kullanılan destek rolüdür. Müşteri organizasyonlarını inceleyebilir, sorun çözme ve destek süreçlerinde gerekli erişimlere sahiptir.</td></tr><tr><td><mark style="color:purple;"><strong>ApplicationAdmin</strong></mark></td><td>Uygulama veya platform seviyesinde yönetim yetkisine sahip roldür. Sistem konfigürasyonları, uygulama ayarları ve platform genelindeki yönetim işlemlerini gerçekleştirebilir.</td></tr></tbody></table>

* [x] Rol bazında hangi modüllerin görüntülenebileceği ve hangi alanların düzenlenebileceği ayrı ayrı belirlenebilir. Gerekli durumlarda, daha yüksek yetkilere sahip kullanıcılar bu rol yetkilerini konfigüre ederek erişim kapsamını güncelleyebilir.

#### :arrow\_forward:<mark style="color:$info;">Rol bazlı yetkiler nelerdir?</mark>

Yetkiler, Sistem altında hiyerarşik olarak yapılandırılır. Her kırılım için <mark style="color:purple;">Görüntüle</mark> ve <mark style="color:purple;">Düzenle</mark> yetkileri ayrı ayrı tanımlanabilir.

**System** → Tüm yetki yapısının en üst kırılımıdır.\
│\
├─**Settings** → Sistem ayarlarının yönetildiği ana alandır.\
│    ├─ **Authorization** → Kullanıcı ve rol yetkilerinin yönetildiği alandır.\
│    │     ├─ <mark style="color:$info;">**Authorized Users**</mark> → Sistem kullanıcılarının yönetildiği alandır.\
│    │     └─ <mark style="color:$info;">**Roles**</mark> → Roller ve rol yetkilerinin tanımlandığı alandır.\
│    ├─ **Contacts** → İletişim kayıtlarının yönetildiği alandır.\
│    ├─ **Catalog** → Ürün veri yapısına ait tanımların yönetildiği alandır.\
│    │      ├─ <mark style="color:$info;">**Data Schemas**</mark> → Veri şemalarının oluşturulduğu ve yönetildiği alandır.\
│    │      ├─ <mark style="color:$info;">**Collections**</mark> → Koleksiyonların yönetildiği alandır.\
│    │      ├─ <mark style="color:$info;">**Data Locks**</mark> → Veri kilitleme işlemlerinin yönetildiği alandır.\
│    │      ├─ <mark style="color:$info;">**Product Relations**</mark> → Ürün ilişkilerinin tanımlandığı alandır.\
│    │      ├─ <mark style="color:$info;">**Category Dimensions**</mark> → Kategori kırılımlarının yönetildiği alandır.\
│    │      ├─ <mark style="color:$info;">**Channels**</mark> → Kanal yapılarının tanımlandığı alandır.\
│    │      ├─ <mark style="color:$info;">**MetaData Tags**</mark> → Metadata etiketlerinin yönetildiği alandır.\
│    │      ├─ <mark style="color:$info;">**Properties**</mark> → Özelliklerin tanımlandığı ve yönetildiği alandır.\
│    │      └─ <mark style="color:$info;">**Options**</mark> → Seçenek yapılarının yönetildiği alandır.\
│    │            ├─ Properties → Seçeneklerle ilişkili özelliklerin yönetildiği alandır.\
│    │            ├─ Property Groups → Özellik gruplarının yönetildiği alandır.\
│    │            ├─ Options → Seçeneklerin tanımlandığı alandır.\
│    │            ├─ Option Groups → Seçenek gruplarının yönetildiği alandır.\
│    │            ├─ Option Values → Seçenek değerlerinin tanımlandığı alandır.\
│    │            └─ Option Value Groups → Seçenek değer gruplarının yönetildiği alandır.\
│    ├─  **Localization** → Lokalizasyon ayarlarının yönetildiği alandır.\
│    │      ├─ <mark style="color:$info;">**Languages**</mark> → Sistem dillerinin tanımlandığı alandır.\
│    │      ├─ <mark style="color:$info;">**Currencies**</mark> → Para birimlerinin yönetildiği alandır.\
│    │      └─ <mark style="color:$info;">**Measurement Units**</mark> → Ölçü birimlerinin tanımlandığı alandır.\
│    └─ **Configurations** → Sistem konfigürasyonlarının yönetildiği alandır.\
│\
├─**Notification Center** → Bildirim merkezi yönetim alanıdır.\
│    ├─ **Notifications** → Sistem bildirimlerinin görüntülendiği alandır.\
│    └─ **Settings** → Bildirim ayarlarının yapılandırıldığı alandır.\
│\
├─**My Organization** → Organizasyon ayarlarının yönetildiği alandır.\
│    ├─ **Details** → Organizasyon bilgilerinin görüntülendiği alandır.\
│    ├─ **Subscriptions** → Abonelik bilgilerinin yönetildiği alandır.\
│    └─ **Applications** → Organizasyona bağlı uygulamaların yönetildiği alandır.\
│\
├─**Catalog** → Organizasyon bazlı katalog yönetim alanıdır.\
│    ├─ **Data Pools** → Veri havuzlarının yönetildiği alandır.\
│    ├─ **Categories** → Kategori yapısının yönetildiği alandır.\
│    ├─ **Trademarks** → Marka bilgilerinin yönetildiği alandır.\
│    ├─ **Custom Lists** → Özel listelerin yönetildiği alandır.\
│    ├─ **Products** → Ürünlerin yönetildiği alandır.\
&#x20;     └─ **Variants** → Varyantların yönetildiği alandır.\
│\
├─ **Inventory** → Envanter ve fiyat yapılarının yönetildiği alandır.\
│    └─ **Price Lists** → Fiyat listelerinin yönetildiği alandır.\
│\
├ ─**Media Management** → Medya içeriklerinin yönetildiği alandır.\
│    ├─**Documents** → Dokümanların yönetildiği alandır.\
│    ├─ **Images** → Görsellerin yönetildiği alandır.\
│    ├─ **Files** → Dosyaların yönetildiği alandır.\
│    └─ **Videos** → Videoların yönetildiği alandır.\
│&#x20;\
├─ **Services** → Servis ve entegrasyon alanıdır.\
│     └─ **Feeds** → Veri akışlarının yönetildiği alandır.\
│&#x20;\
└─ **Reports** → Raporlama ve kayıt izleme alanıdır.\
&#x20;      └─  **Audit Logs** → Sistem işlem kayıtlarının görüntülendiği alandır.

#### :arrow\_forward:<mark style="color:$info;">Rol nasıl oluşturulur?</mark>

{% hint style="info" %}
**Önemli**&#x20;

Rol oluşturma ve yetki tanımlama işlemleri, kullanıcının sahip olduğu role bağlıdır. Örneğin, Guest rolüne sahip bir kullanıcı rol oluşturma veya yetki tanımlama işlemlerini gerçekleştiremez.
{% endhint %}

{% stepper %}
{% step %}
<mark style="background-color:purple;">**Ayarlar > Yetkilendirme > Roller**</mark>**&#x20;sayfasına gidin.**
{% endstep %}

{% step %}
<mark style="background-color:purple;">**Yeni Rol Ekle**</mark> **aksiyonunu seçin.**

Açılan modalda:

* **Rol adı** alanını doldurun _(zorunlu)_
* **Kullanıcılar** alanı isteğe bağlıdır, daha sonra eklenebilir
*

    <div align="left" data-with-frame="true"><figure><img src="../../../.gitbook/assets/image.png" alt="" width="234"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
:tada:**Yeni rol tanımlandı.**

Rol oluşturulduktan sonra detay sayfası üzerinden yönetilebilir.
{% endstep %}
{% endstepper %}

> **Rol detayında neler yapılır?**
>
> Rol oluşturulduktan sonra rol detay sayfası üzerinden yönetim yapılır.
>
> > * _<mark style="color:$info;">Kullanıcılar</mark>_ sekmesinde bu role bağlı kullanıcılar görüntülenebilir ve <mark style="background-color:purple;">**Kullanıcılara rol tanımla**</mark> aksiyonu ile yeni kullanıcılar bu role eklenebilir.&#x20;
> > * _<mark style="color:$info;">Yetkiler</mark>_ sekmesinde ise rolün sistemde hangi alanlara erişebileceği belirlenir; her modül için görüntüleme ve düzenleme yetkileri ayrı ayrı tanımlanabilir veya kaldırılabilir. Bu sayede rol bazlı erişim kapsamı merkezi ve kontrollü şekilde yönetilir.
>
> &#x20;

#### :arrow\_forward:<mark style="color:$info;">Yeni kullanıcı nasıl oluşturulur?</mark>

{% stepper %}
{% step %}
<mark style="background-color:purple;">**Ayarlar > Yetkilendirme > Kullanıcılar**</mark> **sayfasına gidin.**
{% endstep %}

{% step %}
<mark style="background-color:purple;">**Yeni Kullanıcı Ekle**</mark>**&#x20;butonuna tıklayın.**

Açılan modalda:

* **E-posta**, **Cep Telefonu** ve **Doğum Tarihi** alanlarını doldurun _(zorunludur)_
*

    <div align="left" data-with-frame="true"><figure><img src="../../../.gitbook/assets/image (114).png" alt="" width="237"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
:tada:**Yeni kullanıcı oluşturdunuz.**
{% endstep %}
{% endstepper %}

> **Kullanıcı detayında neler yapılır?**
>
> Kullanıcı oluşturulduktan sonra detay sayfası üzerinden yönetilebilir.
>
> > * _<mark style="color:$info;">Temel Bilgiler</mark>_ sekmesinden ad soyad, cep telefonu, doğum tarihi ve kimlik bilgisi gibi kullanıcı bilgilerini görüntüleyebilir ve kontrol edebilirsiniz. Gerekli durumlarda <mark style="background-color:purple;">**Şifre sıfırlama isteği gönder**</mark> aksiyonu ile kullanıcı için şifre yenileme süreci başlatabilirsiniz.
> > * _<mark style="color:$info;">Yetkiler</mark>_ sekmesinde kullanıcıya ekstra rol atayabilirsiniz. Bir kullanıcıya birden fazla rol tanımlanabilir ve kullanıcının sistemdeki erişim yetkileri bu roller üzerinden belirlenir.

#### :arrow\_forward:<mark style="color:$info;">Kullanıcıya rol nasıl atanır?</mark>

Kullanıcıya rol atama işlemi birden fazla noktadan yapılabilir:

* **Kullanıcı üzerinden:** <mark style="background-color:purple;">Kullanıcı oluşturma sırasında</mark> veya kullanıcı detay sayfasındaki _<mark style="color:$info;background-color:purple;">Yetkiler</mark>_ sekmesinden rol atanabilir.
* **Rol üzerinden:** <mark style="background-color:purple;">Rol oluşturma sırasında</mark> veya rol detay sayfasındaki _<mark style="color:$info;background-color:purple;">Kullanıcılar</mark>_ sekmesinden kullanıcıya rol atanabilir.

:bangbang:Tüm bu yöntemlerde kullanıcıya bir veya birden fazla rol tanımlanabilir ve kullanıcının sistemdeki erişim yetkileri, atanmış rollerin birleşimi ile belirlenir.
