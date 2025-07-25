---
description: >-
  Bu ay boyunca Lidia platformunda fonksiyonellik ve kullanıcı deneyimini
  iyileştiren en son güncellemeleri ve geliştirmeleri keşfedin.
cover: ../../../.gitbook/assets/1 (7).png
coverY: 0
---

# Lidia 2.7.x sürüm notları

Bu ayki sürüm, Lidia platformunun çeşitli bileşenlerinde önemli güncellemeler içeriyor. Bu bileşenler arasında **Console, Merchant Console, Ürün Bilgi Yönetimi (PIM) sistemleri ve Lidia Commerce Engine**bulunuyor. Yapılan iyileştirmeler, iş akışlarını optimize etmeyi ve tüm platform kullanıcıları için daha akıcı bir deneyim sunmayı amaçlıyor.

{% hint style="info" %}
🔎 **Sürüm Kodları Hakkında**\
Bu dokümanda, Lidia platformunun farklı bileşenleri için sürüm kodlarını bulabilirsiniz:

* **LC:** Lidia Console – Ana yönetim konsoluna yönelik iyileştirmeler ve hata düzeltmeleri.
* **LMC:** Lidia Merchant Console – Satıcı araçları ve iş akışlarına özel güncellemeler.
* **LP:** Lidia PIM (Ürün Bilgi Yönetimi) – Ürün veri yönetimiyle ilgili geliştirmeler ve yeni özellikler.
* **LCE:** Lidia Commerce Engine - Lidia Commerce Engine'e eklenen mikroservis geliştirmeleri

Bu kodlar, platform genelindeki iyileştirmelerin hangi alanlara yönelik olduğunu takip etmenize yardımcı olur.
{% endhint %}

***

## <mark style="color:purple;">**Sürüm 2.7**</mark>

### Yeni Geliştirmeler

### 🎯 **Fatura Yönetimi Geliştirmeleri**

#### **Satıcıların faturalarının yöneticiler tarafından onay ve reddedilebilmesi** Sürüm Tarihi: 22/07/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.7.1.1 - LMC-2.7.1.1</mark>

Platformda satıcıların yüklediği faturaların kontrol edilebilmesi ve kayıt dışı evrak girişlerinin önlenebilmesi amacıyla, fatura yükleme ve onay süreçleri fatura merkezi başlığı altında konumlandırılmıştır. Bu geliştirme ile birlikte satıcıların, sipariş veya iade faturalarını platform yöneticilerinin erişebileceği şekilde fatura merkezi üzerinden yükleyebilmesi sağlanmıştır. Yöneticiler bu faturaları sistem üzerinden görüntüleyerek onaylayabilir veya gerekçesiyle birlikte reddedebilir. Reddedilen faturalar satıcılar tarafından tekrar yüklenebilir. Böylelikle fatura paylaşımı ve kontrol süreçleri sistem üzerinde uçtan uca yönetilebilir hale getirilmiştir.



#### Satıcıların tüm faturaları tek bir yerden görüntüleyip yükleyebilmesi Sürüm Tarihi: 22/07/2025 Sürüm Numarası: <mark style="color:purple;">LMC-2.7.1.2</mark>

Satıcılar, fatura yükleme işlemlerini yalnızca ilgili sipariş detay sayfaları üzerinden gerçekleştirebiliyor; tüm faturalarını merkezi bir noktadan yönetemiyordu. Bu geliştirme ile birlikte satıcıların, sipariş ve iade faturalarını merkezi bir fatura sayfası üzerinden yükleyebilmesi sağlanmıştır. Ayrıca, iade işlemleri için iade fatura detaylarına özel bir fatura yükleme alanı eklenmiştir. Satıcılar artık nereden eklendiğinden bağımsız olarak tüm faturalarını tek bir ekranda görüntüleyebilir, mevcut belgeleri güncelleyebilir veya silebilir.





#### Tüm faturaların tek bir sayfadan görüntülenebilmesi Sürüm Tarihi: 22/07/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.7.1.2 - LMC-2.7.1.3</mark>

