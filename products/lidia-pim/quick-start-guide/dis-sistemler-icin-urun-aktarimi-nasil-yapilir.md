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

<figure><img src="../../../.gitbook/assets/image (165).png" alt=""><figcaption></figcaption></figure>

#### :arrow\_forward:<mark style="color:$info;">Yeni Akış Nasıl Oluşturulur?</mark>

{% stepper %}
{% step %}
<mark style="background-color:purple;">**Servisler > Akışlar**</mark>**&#x20;sayfasına gidin.**
{% endstep %}

{% step %}
<mark style="background-color:purple;">**Yeni Akış Ekle**</mark>**&#x20;butonuna tıklayın.**

Açılan modalda:

* **Akış Adı (Zorunlu)**
* **Akış Kodu (Zorunlu)**
* **Akış Formatı (Zorunlu)** — Lidia PIM veya Google Shopping formatlarından birini seçin.
*

    <div align="left" data-with-frame="true"><figure><img src="../../../.gitbook/assets/image.png" alt="" width="147"><figcaption></figcaption></figure></div>
* **Devam Et** butonuna tıklayın.
{% endstep %}

{% step %}
:tada:**Yeni akış oluşturuldu.**

Akış oluşturulduktan sonra sistem sizi akış detay sayfasına yönlendirir. Bu sayfada akış ayarlarını yapılandırabilir ve alan eşleştirme işlemlerini tamamlayabilirsiniz.
{% endstep %}
{% endstepper %}

{% hint style="info" %}
**Önemli**&#x20;

Oluşturulan her akış için erişim yetkileri **Erişim Kontrolü** üzerinden yönetilebilir. Böylece akış bağlantısını yalnızca erişim izni bulunan kullanıcılar veya sistemler kullanabilir.
{% endhint %}

#### :arrow\_forward:<mark style="color:$info;">Feed Ayarları Nasıl Yapılır?</mark>

* Akış oluşturulduktan sonra temel bilgilerde değişiklik yapmak isterseniz, akış detay sayfasında yer alan **Temel Bilgiler** sekmesini kullanabilirsiniz.

Bu bölümde **Bilgileri Güncelle** butonuna tıklayarak aşağıdaki bilgileri düzenleyebilirsiniz:\
&#x20;    Akış Adı, Akış Kodu, Akış Formatı, Erişim Kontrolü Durumu, Akış Durumu (Aktif / Pasif)

<div align="center" data-with-frame="true"><figure><img src="../../../.gitbook/assets/image (157).png" alt="" width="563"><figcaption></figcaption></figure></div>

Aynı ekranda yer alan **Yeni Erişim Anahtarı Ekle** butonu ile akış bağlantısına erişim için kullanılacak anahtar değerler oluşturabilirsiniz. Erişim anahtarı, akış URL’inin yetkili sistemler tarafından güvenli şekilde kullanılmasını sağlar.

Bir akış için birden fazla erişim anahtarı tanımlayabilirsiniz. Böylece farklı dış sistemler veya iş ortakları için ayrı anahtarlar oluşturabilir, erişimleri birbirinden bağımsız şekilde yönetebilirsiniz.

<div data-with-frame="true"><figure><img src="../../../.gitbook/assets/image (158).png" alt="" width="563"><figcaption></figcaption></figure></div>



* **Akış Ayarları** sekmesinde, oluşturduğunuz akışın çıktı biçimi, veri işleme kuralları, filtreleme seçenekleri ve akışa dahil edilecek veri paketleri yapılandırılır.

<mark style="background-color:blue;">**-Çıktı Ayarları**</mark>

Bu bölümde oluşturulacak akış dosyasının nasıl üretileceği belirlenir.

{% tabs %}
{% tab title="GZIP Sıkıştırma" %}
**GZIP** Sıkıştırma seçeneği etkinleştirildiğinde oluşturulan çıktı dosyası GZIP algoritması kullanılarak sıkıştırılır.&#x20;

<div data-with-frame="true"><figure><img src="../../../.gitbook/assets/image (162).png" alt="" width="309"><figcaption></figcaption></figure></div>

Büyük veri setlerinin daha **küçük boyutta** paylaşılması gerektiğinde bu seçenek kullanılabilir.
{% endtab %}

{% tab title="Boş Alan Yönetimi" %}
Bu bölüm, boş veya **null** değerlerin akış çıktısında nasıl işleneceğini belirler.&#x20;

<div data-with-frame="true"><figure><img src="../../../.gitbook/assets/image (161).png" alt="" width="313"><figcaption></figcaption></figure></div>

**Boş Değerleri Hariç Tut** seçeneği etkinleştirildiğinde boş veya null değer içeren alanlar oluşturulan akış çıktısına dahil edilmez.
{% endtab %}

