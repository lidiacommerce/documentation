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

<table><thead><tr><th width="244.44439697265625">Rol Adı</th><th width="436.266845703125">Rol Açıklaması</th></tr></thead><tbody><tr><td><strong>Guest</strong></td><td>Sisteme sınırlı erişimi olan kullanıcı rolüdür. Genellikle yalnızca belirli alanları görüntüleme yetkisine sahiptir ve düzenleme yetkisi bulunmaz.</td></tr><tr><td><strong>OrganizationUser</strong></td><td>Organizasyon içinde temel kullanıcı rolüdür. Yetkili olduğu modüllerde verileri görüntüleyebilir ve görev kapsamına göre sınırlı düzenleme işlemleri yapabilir.</td></tr><tr><td><strong>OrganizationAdmin</strong></td><td>Organizasyon seviyesinde yönetim yetkilerine sahip roldür. Kullanıcıları, rolleri ve organizasyon içindeki erişimleri yönetebilir.</td></tr><tr><td><strong>OrganizationOwner</strong></td><td>Organizasyonun en yüksek yetkili rolüdür. Organizasyon ayarlarını yönetebilir, kullanıcı ve rol yetkilerini düzenleyebilir ve tüm modüllere tam erişime sahiptir.</td></tr><tr><td><strong>CustomerSuccess</strong></td><td>Platform sağlayıcı ekipleri için kullanılan destek rolüdür. Müşteri organizasyonlarını inceleyebilir, sorun çözme ve destek süreçlerinde gerekli erişimlere sahiptir.</td></tr><tr><td><strong>ApplicationAdmin</strong></td><td>Uygulama veya platform seviyesinde yönetim yetkisine sahip roldür. Sistem konfigürasyonları, uygulama ayarları ve platform genelindeki yönetim işlemlerini gerçekleştirebilir.</td></tr></tbody></table>

* [x] Rol bazında hangi modüllerin görüntülenebileceği ve hangi alanların düzenlenebileceği ayrı ayrı belirlenebilir. Gerekli durumlarda, daha yüksek yetkilere sahip kullanıcılar bu rol yetkilerini konfigüre ederek erişim kapsamını güncelleyebilir.

