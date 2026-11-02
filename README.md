# Esin — ikas Studio teması · Kullanım kılavuzu

![Esin](images/kapak.png)

Esin; giyim, ayakkabı, çanta ve aksesuar mağazaları için hazırlanmış bir ikas Studio teması. Bu sayfa, temayı kuran mağaza sahibi için adım adım bir kullanım kılavuzu: her ayarın editörde nerede olduğunu, ne işe yaradığını ve sitede neyi değiştirdiğini anlatır.
*Esin is an ikas Studio theme for apparel, footwear, bag and accessory stores. This page is a step-by-step guide: where each setting is, what it does and what it changes on the site.*

**Canlı önizleme / Live preview:** https://qxwqy-themes.myikas.com/

---

## İçindekiler · Contents

0. [Başlarken](#0-başlarken--getting-started)
1. [Beden tablosu](#1-beden-tablosu--size-guide)
2. [Ürün kartı](#2-ürün-kartı--product-card)
3. [Panel → site](#3-panel--site--admin-panel--storefront)
4. [Kombin (shop the look)](#4-kombin--shop-the-look)
5. [Yan sepet](#5-yan-sepet--cart-drawer)
6. [Header ve menü](#6-header-ve-menü--header-and-menu)
7. [Ana sayfa bölümleri](#7-ana-sayfa-bölümleri--homepage-sections)
8. [Listeleme ve filtreler](#8-listeleme-ve-filtreler--product-listing-and-filters)
9. [Hazır stiller, renk ve animasyon](#9-hazır-stiller-renk-ve-animasyon--style-presets-colors-and-motion)
10. [Mobil](#10-mobil--mobile)
11. [Görsel boyutları](#11-görsel-boyutları--image-sizes)
12. [Sık sorulanlar](#12-sık-sorulanlar--faq)

---

## 0. Başlarken · Getting started

1. **Temayı aç:** ikas panelinde tema listesinden Esin → Düzenle. Editör açılır; solda sayfa ve bölümler, sağda seçili bölümün ayarları.
2. **Header'ı kur:** sayfanın en üstündeki Üst Bar bölümünü seç. Logo, menü ve sepet ayarları buradadır ([6. bölüm](#6-header-ve-menü--header-and-menu)).
3. **Hazır stili seç:** Üst Bar → Tema geneli (tüm sayfalar) altındaki köşe ve buton ayarlarını ya da bir bölümdeki "Tema havası" ayarını kullan ([9. bölüm](#9-hazır-stiller-renk-ve-animasyon--style-presets-colors-and-motion)).
4. **Ana sayfayı doldur:** hero, ürün slider, kategori karoları ve kombin bölümlerine görsel ve ürün listesi ekle ([7. bölüm](#7-ana-sayfa-bölümleri--homepage-sections)).
5. **Beden tablosunu kur:** Ürün sayfası → Ürün Detay → Beden tablosu ([1. bölüm](#1-beden-tablosu--size-guide)).
6. **Önizle ve yayınla:** editörün üstündeki cihaz seçiciyle masaüstü ve mobili kontrol et, sonra Yayınla.

*Open the theme, set up the header, pick a style, fill the homepage, set up the size guide, check desktop and mobile, publish.*

> Her bölümde ayarlar aynı sırayla gelir: Veri → İçerik → Düzen / Mobil → Renkler → Yazı ve buton stili → Animasyon → Boşluk ve görünürlük → Metinler. Sitedeki tüm yazılar "Metinler" grubundan değiştirilebilir.
> *Every section uses the same settings order. All visible texts can be changed under "Texts".*

---

## 1. Beden tablosu · Size guide

Ürün sayfasında beden seçiminin yanında "Beden tablosu" bağlantısı çıkar. Bağlantı, ürüne uyan tabloyu kendisi seçer. Bedeni olmayan üründe (çanta, cüzdan) bağlantı hiç görünmez.
*The size guide link picks the right table for each product and is hidden on products without sizes.*

### Hangi tablo açılır? · Which table opens?

![Hangi tablo açılır](images/beden-tablosu-akis.png)

Tema şu sırayla bakar:
1. Ürünün **özel alanı** doluysa → o ürüne ait tablo açılır (panelden girilir).
2. Değilse → ürünün **kategorisine** bağlı tema tablosu açılır.
3. O da yoksa → kategori seçilmemiş **genel** tablo açılır.
4. Ürünün bedeni yoksa → bağlantı gösterilmez.

*1 product custom field → 2 category table → 3 general table → 4 no sizes, no link.*

### Editörde tablo eklemek · Adding a table in the editor

**Nerede:** Ürün sayfası → Ürün Detay → Beden tablosu → Beden tabloları → "+" (Beden Tablosu).

![Beden tablosu: editör → site](images/editor-02-beden-tablosu.png)

Adım adım:
1. Ürün sayfasını aç, Ürün Detay bölümünü seç.
2. "Beden tablosu" grubunu aç, "Beden tabloları" listesine yeni öğe ekle.
3. **Tablo adı** yaz (ör. Kadın ayakkabı). Pencerede başlığın altında görünür.
4. **Bedenler** alanına sütunları aralarına boşluk koyarak yaz: `36 37 38 39 40 41` ya da `S M L XL`.
5. **Ölçü satırları** listesine her ölçü için bir satır ekle (ör. Ayak uzunluğu, UK, US). Değerleri bedenlerle aynı sırada yaz: `22,5 23 23,5 24,5 25 25,5`.
6. İstersen **Ölçüm şeması** görseli ve **Tablo altı notu** ekle.
7. "Hangi ürünlerde açılır" grubunda **Kategoriler** seç. Kadın ayakkabı tablosu için Kadın → Ayakkabı gibi.

*Add a table, name it, type the sizes, add one row per measurement, pick the categories.*

| Ayar | Ne yapar | Varsayılan |
|---|---|---|
| Tablo adı | Pencerede tabloyu adlandırır | Ayakkabı |
| Bedenler (tablonun sütunları) | Sütun başlıkları; ürünlerdeki beden adlarıyla aynı yazılmalı | 36 37 38 39 40 41 |
| Ölçü satırları | Tablonun satırları; sürükleyerek sıralanır | — |
| Ölçü adı (satır) | Satırın başlığı: Ayak uzunluğu, Göğüs, Bel, UK, US | Ayak uzunluğu |
| Değerler (satır) | Her bedene bir değer, aynı sırada | — |
| Değerler santimetre (satır) | Açık: cm, ziyaretçi inç seçebilir. Kapalı: UK / US / yaş gibi değerler olduğu gibi kalır | Açık |
| Nasıl ölçülür (satır) | Doluysa satır "Nasıl ölçülür?" sekmesinde numaralı adım olur | örnek metin |
| Ölçüm şeması | "Nasıl ölçülür?" sekmesinde adımların üstünde görünür | — |
| Tablo altı notu | Tablonun altında küçük açıklama; boşsa çıkmaz | örnek metin |
| Kategoriler | Tablo yalnız bu kategorilerdeki ürünlerde açılır. Üst kategori alt kategorileri de kapsar | — |
| Yalnız bedeni uyan ürünlerde aç | Açıkken aynı kategorideki bedensiz ürünlerde açılmaz | Açık |
| cm / inç düğmesi | Ziyaretçi cm ↔ inç geçişi yapabilir | Açık |
| Bağlantı yazısı (Ürün Detay) | Bağlantının ve pencerenin başlığı | Beden tablosu |

### Ürüne özel tablo (panelden) · Product-specific table

Bir ürünün kalıbı farklıysa, o ürüne ayrı tablo girebilirsin.

**Panelde:** Ürünler → Tanımlamalar → Özel Alanlar → yeni alan ekle (ör. "Beden Tablosu", tür: tablo, görsel ya da HTML). Sonra ürünü açıp bu alanı doldur.
**Editörde:** Ürün Detay → Beden tablosu → "Ürüne özel tablo (özel alan)" ayarından bu alanı seç.

![Özel alan → beden tablosu](images/panel-03-ozel-alan-beden-tablosu.png)

- Özel alanı dolu üründe yalnız o tablo görünür; temadaki tablolar o üründe çıkmaz.
- Alanı boş ürünlerde temadaki tablolar geçerlidir.

*Create a custom field in the panel, pick it in the editor. A filled field overrides the theme tables for that product.*

### Sitede · On the site

![Beden tablosu görünümleri](images/beden-tablosu-gorunumler.png)

- Ziyaretçinin seçtiği beden tabloda vurgulanır ("Seçili beden: 38").
- Ölçüler cm ya da inç olarak gösterilir.
- "Nasıl ölçülür?" sekmesi ölçüm şemasını ve adımları gösterir.
- Telefonda tablo alttan açılır ve tek bedenin ölçülerini gösterir.

*Selected size highlighted, cm / inch switch, "How to measure" tab, one size at a time on phones.*

### Sık yapılan hatalar · Common mistakes

| Sorun | Neden | Çözüm |
|---|---|---|
| Bağlantı görünmüyor | Ürünün bedeni yok ya da kategori seçilmemiş | Tabloya kategori ekle ya da kategorisiz bir genel tablo bırak |
| Seçilen beden vurgulanmıyor | Tablodaki beden adı üründekiyle farklı (ör. "38" ↔ "38 EU") | Bedenleri ürünlerdeki gibi yaz |
| Değerler kayık | Değer sayısı beden sayısından az/fazla | Her bedene tam bir değer yaz |
| Çantada beden tablosu açılıyor | "Yalnız bedeni uyan ürünlerde aç" kapalı | Ayarı aç |
| İnç çevirisi UK/US satırını bozuyor | Satırda "Değerler santimetre" açık | O satırda kapat |

---

## 2. Ürün kartı · Product card

**Nerede:** Ürün listeleyen her bölümde → Ürün kartı grubu (Ürün Vitrini, Ürün Listeleme, Favorilerim vb.). Her bölüm kendi kart ayarını taşır; ana sayfadaki slider ile kategori sayfası farklı görünebilir.
*Every product section has its own "Product card" group.*

![Ürün kartı](images/editor-05-urun-karti.png)

| Ayar | Seçenekler | Varsayılan | Sitede |
|---|---|---|---|
| Görsel oranı | Kare 1:1 · Dikey 3:4 · Portre 4:5 · Uzun 2:3 | Dikey 3:4 | Kart görselinin şekli |
| Görsel sığdırma | Doldur · Sığdır | Doldur | Doldur kenarları kırpabilir; Sığdır görselin tamamını gösterir |
| Hover efekti | İkinci görsel · Yakınlaştırma · Yok | İkinci görsel | Fareyle üzerine gelince ürünün 2. görseli açılır |
| Üzerine gelince beden seçenekleri | Açık / Kapalı | Açık | Hover'da bedenler çıkar, tek tıkla sepete eklenir |
| Sepete ekle butonunu göster | Açık / Kapalı | Açık | — |
| Sepete ekle görünümü | Kartın altında buton · Görsel üstünde (hover) | Kartın altında | — |
| Renk seçeneklerini göster | Açık / Kapalı | Açık | Kartın altında renk noktaları |
| Marka adını göster | Açık / Kapalı | Açık | Ürün adının üstünde marka |
| Son adet uyarısı eşiği | sayı | 3 | Stok bu sayıya inince "Son X adet" badge'i |
| Kart stili | Çerçevesiz · Kenarlıklı · Zeminli | Çerçevesiz | — |
| Rozet stili | Dolu · Çerçeveli · Sadece metin | Dolu | Badge görünümü |
| Metin hizası | Sola hizalı · Ortalı | Sola hizalı | — |

Kartta görünen badge'ler (sırayla): **Tükendi** → **İndirim %** → **Yeni** → **Son X adet**. Yazıları Metinler grubundan değişir ("Rozet: indirim", "Rozet: yeni" …).
*Badges: sold out, discount %, new, low stock. Their texts are editable.*

> İkinci görsel hover'ı için üründe en az 2 görsel olmalı. Telefonda hover yoktur; kart ilk görselle kalır.
> *Second-image hover needs at least 2 product images. Phones have no hover.*

---

## 3. Panel → site · Admin panel → storefront

Bu bilgiler editörde değil, ikas panelinde girilir; tema bunları kendisi gösterir.
*These are entered in the ikas admin panel, the theme shows them automatically.*

![Panel → site](images/panel-01-fiyat-marka-renk-stok.png)

| Panelde ne girersin | Nerede | Sitede ne olur | Boşsa |
|---|---|---|---|
| İndirimli fiyat | Ürün → Fiyat (indirimli satış fiyatı) | Kırmızı fiyat, üstü çizili eski fiyat, "-%X" badge'i, sepette "X TL tasarruf" | Normal fiyat |
| Renk kodu | Ürünler → Tanımlamalar → Varyant Türleri → Renk → değer → renk kodu | Ürün sayfasında ve kartta renk noktası | Renk adı yazı olarak çıkar |
| Stok | Ürün → Varyant → Stok | Eşiğin altında "Son X adet"; 0'da "Tükendi", beden pasif | — |
| "Yeni" etiketi | Ürün → Etiketler → "yeni" ya da "new" | Kartta "Yeni" badge'i | Badge çıkmaz |
| Marka | Ürün → Marka | Kartta ve ürün sayfasında marka adı | Marka satırı çıkmaz |
| Özel alan | Ürünler → Tanımlamalar → Özel Alanlar | O ürüne ait beden tablosu ([1. bölüm](#1-beden-tablosu--size-guide)) | Tema tablosu açılır |

> "Yeni" badge'i etiket adına bakar. Metinler grubundaki "Rozet: yeni" yazısını değiştirirsen (ör. "Yeni sezon"), aynı adla açılan etiket de çalışır.
> *The "New" badge follows a product tag named "yeni" / "new" or your custom badge text.*

---

## 4. Kombin · Shop the look

Bir fotoğrafın üstüne ürün noktaları (hotspot) koyarsın; ziyaretçi noktaya tıklayınca ürünü görür, tüm kombini tek seferde sepete ekleyebilir.
*Place product hotspots on a photo; visitors can add the whole look to the cart.*

**Nerede:** Ana sayfa → Kombin (Shop the Look) → Ürün noktaları → Etkileşim Noktası.

![Kombin](images/editor-03-kombin-noktasi.png)

Adım adım:
1. **Görsel** ekle (önerilen 1600×2000, 4:5). Telefonda farklı kadraj istiyorsan **Görsel (mobil)** ekle.
2. **Kombin ürünleri** listesine fotoğraftaki ürünleri seç (statik liste). Toplam fiyat ve "Tüm kombini sepete ekle" bu listeden hesaplanır.
3. **Ürün noktaları** listesine her ürün için bir nokta ekle, **Ürün** seç.
4. **Yatay konum** ve **Dikey konum**u yüzde olarak gir. 0/0 sol üst köşe, 100/100 sağ alt köşe. Örnekte yatay 64, dikey 88 → nokta ayakkabının üstünde.
5. Mobil görsel farklı kadrajdaysa **Mobilde farklı konum**u aç ve mobil yüzdelerini gir.

| Ayar | Seçenekler | Varsayılan |
|---|---|---|
| Nokta stili | Nokta · Artı · Numaralı | Nokta |
| Nabız efekti | Açık / Kapalı | Açık |
| Görsel tarafı | Medya solda · Medya sağda | Medya solda |
| Ürün listesini göster | Açık / Kapalı | Açık |
| Mobil ürün listesi | Alt alta liste · Yatay kaydırmalı kartlar | Alt alta liste |

> Noktalardaki ürünler ile Kombin ürünleri listesi aynı olmalı.
> *Hotspot products and the look product list should match.*

---

## 5. Yan sepet · Cart drawer

**Nerede:** Üst Bar → Sepet.

![Sepet](images/editor-04-sepet-cekmecesi.png)

| Ayar | Ne yapar | Varsayılan |
|---|---|---|
| Sepet tipi | Yan panel (drawer) ya da ayrı sepet sayfası | Yan panel |
| Ücretsiz kargo eşiği | Kargo çubuğu bu tutara göre dolar. 0 yazarsan çubuk gizlenir | 1500 |
| Sepette önerilen ürünler | "Bunu da beğenebilirsin" listesi | — |
| Kasa önü ürünleri | Tek dokunuşla eklenen küçük ürünler (çorap, bakım ürünü). Boşsa önerilerdeki en ucuz tek varyantlı ürünler kullanılır | — |

Sepette ayrıca: adet artır/azalt, kaldır ve "Geri al", "Başka beden ekle" çipleri, kampanya hediyesi ve hediye kartı satırı, tasarruf metni.
*Quantity, remove with undo, "add another size" chips, gift lines, savings text.*

> Ücretsiz kargo eşiği, paneldeki kargo kuralıyla aynı tutar olmalı. Tema kargo ücretini hesaplamaz, yalnız çubuğu gösterir.
> *Use the same amount as your panel shipping rule; the theme only shows the bar.*

---

## 6. Header ve menü · Header and menu

**Nerede:** Üst Bar (her sayfada aynı).

**Logo**
| Ayar | Not |
|---|---|
| Logo | Şeffaf PNG, önerilen yükseklik 80 px |
| Logo (koyu zemin için) | Şeffaf header'da kullanılır; boşsa normal logo beyaza çevrilir |
| SVG logo | Görsel logonun yerine geçer |
| Marka adı | Logo yoksa yazı logo olur; footer'daki büyük yazıda da kullanılır |
| Logo genişliği / yüksekliği (masaüstü, mobil) | Kare ya da dikey logoda yükseklik ayarını kullan |

**Düzen**
| Ayar | Seçenekler | Varsayılan |
|---|---|---|
| Yerleşim (masaüstü) | Logo solda · Logo ortada | Logo solda |
| Yerleşim (mobil) | Logo solda · Logo ortada | Logo ortada |
| Menü hizası | Sola · Ortada · Sağa | Sola |
| Yapışkan header (sticky) | Açık / Kapalı | Açık |
| Aşağı kaydırınca gizle | Açık / Kapalı | Açık |
| İlk section üzerinde şeffaf | Header hero'nun üstüne biner, kaydırınca dolar | Kapalı |

**Menü ve mega menü:** Menü öğeleri listesine öğe ekle, **Menü linki** seç. Linkin alt linkleri varsa mega menü açılır: alt linkler kolon başlığı, onların altındakiler kolon içeriği olur. Her öğeye **Rozet** (ör. "Yeni"), **Vurgulu link** (ör. Outlet), kolon görselleri ve bir **Promosyon kartı** (800×1000) eklenebilir.

**Duyuru bandı:** Mesajlar listesine link ekle; gösterim Kayan şerit ya da Dönen mesaj. Kapatılabilir, renkleri ayrı seçilir.

**Arama:** Arama ürün listesini "Arama" türünde ayarla; anlık sonuçlar buradan gelir. Öne çıkan ürünler yazmadan önce, Popüler aramalar çip olarak gösterilir.

*Logo, layout, sticky header, mega menu with badges and promo card, announcement bar, instant search.*

---

## 7. Ana sayfa bölümleri · Homepage sections

### Hero (Vitrin)
Tek görsel ya da video ile büyük açılış alanı.
| Ayar | Seçenekler | Varsayılan |
|---|---|---|
| Yerleşim | Tam ekran görsel · Split – görsel solda · Split – görsel sağda | Tam ekran |
| Yükseklik | Tam ekran · Büyük · Orta (mobilde + İçeriğe göre) | Tam ekran |
| Görsel oranı | ör. 16:9; girilirse yükseklik ayarının yerine geçer | — |
| İçerik konumu | 9 konum (mobilde Üst / Orta / Alt) | Sol alt |
| Metin rengi | Açık metin · Koyu metin | Açık |
| Karartma rengi / yoğunluğu | görsel üstünde okunurluk için | siyah, 30 |
| Video (masaüstü / mobil) | Doluysa görselin yerine oynar | — |

Görsel: masaüstü 2400×1350 (16:9), mobil 1080×1350 (4:5).

### Hero slider (Vitrin Slider)
Slaytlar listesine slayt ekle; her slaytın görseli, başlığı ve 2 butonu var.
| Ayar | Seçenekler | Varsayılan |
|---|---|---|
| Gösterge | Süre çubukları · Noktalar · Sayı (01 / 03) | Süre çubukları |
| Geçiş efekti | Solma + yakınlaşma · Kaydırma | Solma + yakınlaşma |
| Ken Burns (yavaş yakınlaşma) | Açık / Kapalı | Açık |
| Okları göster | Açık / Kapalı | Açık |

> Sayfada yalnız bir bölümde "Sayfa başlığı (H1)" açık olmalı (SEO).

### Ürün slider (Ürün Vitrini)
4 sekmeye kadar ürün listesi (ör. Yeni gelenler / Çok satanlar). Her sekmeye başlık ve ürün listesi seç.
| Ayar | Seçenekler | Varsayılan |
|---|---|---|
| Yerleşim | Slider · Grid | Slider |
| Kolon sayısı | sayı | 4 |
| En fazla ürün | sayı | 12 |
| Mobilde kart sayısı | 1 · 1,5 · 2 kart | 2 kart |
| Sonraki kart kenardan görünsün | Açık / Kapalı | Açık |

Kart ayarları için [2. bölüm](#2-ürün-kartı--product-card).

### Diğer bölümler
Kategori karoları (1200×1500), marka logoları, müşteri yorumları, UGC, öncesi/sonrası, zaman çizelgesi, bülten, SSS gibi bölümler "Bölüm ekle" listesinden eklenir. Hepsi aynı ayar sırasını kullanır.

---

## 8. Listeleme ve filtreler · Product listing and filters

**Nerede:** Kategori sayfası → Ürün Listeleme.

| Ayar | Seçenekler | Varsayılan |
|---|---|---|
| Filtre yerleşimi (masaüstü) | Sol sidebar · Üst bar · Sadece çekmece | Sol sidebar |
| Kolon sayısı | sayı | 3 |
| Kolon değiştirici | Ziyaretçi 2 / 3 / 4 kolon seçer | Açık |
| Mobilde kolon | 1 · 2 | 2 |
| Sayfalama | Sayfalama · Daha fazla yükle · Sonsuz kaydırma | Daha fazla yükle |
| Renk / görsel seçenek görünümü | Yuvarlak + ipucu · Yuvarlak + yazı · Sadece yazı | Sadece yazı |
| Sonuç yoksa önerilen ürünler | Boş sonuçta gösterilecek liste | — |

Filtreler ikas panelindeki filtre ayarlarından gelir; tema yalnız görünümünü belirler. Telefonda filtre ve sıralama sticky bir çubuktan alttan açılır.
*Filters come from the panel; the theme controls their layout.*

---

## 9. Hazır stiller, renk ve animasyon · Style presets, colors and motion

![Üç hazır stil](images/uc-gorunum.png)

**Tema havası** (her bölümde, Yazı ve buton stili grubunda): Varsayılan · Editorial · Minimal Lüks · Street / Bold. Seçtiğin stil başlık fontunu, köşeleri, buton şeklini ve başlık harflerini birlikte değiştirir.

**Tüm site için:** Üst Bar → Tema geneli (tüm sayfalar)
| Ayar | Seçenekler | Varsayılan |
|---|---|---|
| Köşeler (tüm site) | Temaya göre · Keskin · Yumuşak · Yuvarlak | Temaya göre (keskin) |
| Buton stili (tüm site) | Temaya göre · Dolu · Çerçeveli · Altı çizili · Hap | Temaya göre (dolu) |
| Buton hover efekti | Varsayılan · Metin kayması · Dolgu kayması · Sade | Varsayılan |
| Sayfa maksimum genişliği | px | 1600 |
| Kenar boşluğu (masaüstü / mobil) | px | 48 / 16 |
| Animasyon seviyesi | Kapalı · Hafif · Yoğun | Yoğun |
| Görünme efekti | Yukarı süzülme · Perde açılışı · Bulanıklıktan netleşme | Yukarı süzülme |
| Sayfa geçiş animasyonu | Açık / Kapalı | Açık |
| Sepete uçuş animasyonu | Açık / Kapalı | Açık |
| Özel imleç | Yalnız fareli cihazlarda ve Yoğun seviyede | Kapalı |

**Tek bölüm için** (her bölümde aynı): Başlık fontu, Gövde fontu, Başlık ölçeği, Başlık harfleri, Köşeler, Buton stili, renkler (arka plan, CTA, hover), Animasyon (Tema ayarı · Sade · Kapalı), Mobilde animasyon, Üst / Alt boşluk (Yok · Küçük · Orta · Büyük), Görünürlük (Her yerde · Sadece masaüstü · Sadece mobil).

> "Temaya göre" yazan her ayar genel ayarı izler. Bir bölümü farklı yapmak istediğinde yalnız o bölümde değiştir.
> *"Theme default" follows the global setting; override per section only when needed.*
> Hareket azaltma tercihi açık ziyaretçilerde animasyonlar otomatik kapanır.

---

## 10. Mobil · Mobile

![Mobil](images/mobil.png)

- **Alt navigasyon:** Üst Bar → Tema geneli → Mobil alt navigasyon (açık).
- **Sticky sepete ekle çubuğu:** Ürün Detay → Mobil → Mobilde alttan sabit sepet çubuğu (açık).
- **Filtre çubuğu:** listeleme sayfasında header'ın altında sticky.
- **Beden tablosu ve sepet** ekranın altından açılır.
- **Ayrı mobil görsel:** hero, slider ve kombinde "Görsel (mobil)" alanı; boşsa masaüstü görseli kullanılır.
- **Mobil menü kartı:** Üst Bar → Mobil menü tanıtımı (1200×800).

*Bottom navigation, sticky add to cart, sticky filter bar, bottom sheets, separate mobile images.*

---

## 11. Görsel boyutları · Image sizes

| Yer | Önerilen boyut | Oran |
|---|---|---|
| Hero / slider (masaüstü) | 2400×1350 | 16:9 |
| Hero / slider (mobil) | 1080×1350 | 4:5 |
| Ürün görseli | 1200×1600 | 3:4 (kart varsayılanı) |
| Kategori karosu | 1200×1500 | 4:5 |
| Kombin görseli | 1600×2000 | 4:5 |
| Mega menü promosyon kartı | 800×1000 | 4:5 |
| Mobil menü kartı | 1200×800 | 3:2 |
| Logo | 80 px yükseklik, şeffaf PNG ya da SVG | — |

Görselin kesilmesini istemiyorsan o bölümde **Görsel sığdırma → Sığdır** seç.
*Pick "Contain" to show the whole image without cropping.*

---

## 12. Sık sorulanlar · FAQ

**Beden tablosu bazı ürünlerde çıkmıyor.**
Ürünün kategorisi bir tabloya bağlı değil ya da ürünün bedeni yok. Kategorisiz bir genel tablo eklersen tüm bedenli ürünlerde açılır.

**Renk noktası yerine renk adı yazıyor.**
Panelde varyant rengine renk kodu girilmemiş. Ürün Detay → Varyant stili "Renk" seçili olmalı.

**"Yeni" badge'i görünmüyor.**
Ürüne "yeni" ya da "new" etiketi ekle. Ürün tükendiyse "Yeni" yerine "Tükendi" görünür.

**Kartta ikinci görsel açılmıyor.**
Üründe tek görsel var ya da kartın Hover efekti "İkinci görsel" değil.

**Kargo çubuğu yanlış tutarı gösteriyor.**
Üst Bar → Sepet → Ücretsiz kargo eşiği, paneldeki kargo kuralıyla aynı olmalı.

**Header hero'nun üstünde okunmuyor.**
Logo (koyu zemin için) ekle ya da hero karartma yoğunluğunu artır.

**Bir bölüm telefonda görünmesin.**
O bölümde Boşluk ve görünürlük → Görünürlük → Sadece masaüstü.

**Site yazılarını değiştirmek istiyorum.**
Her bölümün en altındaki Metinler grubunda; ortak yazılar (bildirimler, sepet) Üst Bar'da.

---

Dokümanlar ve görseller [CC BY 4.0](LICENSE) lisanslıdır. Temanın kaynak kodu bu depoda yer almaz.
*Docs and images are licensed under CC BY 4.0. The theme's source code is not part of this repository.*
