---
description: >-
  Bu sayfada Lidia PIM'de bulunan ürünlerinizi farklı platformlara aktarmak için
  akış oluşturmayı, akış ayarlarını yapılandırmayı ve alan eşleştirmelerini
  yapmayı öğreneceksiniz.
icon: list-radio
---

# Dış sistemler için ürün aktarımı nasıl yapılır?

### :rocket:<mark style="color:$primary;background-color:purple;">Ürünlerinizi Dış Platformlara Hazırlayın</mark>

Akış yönetimi, Lidia PIM’deki ürün verilerini farklı platformların beklediği formatlarda hazırlamanızı sağlar. Bu sayede ürünlerinizi pazaryerleri, reklam platformları, entegrasyon servisleri veya diğer dış sistemlerle tek bir bağlantı üzerinden paylaşabilirsiniz.

Doğru yapılandırılmış bir akış, ürün bilgilerinin hedef platformun beklediği alan yapısına uygun şekilde aktarılmasını sağlar ve manuel veri hazırlama ihtiyacını ortadan kaldırır.

#### :arrow\_forward:<mark style="color:$info;">Akış Nedir, Ne Amaçla Kullanılır?</mark>

Akış, Lidia PIM'de bulunan ürün bilgilerinin belirli bir formatta dış sistemlere aktarılmasını sağlayan veri çıktısıdır.

Bir akış oluşturduğunuzda sistem, seçtiğiniz ürün bilgilerini belirlediğiniz alan yapısına göre hazırlar ve size benzersiz bir bağlantı (**URL**) oluşturur. Bu bağlantıyı ürün verilerini almak isteyen dış sistemlerle paylaşabilirsiniz. Dış sistem, bu URL üzerinden ürün adı, marka, kategori, fiyat, stok, teknik özellikler ve görseller gibi bilgileri belirlenen formatta alabilir.

> **Örneğin**, seramik ve yapı malzemeleri üreten bir firma, ürün kataloglarını sürekli e-posta ile göndermek yerine mimarlık ofisleriyle oluşturduğu akış bağlantısını paylaşabilir. Mimarlar bu bağlantı üzerinden güncel ürün bilgilerine, teknik özelliklere ve görsellere her zaman erişebilir. Ürün bilgilerinde bir güncelleme yapıldığında, akış üzerinden paylaşılan veriler de güncel hale gelir ve dosyaların yeniden gönderilmesine gerek kalmaz.
>
> \
> Bu sayede ürün verileri tek bir kaynaktan yönetilir ve farklı sistemlerle güncel ve tutarlı şekilde paylaşılabilir.

#### :arrow\_forward:<mark style="color:$info;">Hangi Akış Formatları Desteklenmektedir?</mark>

Lidia PIM'de akış oluştururken üç farklı yapılandırma seçeneği sunulur:

* **Lidia PIM Formatı**
* **Google Shopping Formatı**
* **Manuel Yapılandırma**

Seçtiğiniz format, ürün bilgilerinin hangi alanlarla ve hangi yapıda dış sisteme aktarılacağını belirler.

<div align="left" data-with-frame="true"><figure><img src="../../../.gitbook/assets/image (143).png" alt="" width="323"><figcaption></figcaption></figure></div>



1.  **Lidia PIM Formatı**\
    ![](<../../../.gitbook/assets/image (152).png>)\
    Bu format seçildiğinde feede dahil edilecek alanlar hazır olarak gelir ve kullanıcıdan yalnızca bu alanların sistem karşılıklarını girmesi beklenir. Ürün, kategori, marka, görsel, doküman, etiket, envanter, çeviri (Translation), özellik ve varyant bilgileri için oluşturulmuş alan grupları doğrudan ekrana gelir.<br>

    Her grup altında ilgili verilerin dış sisteme aktarılacak alanları önceden tanımlanmıştır. İhtiyacınıza göre bu alanları düzenleyebilir, yeni alanlar ekleyebilir veya kullanılmasını istemediğiniz alanları kaldırabilirsiniz.<br>

    Bu yapı, Lidia PIM verilerini eksiksiz şekilde dış sistemlere aktarmak isteyen kullanıcılar için hızlı bir başlangıç sağlar.

