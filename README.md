# realtry.app

Real TRY'nin tanıtım sayfası, gizlilik politikaları ve uygulamanın okuduğu veri dosyası.
Derleme adımı yok.

| Adres | Dosya |
|---|---|
| `realtry.app/` | `index.html` |
| `realtry.app/gizlilik` | `gizlilik.html` |
| `realtry.app/privacy` | `privacy.html` |
| `realtry.app/data.json` | uygulamanın okuduğu veri (**otomatik üretilir**) |
| `realtry.app/sources.json` | ENAG aylık rakamlarının kaynakları (**otomatik üretilir**) |

**Bu depodaki dosyalar elle düzenlenmez.** Kaynak, uygulama projesindeki `site/` klasörü ve
`npm run publish-data` komutu; o komut sayfaları ve veriyi buraya yazar, doğrular ve push eder.

`CNAME` dosyası alan adını GitHub Pages'e bağlar; silmeyin.
