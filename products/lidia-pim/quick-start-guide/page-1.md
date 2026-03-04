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



* **Özellik Veri Tipi Nedir?**

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

* **Özellik Grubu Nedir?**

**Özellik grubu**, benzer özellikleri bir arada düzenlemek için kullanılır. Özellik grupları, PIM kullanıcısı olarak ürün verinizi daha düzenli yönetmenize yardımcı olur. İlgili özellikleri aynı başlık altında toplayarak hem ürün girişini hem de veri yönetimini kolaylaştırabilirsiniz.

> Örneğin televizyon ürünü için **Ekran Boyutu, Çözünürlük ve Panel Teknolojisi** gibi özellikleri oluşturduysanız, bu özellikleri **Ekran Özellikleri** adlı bir özellik grubu altında toplayın. Bu şekilde ilgili özellikleri aynı başlık altında düzenleyebilir ve ürün kartında daha düzenli bir yapı oluşturabilirsiniz.



* **Özellik Nasıl Oluşturulur?**

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

* Veri Tipi seçilir
* Gerekirse özellik grubu bağlanır
* Seçim tipindeyse değerler eklenir

Kaydedin.
{% endstep %}
{% endstepper %}