<div align="left"><figure><img src="../../../.gitbook/assets/image (153).png" alt="" width="375"><figcaption></figcaption></figure> <figure><img src="../../../.gitbook/assets/image (155).png" alt="" width="176"><figcaption></figcaption></figure> <figure><img src="../../../.gitbook/assets/image (156).png" alt="" width="189"><figcaption></figcaption></figure></div>

{% hint style="info" %}
Ekranın sağ tarafında bulunan **Önizleme** alanı, yaptığınız alan eşleştirmelerinin oluşturulacak akış çıktısına nasıl yansıyacağını anlık olarak gösterir. Böylece akışı kaydetmeden önce oluşacak çıktıyı kontrol edebilir ve gerekli düzenlemeleri yapabilirsiniz.
{% endhint %}



2. **Google Shopping Formatı**\
   <img src="../../../.gitbook/assets/image (144).png" alt="" data-size="original">\
   Google Shopping Formatı, Google Merchant Center'ın beklediği XML yapısına uygun olarak hazırlanmış hazır bir akış şablonudur.\
   \
   Bu format seçildiğinde sistem, Google Shopping için gerekli XML yapısını otomatik olarak oluşturur. **rss**, **channel** ve **item** grupları ile birlikte XML öznitelikleri (Node Attribute) ve Google'ın kullandığı temel alan eşleştirmeleri varsayılan olarak hazır gelir.\
   \
   Ürün adı (**g**), kısa açıklama (**g**), ürün bağlantısı (**g**), ana görsel (**g**), fiyat (**g**), marka (**g**), entegrasyon kodu (**g**) ve benzeri Google Shopping alanları Lidia PIM ürün alanlarıyla önceden eşleştirilmiştir.

<div><figure><img src="../../../.gitbook/assets/image (148).png" alt="" width="375"><figcaption></figcaption></figure> <figure><img src="../../../.gitbook/assets/image (147).png" alt="" width="560"><figcaption></figcaption></figure></div>



3.  **Manuel Yapılandırma**\
    ![](<../../../.gitbook/assets/image (149).png>)\
    Manuel Yapılandırma seçildiğinde Mapping Alanı boş olarak oluşturulur.

    Bu yöntemde hangi alanların akışta yer alacağı tamamen kullanıcı tarafından belirlenir. **Alan Ekle** butonunu kullanarak yeni alanlar oluşturabilir, ürün verilerinden hangi bilgilerin aktarılacağını seçebilir ve alanların sırasını ihtiyacınıza göre düzenleyebilirsiniz.

    Bu seçenek, hazır şablonlar yerine tamamen özelleştirilmiş bir akış oluşturmak isteyen kullanıcılar için uygundur.



#### :arrow\_forward:<mark style="color:$info;">Yeni Akış Nasıl Oluşturulur?</mark>

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

    <div align="left" data-with-frame="true"><figure><img src="../../../.gitbook/assets/image (7).png" alt="" width="234"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
:tada:**Yeni rol tanımlandı.**

Rol oluşturulduktan sonra detay sayfası üzerinden yönetilebilir.
{% endstep %}
{% endstepper %}

{% hint style="info" %}
**Önemli**&#x20;

Rol oluşturma ve yetki tanımlama işlemleri, kullanıcının sahip olduğu role bağlıdır. Örneğin, Guest rolüne sahip bir kullanıcı rol oluşturma veya yetki tanımlama işlemlerini gerçekleştiremez.
{% endhint %}

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

{% hint style="warning" %}
:bangbang:Tüm bu yöntemlerde kullanıcıya bir veya birden fazla rol tanımlanabilir ve kullanıcının sistemdeki erişim yetkileri, atanmış rollerin birleşimi ile belirlenir.
{% endhint %}
