---
description: >-
  Bu sayfada ürün özelliklerini ve seçeneklerini nasıl tanımlayacağınızı,
  aralarındaki farkı ve veri şemasına nasıl ekleyeceğinizi öğreneceksiniz.
icon: list-radio
---

# Özellik ve Seçenek nasıl tanımlanır?

## :rocket:<mark style="color:$primary;background-color:purple;">Özellik ve Seçenekleri Yapılandırın</mark>

Özellikler ve seçenekler, ürün kartının hangi bilgileri içereceğini ve bu bilgilerin sistemde nasıl yönetileceğini belirler. Doğru yapılandırıldığında, ürün verisi daha tutarlı ilerler ve varyant yönetimi daha kontrollü şekilde yapılır.

#### :arrow\_forward:<mark style="color:$info;">Özellik Nedir?</mark>

**Özellik**, ürünün teknik veya açıklayıcı niteliklerini tanımlamak için kullanılan veri alanıdır. Özellikler, ürün kartında gösterilen bilgileri oluşturur ve ürünün filtrelenmesini, karşılaştırılmasını ve detaylandırılmasını sağlar.

Özellikler fiyat veya stok değişikliğine neden olmaz; ürünün niteliğini tanımlar.



* <mark style="background-color:purple;">**Özellik Veri Tipi Nedir?**</mark>

Bir özellik oluşturulduktan sonra, bu özelliğin hangi formatta veri kabul edeceği belirlenir. Buna veri tipi denir.

```
Desteklenen veri tipleri: 
-Tekil Kod   -Tek Satır Metin   -Uzun Metin   -Zengin Metin   -Tekli Seçim  -Çoklu Seçim
-Liste   -Var/Yok   -Tarih   -E-posta   -Tel No   -URL   -Fiyat   -Yüzde   -Süre   -Ölçü
```

Veri tipi olarak **Tekli Seçim** veya **Çoklu Seçim** seçildiğinde, özellik için kullanılacak değerleri önceden tanımlamalısınız. Bu değerleri sistemde siz oluşturur ve ihtiyaçlarınıza göre istediğiniz kadar ekleyebilir veya düzenleyebilirsiniz.

> Televizyon örneğinden devam edelim, önce bir özellik tanımlayalım ve veri tipini 'çoklu seçim' olarak seçelim:
>
> * **Özellik:** Enerji Sınıfı
> * **Veri Tipi:** Çoklu Seçim
> * **Tanımlanan Değerler:** A, B, C, D, E, F
> *
>
>     <div align="left" data-with-frame="true"><figure><img src="../../../.gitbook/assets/image (54).png" alt="" width="188"><figcaption></figcaption></figure></div>
>
> Bu sayede ürün oluşturma sırasında kullanıcı yalnızca tanımladığınız değerler arasından seçim yapabilir. Yeni değer girilemez; yalnızca mevcut seçenekler kullanılabilir.

Bu yöntemle veri girişini kontrol altında tutarsınız ve tutarlı bir ürün yapısı oluşturursunuz.



* <mark style="background-color:purple;">**Özellik Grubu Nedir?**</mark>

**Özellik grubu**, benzer özellikleri bir arada düzenlemek için kullanılır. Özellik grupları, PIM kullanıcısı olarak ürün verinizi daha düzenli yönetmenize yardımcı olur. İlgili özellikleri aynı başlık altında toplayarak hem ürün girişini hem de veri yönetimini kolaylaştırabilirsiniz.

> Örneğin televizyon ürünü için **Ekran Boyutu, Çözünürlük ve Panel Teknolojisi** gibi özellikleri oluşturduysanız, bu özellikleri **Ekran Özellikleri** adlı bir özellik grubu altında toplayın. Bu şekilde ilgili özellikleri aynı başlık altında düzenleyebilir ve ürün kartında daha düzenli bir yapı oluşturabilirsiniz.

#### :arrow\_forward:<mark style="color:$info;">Seçenek Nedir?</mark>

**Seçenek**, ürünün farklı versiyonlarını oluşturmak için kullanılan alanlardır. Genellikle fiyat veya stokta farklılık yaratan bilgiler seçenek olarak tanımlanır.

