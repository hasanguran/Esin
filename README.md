# Esin — ikas Studio teması

![Esin](images/kapak.png)

Esin, ayakkabı ve moda mağazaları için hazırlanmış bir ikas Studio teması. Bu sayfa, editörde ya da panelde yaptığın bir ayarın sitede neyi değiştirdiğini görsellerle gösterir.
*Esin is an ikas Studio theme for footwear and fashion stores. This page shows what each editor or panel setting changes on the site.*

**Canlı önizleme / Live preview:** https://qxwqy-themes.myikas.com/

---

## 1. Beden tablosu · Size guide

Ürün sayfasındaki "Beden Tablosu" bağlantısı, ürüne uyan tabloyu kendisi seçer.
*The size guide link picks the right table for each product.*

![Hangi tablo açılır](images/beden-tablosu-akis.png)

**Editörde nereden açılır:** Ürün Detay → Beden tablosu → Beden tabloları → Beden Tablosu → Tablo.
Tablo adını, bedenleri ve ölçüm şemasını buradan girersin. Hangi kategorilerde açılacağını "Hangi ürünlerde açılır" bölümünden seçersin.
*Editor: Product detail → Size guide → Size tables → Size table.*

![Beden tablosu: editör → site](images/editor-02-beden-tablosu.png)

**Panelde ürüne özel tablo:** Ürünlerde bir özel alan aç (tablo, görsel ya da HTML) ve editörde Ürün Detay → Beden tablosu → "Ürüne özel tablo (özel alan)" ayarından bu alanı seç. Özel alanı dolu olan üründe yalnız o tablo gösterilir, temadaki tablolar çıkmaz. Alanı boş ürünlerde temadaki tablolar geçerlidir.
*Panel: create a custom field, then pick it in Product detail → Size guide → "Product-specific table". A filled field overrides the theme tables for that product.*

![Özel alan → beden tablosu](images/panel-03-ozel-alan-beden-tablosu.png)

Sitede seçilen beden tabloda vurgulanır. Ölçüler cm ya da inç olarak gösterilir. "Nasıl ölçülür?" sekmesi ölçüm adımlarını anlatır. Telefonda tablo tek bedenin ölçülerini gösterir.
*The selected size is highlighted, units switch between cm and inch, and phones show one size at a time.*

![Beden tablosu görünümleri](images/beden-tablosu-gorunumler.png)

> Bedenleri aralarına boşluk koyarak yaz (`36 37 38`). Ürünlerdeki beden adlarıyla aynı yazılmalı.
> *Write sizes separated by spaces, exactly as in your products.*

---

## 2. Panel → site · Admin panel → storefront

Panele girdiğin bilgi siteye otomatik olarak yansır.
*Data entered in the admin panel appears on the site automatically.*

![Panel → site](images/panel-01-fiyat-marka-renk-stok.png)

| Panelde | Sitede |
|---|---|
| 1 · İndirimli fiyat | Kırmızı fiyat, üstü çizili eski fiyat ve indirim badge'i |
| 2 · Varyant renk kodu | Ürün sayfasında renk seçeneği |
| 3 · Marka | Kartta ve ürün sayfasında marka adı |
| 4 · Özel alan | Yalnız o ürüne ait beden tablosu |

*1 Sale price → red price and discount badge · 2 Color code → color swatch · 3 Brand → brand name · 4 Custom field → product size chart*

---

## 3. Kombin · Shop the look

**Editörde nereden açılır:** Ana sayfa → Kombin (Shop the Look) → Etkileşim Noktası → İçerik.
Ürünü seçersin, noktanın yerini yüzde olarak girersin. Örnekte yatay %64, dikey %88. Nokta fotoğrafta tam bu konumda görünür.
*Pick a product and enter the hotspot position in percent (64 / 88).*

![Kombin](images/editor-03-kombin-noktasi.png)

---

## 4. Sepet · Cart

**Editörde nereden açılır:** Üst Bar → Sepet.
Sepet tipini, ücretsiz kargo sınırını, önerilen ürünleri ve kasa önü ürünlerini buradan seçersin.
*Header → Cart: cart type, free shipping threshold, recommended and add-on products.*

![Sepet](images/editor-04-sepet-cekmecesi.png)

> Ücretsiz kargo sınırı, paneldeki kargo kuralıyla aynı tutar olmalı.
> *Use the same amount as your shipping rule in the panel.*

---

## 5. Ürün kartı · Product card

**Editörde nereden açılır:** Ürün Vitrini, Ürün Listeleme, Favorilerim gibi ürün listeleyen bölümler → Ürün kartı.
Görsel oranını, hover efektini, badge stilini ve sepete ekle butonunu bölüm bölüm ayarlarsın.
*Image ratio, hover effect, badge style and add to cart button, per section.*

![Ürün kartı](images/editor-05-urun-karti.png)

---

## 6. Üç hazır stil · Three style presets

**Editörde nereden açılır:** Herhangi bir bölüm → Yazı ve buton stili → Tema havası.
Seçtiğin stil başlık fontunu, köşeleri ve buton şeklini aynı anda değiştirir.
*One setting changes heading font, corners and button shape at once.*

![Üç hazır stil](images/uc-gorunum.png)

---

## 7. Mobil · Mobile

Telefonda alt menü, header'ın altında bir filtre çubuğu ve sticky sepete ekle çubuğu var. Beden tablosu ve sepet ekranın altından açılır.
*Bottom menu, filter bar, sticky add to cart; size guide and cart open from the bottom.*

![Mobil](images/mobil.png)

---

Dokümanlar ve görseller [CC BY 4.0](LICENSE) lisanslıdır. Temanın kaynak kodu bu depoda yer almaz.
*Docs and images are licensed under CC BY 4.0. The theme's source code is not part of this repository.*