Faturalar, sistem üzerinde farklı ekranlarda listeleniyor; hem satıcılar hem de yöneticiler için faturalara erişim ve arama süreçleri dağınık ve yönetimi zor bir şekilde ilerliyordu. Bu durum, kontrol süreçlerinin yavaşlamasına ve işlem sürelerinin uzamasına neden olabiliyordu. Bu geliştirme ile birlikte tüm faturaların tek bir sayfa altında merkezi olarak görüntülenebilmesi sağlanmıştır. Sol menüde yer alan “Fatura Merkezi” başlığı altından erişilebilen bu ekran üzerinden yöneticiler, satıcı adı, fatura türü gibi filtrelerle arama yaparak ilgili faturaları görüntüleyebilir ve indirebilir. Satıcılar ise kendi faturalarını listeleyebilir, arama yapabilir, güncelleyebilir veya silebilir.&#x20;





### 🎯 **Raporlama Geliştirmeleri**

#### Stopaj tahsilat raporunun alınabilmesi Sürüm Tarihi: 22/07/2025 Sürüm Numarası: <mark style="color:purple;">LMC-2.7.1.4</mark>

Türkiye’de pazaryeri komisyonlarına stopaj kesintisi uygulanmakta; bu kesintilerin Gelir İdaresi Başkanlığı (GİB) sistemine beyan edilmesi yasal olarak satıcının sorumluluğundadır. Ancak bu beyanın hazırlanması süreci pazaryeri altyapı sağlayıcısı tarafından desteklenmelidir. Bu geliştirme ile birlikte Merchant Console üzerinden, satıcılara GİB formatına uygun stopaj beyan Excel dosyası oluşturma özelliği sunulmuştur. Satıcılar, dönem bazlı tahsilat verilerini “Raporlar” başlığı altındaki Stopaj Tahsilat Raporu ekranı üzerinden dışa aktarabilir; bu dosyayı GİB sistemine beyan sürecinde kullanabilir.





### 🎯 **Sistem Sağlığı Geliştirmeleri**

#### **Console üzerinden önbellek temizleme işleminin yapılabilmesi** Sürüm Tarihi: 22/07/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.7.1.3</mark>

Yöneticiler tarafından önbellek temizliği manuel olarak yapılamıyor; her projedeki cache mekanizmaları yalnızca teknik ekipler tarafından yönetiliyordu. Bu geliştirme ile birlikte Operasyonel İşlemler başlığı altında “Önbellek Temizliği” yeteneği eklenmiştir. Bu sayfada sistemde cache’e sahip olan veri kümeleri listelenir; yöneticiler ilgili rollere sahip olmaları durumunda bu önbelleği console üzerinden manuel olarak temizleyebilir. Böylece önbellek temizleme aksiyonu teknik ekiplere ihtiyaç duymadan daha çevik şekilde yönetilebilir hale gelmiştir.





### 🎯 **Finans Yönetimi Geliştirmeleri**



#### Hakediş kırılımlarında ödeme tipi bilgisinin gösterilmesi Sürüm Tarihi: 22/07/2025 Sürüm Numarası: <mark style="color:purple;">LMC-2.7.1.5 - LC-2.7.1.4</mark>

Hakediş kırılımlarında ilgili siparişlere ait ödeme aracı tipi bilgisi gösterilmiyordu. Bu geliştirme ile birlikte hakediş kırılım satırlarında, her siparişe ait ödeme aracı tipi (örneğin: kredi kartı, kapıda ödeme, havale) bilgisi de görüntülenebilir hale getirilmiştir. Böylece hem yöneticiler hem de satıcılar tahsilat verilerini daha detaylı inceleyebilir ; rapor ve muhasebe süreçlerini daha sağlıklı şekilde yürütebilir.





#### Satıcı hakedişlerinin dönem bazlı finans yönetimi altında konumlandırılması Sürüm Tarihi: 22/07/2025 Sürüm Numarası: <mark style="color:purple;">LMC-2.7.1.6</mark>

Satıcılar, hakedişlerini dönemsel bazda görüntüleyemiyor; vade ve dönemine göre oluşan hakediş bilgilerine sistematik olarak erişemiyordu. Bu geliştirme ile birlikte her satıcının belirlenen periyot ve vade yapılarına göre hakedişleri sistem tarafından otomatik olarak kayıt altına alınmakta ve satıcı panelindeki Finans Yönetimi > Hakedişler sayfası üzerinden dönem bazlı olarak görüntülenebilmektedir. Ayrıca, ilgili sayfalardaki dashboard yapısı ile satış, kampanya, kargo gibi maliyet kalemlerinin kırılımlarına da kolaylıkla ulaşılabilir hale gelmiştir.&#x20;