{% tab title="Boşluk Karakteri Yönetimi" %}
Bu bölüm, metin alanlarında bulunan gereksiz boşlukların otomatik olarak temizlenmesini sağlar.

<div data-with-frame="true"><figure><img src="../../../.gitbook/assets/image (160).png" alt="" width="364"><figcaption></figcaption></figure></div>

&#x20;**Boşlukları Temizle** seçeneği etkinleştirildiğinde tüm metin değerlerinin başındaki ve sonundaki gereksiz boşluk karakterleri kaldırılır.
{% endtab %}

{% tab title="Durum Bazlı Filtreleme" %}
Bu bölümde akışa dahil edilecek ürün ve varyant durumları belirlenir.

<div align="center" data-with-frame="true"><figure><img src="../../../.gitbook/assets/image (159).png" alt="" width="375"><figcaption></figcaption></figure></div>

**Ürün Durumları** ve **Varyant Durumları** için ayrı ayrı durum filtreleme uygulanabilir. Durum filtreleme kapalı olduğunda ilgili tüm durumlar akışa dahil edilir.

Durum filtreleme etkinleştirildiğinde **Dahil Edilecek Durumlar** alanı aktif olur ve akışta yer almasını istediğiniz durumları seçmeniz gerekir. Yalnızca seçilen durumlara sahip ürün veya varyantlar akış çıktısına dahil edilir.
{% endtab %}
{% endtabs %}

<mark style="background-color:blue;">**-Filtreler**</mark>

Filtreler bölümü, akışa dahil edilecek verileri belirli kriterlere göre sınırlandırmanızı sağlar. Bu sayede yalnızca istediğiniz ürünler akışta yer alır.

Bu bölümde aşağıdaki filtreler kullanılabilir:

* Kategoriler
* Hariç Kategoriler
* Markalar
* Hariç Markalar
* Özel Listeler
* Ürün Özellikleri
* Varyant Özellikleri
* Seçenek Değerleri
* Ürün Etiketleri
* Hariç Ürün Etiketleri
* Varyant Etiketleri
* Hariç Varyant Etiketleri

Seçilen filtreler birlikte değerlendirilir ve yalnızca belirlenen kriterlere uyan kayıtlar akışa dahil edilir.

<mark style="background-color:blue;">**-Veri Paketi**</mark>

Veri Paketi bölümü, akışta hangi veri paketlerinin yer alacağını belirlemek için kullanılır.

Bu bölümde aşağıdaki alanlar yapılandırılabilir:

* Koleksiyonlar
* Kategori Boyutları

Seçilen veri paketleri, oluşturulan akış çıktısına dahil edilir.

#### :arrow\_forward:<mark style="color:$info;">Ürün Alanları Feed Alanları ile Nasıl Eşleştirilir?</mark>

Alan eşleştirme işlemleri **Formatlar ve Önizleme** sekmesinde gerçekleştirilir. Sayfanın üst kısmında yer alan **Kullanım Kuralları ve İpuçları** bölümü ise eşleştirme işlemi sırasında dikkat edilmesi gereken kurallar hakkında yönlendirici bilgiler sunar.

<div data-with-frame="true"><figure><img src="../../../.gitbook/assets/image (166).png" alt=""><figcaption></figcaption></figure></div>

{% hint style="warning" %}
:bangbang:Tüm bu yöntemlerde kullanıcıya bir veya birden fazla rol tanımlanabilir ve kullanıcının sistemdeki erişim yetkileri, atanmış rollerin birleşimi ile belirlenir.
{% endhint %}

#### :arrow\_forward:<mark style="color:$info;">Akış Nasıl Çalıştırılır ve Dış Sistemlerle Nasıl Paylaşılır?</mark>

Akış ayarları ve alan eşleştirme işlemleri tamamlandıktan sonra akışınızı kullanabilirsiniz.

Akış çalıştırıldığında sistem, seçilen ürün verilerini belirlenen formatta hazırlar. Oluşturulan akış çıktısı bağlantı üzerinden dış sistemlerle paylaşılabilir.

Örnek bağlantı:

<div data-with-frame="true"><figure><img src="../../../.gitbook/assets/image (164).png" alt=""><figcaption></figcaption></figure></div>

Feed bağlantısını kopyalayarak ilgili platforma ekleyebilir veya entegrasyon süreçlerinde kullanabilirsiniz.

Örnek çıktı:

<div data-with-frame="true"><figure><img src="../../../.gitbook/assets/pim-api-techie-tt-tr.lidiacommerce.net_api_v2.0_feeds_1023_1020_Emre%20Test2_xml (3).png" alt=""><figcaption></figcaption></figure></div>

