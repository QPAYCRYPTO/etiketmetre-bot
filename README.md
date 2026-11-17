# EtiketmetreBot

EtiketmetreBot, herkese açık e-ticaret ürün sayfalarındaki yapılandırılmış fiyat ve stok bilgisini
(JSON-LD / Schema.org) okuyan bir fiyat karşılaştırma robotudur.

- **robots.txt:** Kurallarınıza uyar; izin verilmeyen hiçbir adrese istek atmaz.
- **Yük:** Günde en fazla 2 tur, istekler arasında en az 10 saniye bekler.
- **Koruma atlatmaz:** Proxy, tarayıcı taklidi veya CAPTCHA aşma kullanmaz.
- **İletişim:** Bu sayfadaki "Issues" bölümünden yazabilirsiniz.

## Engelleme

robots.txt dosyanıza şunu eklemeniz yeterli. Bot bunu gördüğünde sitenizi otomatik olarak listeden çıkarır:

```
User-agent: EtiketmetreBot
Disallow: /
```
