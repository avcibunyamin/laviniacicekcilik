# Antakya Çiçekçilik — Lavinia Flower

Antakya'daki butik çiçekçi Lavinia Flower'ın web sitesi.

🌐 **Canlı:** <https://antakyacicekcilik.com>

## İçerik

- Ürün koleksiyonları: canlı güller, buketler, nişan çiçekleri, saksı bitkileri, gelin çiçekleri, yapay çiçekler
- WhatsApp ile tek tıkla sipariş
- Açık / koyu tema, mobil menü
- SEO: `schema.org` yapılandırılmış verisi (Florist, Product, Offer), `sitemap.xml`, `robots.txt`

## Teknoloji

Derleme adımı olmayan tek sayfalık statik site: `index.html` + Tailwind CSS (CDN). GitHub Pages üzerinde, `CNAME` ile özel alan adından yayınlanır.

## Yapı

```text
index.html     Sayfanın tamamı
images/        Ürün ve banner görselleri
CNAME          antakyacicekcilik.com
sitemap.xml
robots.txt
```

## Yerelde çalıştırma

```sh
python3 -m http.server 8000
```

Ardından <http://localhost:8000>. `main` dalına yapılan push GitHub Pages'te otomatik yayınlanır.
