# Trendyol Marketplace API - Full Postman Collection

Trendyol Marketplace API'nin **tam ve güncel** Postman koleksiyonu.  
Tüm endpoint'ler resmi [developers.trendyol.com/reference](https://developers.trendyol.com/reference/) sayfasından derlenmiş, her istek ve klasöre **Türkçe açıklama** eklenmiştir.

## Özellikler

- Tüm ana modüller: Sipariş & Kargo, İade, Ürün V2, Finans, Webhook, Fatura, Müşteri Soruları, Adres, Tazmin vb.
- Her endpoint için Türkçe açıklama
- Klasör (parent) seviyesinde açıklamalar
- Collection değişkenleri hazır (`sellerId`, `api_key`, `api_secret` vb.)
- Basic Auth yapılandırması hazır

## Kurulum

1. Postman'i aç → **Import** → JSON dosyasını seç
2. Collection Variables kısmından şu alanları doldur:
   - `sellerId` → Satıcı ID'niz
   - `api_key` → API Key
   - `api_secret` → API Secret
3. İstekleri çalıştırabilirsiniz.

## Önemli Notlar

- **Ürün V1** servisleri **15 Ekim 2026** itibarıyla kapatılacaktır. Yeni geliştirmelerde **Ürün V2** kullanın.
- AutoFT (İhracat Merkezi) endpoint'leri şu an `stageapigw.trendyol.com` üzerindedir. Production kullanılabilirliğini resmi dokümantasyondan doğrulayın.

## Kaynak

- [Trendyol Developers - API Reference](https://developers.trendyol.com/reference/)

## Lisans

MIT