> Örneğin televizyon ürününde **Çözünürlük** bir seçenek olabilir. Bu seçenek, televizyonun hangi çözünürlükte sunulduğunu belirler ve kendine ait seçenek değerleri içerir, kendine ait seçenek değerleri vardır.

Bir seçenek oluştururken, seçeneğin hangi veri tipinde değer alacağını belirleyebilirsiniz.

Desteklenen veri tipleri şunlardır:

* [x] Metin, Tam Sayı, Ondalık Sayı, Ölçü



* <mark style="background-color:purple;">**Seçenek Değeri Nedir?**</mark>

**Seçenek değeri**, bir seçeneğe ait kullanılabilir değerleri ifade eder. Bir seçenek oluşturduktan sonra, o seçeneğe ait istediğiniz kadar seçenek değeri ekleyebilirsiniz.

> Örneğin **Çözünürlük** bir TV seçeneği ise, buna ait seçenek değerleri **4K**, **8K** gibi değerler olabilir. Ürün oluştururken kullanıcı bu değerler arasından seçim yapar.\
> Başka bir örnek olarak **Renk** seçeneğini düşünün. Bu seçeneğe ait değerler **Siyah**, **Mavi**, **Bebek Mavisi** gibi farklı renkler olabilir.

Seçenek değerlerini tamamen ihtiyaçlarınıza göre tanımlayabilirsiniz.



* <mark style="background-color:purple;">**Seçenek Değer Grubu Nedir?**</mark>

**Seçenek değer grubu**, benzer seçenek değerlerini bir arada düzenlemek için kullanılır. Çok sayıda seçenek değeri bulunan alanlarda değerleri daha düzenli yönetmenize yardımcı olur.

> Örneğin televizyon ürünü için **Renk** seçeneğini oluşturduğunuzu düşünün. Bu seçeneğe ait değerler **Gri, Gümüş, Antrasit, Beyaz, Siyah** gibi farklı tonlar olabilir. Bu değerlerden benzer gördüklerinizi örneğin gri+gümüş+antrasit üçlüsünü **Gri Tonları** adlı bir seçenek değer grubunda toplayabilirsiniz.

Seçenek değer grubu oluşturmak için:

1. **Ayarlar > Katalog > Seçenekler > Seçenek Değer Grupları** sayfasına gidin.
2. **Seçenek Değer Grubu Ekle** butonuna tıklayın.
3. Açılan pencerede **Seçenek Değer Grubu Adı** , **Görüntülenecek Ad** ve **Değer Grubu Kodu** alanlarını doldurun, kaydedin.
4.

    <div align="left" data-with-frame="true"><figure><img src="../../../.gitbook/assets/image (1).png" alt="" width="117"><figcaption></figcaption></figure></div>
5. Seçenek değerlerini oluşturduktan sonra ilgili değerin **detay sayfası**na gidin ve bu değeri oluşturduğunuz **seçenek değer grubuna** bağlayın.

Bu sayede benzer seçenek değerlerini aynı grup altında düzenleyebilirsiniz.



* <mark style="background-color:purple;">**Seçenek Grubu Nedir?**</mark>

**Seçenek grubu**, birden fazla seçeneği mantıksal olarak aynı başlık altında toplamak için kullanılır. Bu yapı özellikle çok sayıda seçenek bulunan ürünlerde yönetimi kolaylaştırır.

> Örneğin televizyon ürününde **Renk**, **Panel Teknolojisi,** **Çözünürlük, Dahili Wi-Fi** gibi birden fazla farklı seçenek oluşturduysanız, bu seçeneklerden renk, panel teknolojisi ve çözünürlüğü ekran özelliği olarak nitelendirebilir, **Ekran Özellikleri** adlı bir seçenek grubunda bir araya getirebilirsiniz.

Seçenek değer grubu oluşturmak için:

1. **Ayarlar > Katalog > Seçenekler > Seçenek Grupları** sayfasına gidin.
2. **Seçenek Grubu Ekle** butonuna tıklayın.
3. Açılan pencerede **Seçenek Grubu Adı, Görüntülenecek Ad** ve **Grubu Kodu** alanlarını doldurun, kaydedin.
4.

    <div align="left" data-with-frame="true"><figure><img src="../../../.gitbook/assets/image (2).png" alt="" width="116"><figcaption></figcaption></figure></div>
