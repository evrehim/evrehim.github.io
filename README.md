# evrehim.github.io

Inkpage'in tanıtım/indirme sayfası.

| Dosya | Adres | Ne işe yarar |
|---|---|---|
| `index.html` | https://evrehim.github.io/ | Instagram bio'sundaki indirme sayfası |
| `app-ads.txt` | https://evrehim.github.io/app-ads.txt | AdMob yayıncı doğrulaması |

`index.html`'in kaynağı `inkfall_flutter` deposundaki `docs/index.html`;
değişiklik orada yapılır, buraya kopyalanır.

Sayfanın varlık sebebi: Instagram'ın kendi tarayıcısı Play Store
bağlantılarını bazı Android telefonlarda açamıyor, tıklayınca hiçbir şey
olmuyor. Araya normal bir sayfa girince oradaki bağlantı kullanıcı
hareketiyle açıldığı için Play Store düzgün çalışıyor. Yine de açılmazsa
sayfa 1,4 saniye sonra "Didn't open?" panelini gösteriyor.
