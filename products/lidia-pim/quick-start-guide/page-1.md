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

Televizyon örneğinden devam edelim, önce bir özellik tanımlayalım ve veri tipini 'çoklu seçim' olarak seçelim:

* **Özellik:** Enerji Sınıfı
* **Veri Tipi:** Çoklu Seçim
* **Tanımlanan Değerler:** A, B, C, D, E, F

Bu sayede ürün oluşturma sırasında kullanıcı yalnızca tanımladığınız değerler arasından seçim yapabilir. Yeni değer girilemez; yalnızca mevcut seçenekler kullanılabilir.

Bu yöntemle veri girişini kontrol altında tutarsınız ve tutarlı bir ürün yapısı oluşturursunuz.
