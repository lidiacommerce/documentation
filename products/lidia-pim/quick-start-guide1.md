---
description: >-
  Lidia PIM’e hoş geldiniz. Bu rehber, ilk ürününüzü sisteme sorunsuz şekilde
  ekleyebilmeniz için gerekli temel adımlarda size yol göstermek amacıyla
  hazırlanmıştır.
---

# Quick Start Guide

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

## :rocket:<mark style="color:$primary;background-color:purple;">Veri modelinizi inşa edin</mark>

Lidia PIM’de ürünlerinizi sorunsuz yönetebilmek için ilk ve en kritik adım veri şemasını doğru şekilde kurgulamaktır. Doğru yapılandırılmış bir veri şeması, benzer ürünleri düzenli bir yapı altında toplar ve ürün verisinin kategori bazında kontrollü ve sürdürülebilir şekilde ilerlemesini sağlar.

#### :arrow\_forward: <mark style="color:$info;">Veri Şeması Nedir?</mark>

Veri şeması, ürünleriniz için hangi bilgilerin tutulacağını ve bu bilgilerin hangi kurallara göre yönetileceğini belirleyen temel veri modelidir.

Basitçe ifade etmek gerekirse veri şeması:

* ürün kartında hangi alanların görüneceğini belirler
* bu alanların veri tipini tanımlar
* hangi bilgilerin zorunlu olduğunu kontrol eder
* benzer ürünlerin aynı yapıda yönetilmesini sağlar

Veri şeması sayesinde ürünleriniz rastgele değil, tanımlı ve kontrol edilen bir yapı içinde ilerler.

> **Örneğin** benzer ürünler için her seferinde yeni alanlar tanımlayıp yeni kural setleri oluşturmak yerine, oluşturduğunuz televizyon veri şemasını hem televizyon hem de HD televizyon ürünleri için kullanabilirsiniz. İhtiyaç duyduğunuz durumlarda ise bu ürün grupları için ayrı veri şemaları tanımlayarak her birini kendi alan ve kural yapısıyla yönetebilirsiniz.&#x20;

#### :arrow\_forward: <mark style="color:$info;">Neden Gereklidir?</mark>

Lidia PIM’de ürün verisinin sağlıklı ilerleyebilmesi için kategori, havuz ve ürün yapıları veri şemasına bağlı çalışır.

Veri şeması sayesinde:

* ürün verisi standart bir yapıda toplanır
* zorunlu alanlar kontrol altına alınır
* hatalı veya eksik veri girişleri önlenir
* ürün grupları kategori bazında doğru şekilde yönetilir