#### **Hakedişlerin dönem bazlı dışa aktarılabilmesi** Sürüm Tarihi: 22/07/2025 Sürüm Numarası: <mark style="color:purple;">LMC-2.7.1.7 - LC-2.7.1.5</mark>

Hakedişlere ait detaylar sistem üzerinde görüntülenebiliyor ancak bu veriler dönem bazlı olarak dışa aktarılamıyordu. Bu geliştirme ile birlikte her bir hakediş dönemine ait kırılım verilerinin, excel formatında dışa aktarılabilmesi sağlanmıştır. Yöneticiler ve satıcılar ilgili dönemi seçerek tüm hakediş kalemlerini ve detaylarını sistem üzerinden tek tıklamayla indirip, harici raporlamalarda kullanabilir.



#### Komisyon oranlarına tarih ve saat bazlı tanım yeteneği Sürüm Tarihi: 22/07/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.7.1.6</mark>

Komisyon oranı tanımlanırken, bu oranın geçerli olacağı tarih ve saat aralıkları belirlenemiyor; oranlar sadece manuel müdahale ile güncelleniyordu. Bu durum, dönemsel kampanyalar veya saatlik değişken stratejiler için sınırlayıcı oluyordu. Bu geliştirme ile birlikte komisyon oranlarına belirli bir başlangıç ve bitiş tarihi ile birlikte saat aralığı da tanımlanabilir hale gelmiştir. Böylece belirli kampanya dönemlerinde yalnızca belirlenen tarih ve saat aralığında geçerli olacak komisyon oranları tanımlanabilir. İlgili sürenin sona ermesi durumunda da sistem, otomatik olarak bir önceki geçerli oranı devreye alarak komisyon hesaplamalarını kesintisiz şekilde sürdürür.





### 🎯 **Satıcı Yönetimi Geliştirmeleri**

#### Satıcı kayıt sürecinde depo adresi tanımlama yeteneği Sürüm Tarihi: 22/07/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.7.1.7</mark>

Yöneticiler, sistem üzerinden manuel olarak satıcı tanımlarken satıcılara ait depo bilgisi ekleyemiyor; bu alan boş kalarak süreç tamamlanabiliyordu. Bu durum, lojistik süreçlerde satıcının depo adresini kendi panelinden kendisi eklemediği durumlarda eksik adres bilgisinden dolayı hata alınmasına olabiliyordu. Bu geliştirme ile birlikte yöneticiler, içeri başvuru dışındaki manuel satıcı tanımlama süreçlerinde ilgili satıcıya ait depo adresi bilgisini ekleyebilir. Depo bilgisi alanı zorunludur; boş şekilde yapılmasının önüne geçilmiştir Ayrıca, kayıt sonrası ilgili depo adresi bilgisi satıcı adına güncellenebilir şekilde düzenlenebilir.&#x20;



### İyileştirmeler

### 💡 **Kullanıcı Deneyimi İyileştirmeleri**

#### Ayarlar altındaki sayfaların yeni listeleme arayüzüne taşınması Sürüm Tarihi: 22/07/2025 Sürüm Numarası: <mark style="color:purple;">LC-2.7.1.8</mark>

Sol menüde yer alan Ayarlar başlığı altındaki bazı sayfalar hala eski listeleme ve arama altyapısını kullanıyor; bu sayfalarda kullanıcı deneyimi diğer sayfalar ile tutarsız kalıyordu. Bu geliştirme ile birlikte, ilgili sayfalar yeni nesil listeleme ve arama altyapısına geçirilmiş; tüm Ayarlar başlığı altındaki sayfaların aynı tasarım diline ve kullanıcı deneyimine sahip olması sağlanmıştır. Böylece filtreleme, sıralama ve veri yönetimi işlemleri daha hızlı ve tutarlı bir yapı üzerinden gerçekleştirilebilir hale gelmiştir.













***

{% hint style="info" %}
### **Hata Düzeltmeleri**

* \-
{% endhint %}





Bu güncellemeler, Lidia ürün ailesinin gelişimini hızlandırmak, pazar ve müşteri ihtiyaçlarına uyum sağlamak ve sürdürülebilirliği artırmak için tasarlanmıştır. Tüm kullanıcılar için daha sorunsuz ve verimli bir deneyim sunmayı hedefliyoruz. Gelecek ay daha fazlası için bizi takip etmeye devam edin!



\
\
