# Esin — ikas Studio theme

![Esin](images/kapak.png)

Giyim, ayakkabı, çanta ve aksesuar mağazaları için bir ikas teması. Bu sayfa temanın **öne çıkan kurgularını** görsellerle anlatır: editörde ya da panelde ne yaparsan sitede ne olur.
*A footwear & fashion theme for ikas. This page shows the key setups: what you do in the editor or admin panel, and what happens on the site.*

**Canlı önizleme / Live preview:** https://qxwqy-themes.myikas.com/

---

## 1. Beden tablosu · Size guide

Temanın en önemli özelliği. Ürün sayfasındaki "Beden Tablosu" bağlantısı, ürüne uyan tabloyu kendisi seçer.
*The size guide picks the right table for each product by itself.*

![Hangi tablo açılır](images/beden-tablosu-akis.png)

**Editörde kurulum:** Ürün Detay → Beden tabloları → Beden Tablosu ekle → tablo adı, bedenler (`35 36 37 …`), ölçü satırları, ölçüm şeması, kategoriler.

![Beden tablosu: editör → site](images/editor-02-beden-tablosu.png)

**Panelde ürüne özel tablo:** Özel alan (tablo / görsel / HTML) doluysa her şeyden önce o gösterilir.

![Özel alan → beden tablosu](images/panel-03-ozel-alan-beden-tablosu.png)

Sitede: seçili beden vurgulu tablo, cm / inç, "Nasıl ölçülür?" sekmesi, mobilde tek beden görünümü.

![Üç görünüm](images/beden-tablosu-gorunumler.png)

> Bedenleri boşlukla yaz (`36 37 38`), virgül ondalık sayılır. Ürün beden adlarıyla birebir aynı olmalı.

---

## 2. Panel → site · Admin panel → storefront

Ürünü panelde bir kez güncelle, site takip etsin.
*Update the product once in the panel; the site follows.*

![Panel → site](images/panel-01-fiyat-marka-renk-stok.png)

| Panelde | Sitede |
|---|---|
| 1 · İndirimli fiyat | Kırmızı fiyat, üstü çizili eski fiyat, "-%60" badge'i |
| 2 · Marka | Ürün adının üstünde |
| 3 · Renk kodu | Kart, filtre ve üründe renk seçeneği |
| 4 · Stok | Bedenler, "Son 3 adet!", "Gelince haber ver" |
| 5 · "Yeni" etiketi | Kartta "Yeni" badge'i |
| 6 · Özel alan | Ürüne özel beden tablosu, ürün özellikleri |

Renk kodu girilmezse renk seçeneği gri görünür:

![Renk kodu → renk seçeneği](images/panel-02-renk-kodu.png)

---

## 3. Shop the look (kombin)

Editörde ürün seçilir, konumu yüzde olarak girilir (x 64 / y 88); hotspot fotoğrafta o noktada görünür. "Tüm kombini ekle" tüm ürünleri sepete ekler.
*Pick a product and enter its position in % (x 64 / y 88); the hotspot appears at that spot. "Add the whole look" adds every item to the cart.*

![Shop the look](images/editor-03-kombin-noktasi.png)

---

## 4. Yan sepet · Cart drawer

Üst Bar → Sepet: sepet tipi, ücretsiz kargo eşiği, önerilen ürünler, kasa önü ürünleri.
*Free-shipping bar, "add another size", one-tap add-ons.*

![Yan sepet](images/editor-04-sepet-cekmecesi.png)

> Ücretsiz kargo eşiği paneldeki kargo kuralıyla aynı tutar olmalı.

---

## 5. Ürün kartı · Product card

Her ürün listeleyen bölümde: görsel oranı, hover efekti, badge stili, sepete ekle butonu.
*Card ratio, hover, badge style and quick add, per section.*

![Ürün kartı](images/editor-05-urun-karti.png)

---

## 6. 3 hazır stil · 3 ready styles

Herhangi bir bölüm → Yazı ve buton stili → Tema havası. Seçilen stil başlık fontunu, harf biçimini, köşe yuvarlaklığını ve buton şeklini birlikte değiştirir; tüm mağaza ya da tek bölüm için.
*Each style changes heading font, letter case, corners and button shape together — for the whole store or one section.*

![3 hazır stil](images/uc-gorunum.png)

---

## 7. Mobil · Mobile

Alt menü, sticky filtre/sıralama çubuğu, sabit "Sepete ekle" butonu, alttan açılan beden tablosu ve sepet.
*Bottom nav, sticky add to cart, size guide and cart as sheets.*

![Mobil](images/mobil.png)

---

Dökümanlar ve görseller [CC BY 4.0](LICENSE). Temanın kaynak kodu bu depoda değildir.
*Docs and images under CC BY 4.0. The theme's source code is not part of this repository.*
