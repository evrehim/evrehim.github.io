# evrehim.github.io

Newbar'ın geliştirici sitesi.

| Yol | Dosya | Ne işe yarar |
|---|---|---|
| `/inkpage/` | `inkpage/index.html` | Inkpage indirme sayfası — Instagram bio'sundaki bağlantı |
| `/` | `index.html` | `/inkpage/`'e yönlendirme (eski kısa bağlantı kırılmasın) |
| `/app-ads.txt` | `app-ads.txt` | AdMob yayıncı doğrulaması |
| `/favicon.png` | `favicon.png` | Sekme/ana ekran ikonu |
| — | `.nojekyll` | Pages'in Jekyll derlemesini kapatır |

## Dikkat

**`app-ads.txt` kökte kalmalı.** Spec gereği geliştirici alan adının
kökünde aranıyor; alt klasöre taşınırsa AdMob doğrulaması bozulur.

**Kaynak kopya:** `inkpage/index.html`'in aslı `inkfall_flutter` deposunda
`docs/index.html`. Değişiklik orada yapılır, buraya kopyalanır.

## Sayfa neden var

Instagram'ın kendi tarayıcısı Play Store bağlantılarını bazı Android
telefonlarda açamıyor — tıklayınca hiçbir şey olmuyor. Araya normal bir
sayfa girince oradaki bağlantı kullanıcı hareketiyle açıldığı için Play
Store düzgün çalışıyor. Yine de açılmazsa sayfa 1,4 saniye sonra
"Didn't open?" panelini gösteriyor: kopyalanabilir bağlantı + "Play
Store'da Inkpage ara".