5. Seçenek grubu oluşturduktan sonra, ilgili seçeneğin detay sayfasına gidin ve **Seçenek Grubu** alanından oluşturduğunuz grubu seçerek seçeneği bu gruba bağlayın.

Bu şekilde televizyon ürününe ait varyant seçeneklerini düzenli bir yapı içinde yönetebilirsiniz.



#### :arrow\_forward:<mark style="color:$info;">Seçenek ve Özellik Aralarındaki Fark Nedir?</mark>

**Özellikler**, ürünün teknik veya açıklayıcı niteliklerini ifade eder. Ürünü tanımlar ancak fiyat veya stokta farklılık oluşturmaz.

**Seçenekler** ise ürünün farklı versiyonlarını oluşturmak için kullanılır. Genellikle fiyat veya stokta farklılık yaratan bilgiler seçenek olarak tanımlanır.

{% hint style="info" %}
Alan tanımlarken şu kuralı kullanabilirsiniz: Ürünün farklı bir versiyonunu oluşturuyorsa **seçenek**, yalnızca ürün bilgisini tanımlıyorsa **özellik** olarak tanımlayın.
{% endhint %}

> Örneğin televizyon ürünü için **Enerji Sınıfı**, **Garanti Süresi** veya **Model Yılı** gibi bilgiler genellikle **özellik** olarak tanımlanır. Bu bilgiler ürünü tanımlar ancak çoğu senaryoda farklı bir varyant oluşturmaz.
>
> Buna karşılık **Ekran Boyutu**, **Renk** veya **Çözünürlük** gibi alanlar genellikle **seçenek** olarak tanımlanır. Bu alanların farklı değerleri ürünün farklı versiyonlarını oluşturabilir ve fiyat veya stok bilgisini etkileyebilir.
>
> Ancak bu ayrım tamamen sizin ürün modelleme tercihinize bağlıdır. Örneğin bazı işletmeler için **Enerji Sınıfı** ürün fiyatını etkileyen bir varyant olabilir. Böyle bir durumda bu alanı **seçenek** olarak tanımlayabilirsiniz.

Lidia PIM’de ürün veri modelinizi iş ihtiyaçlarınıza göre esnek şekilde kurgulayabilir, hangi alanların **özellik** hangi alanların **seçenek** olacağına siz karar verebilirsiniz.

#### :arrow\_forward:<mark style="color:$info;">Özellik nasıl oluşturulur?</mark>

{% stepper %}
{% step %}
**Ayarlar > Katalog > Özellikler sayfasına gidin.**
{% endstep %}

{% step %}
**Özellik Ekle butonuna tıklayın.**

<table data-view="cards"><thead><tr><th></th><th data-hidden data-card-cover data-type="image">Cover image</th></tr></thead><tbody><tr><td><p>Açılan modalda:</p><ul><li><strong>Özellik Adı</strong> → Zorunlu</li><li><strong>Özellik Kodu</strong> → Zorunlu</li><li><strong>Özellik Grubu</strong> → Opsiyonel</li></ul><p>Bu alanlar doldurulduktan sonra <strong>Devam Et</strong> butonuna tıklayın.</p><p>Özellik oluşturulur ve detay sayfasına yönlendirilirsiniz.</p></td><td data-object-fit="fill"><a href="../../../.gitbook/assets/Ekran görüntüsü 2026-03-04 003712.png">Ekran görüntüsü 2026-03-04 003712.png</a></td></tr></tbody></table>
{% endstep %}

{% step %}
**Detay sayfasında ilgili özelleştirmeleri yapın.**

<table data-view="cards"><thead><tr><th></th><th data-hidden data-card-cover data-type="image">Cover image</th></tr></thead><tbody><tr><td><p></p><ul><li>Veri Tipi seçilir</li><li>Gerekirse özellik grubu bağlanır</li><li>Seçim tipindeyse değerler eklenir</li></ul><p>Kaydedin.</p></td><td data-object-fit="fill"><a href="../../../.gitbook/assets/Ekran görüntüsü 2026-03-04 123437.png">Ekran görüntüsü 2026-03-04 123437.png</a></td></tr></tbody></table>
{% endstep %}
{% endstepper %}

