# Atölye Mola - Satış ve Stok Yönetim Sistemi

Hızlı satış, stok takibi, brüt kâr hesaplama ve Supabase bulut veritabanı senkronizasyonlu POS sistemi.

## 🚀 Özellikler

- **Hızlı Satış:** Ürün seçimi ile tek tıkla Nakit veya Kart satışı.
- **Canlı Stok Takibi:** Satış anında otomatik stok düşüşü ve azalan stok uyarıları.
- **Raporlama:** Tarih bazlı ciro, brüt kâr, nakit/kart dağılımı ve ürün bazında kârlılık tablosu.
- **Supabase Bulut Senkronizasyonu:** Çoklu cihaz desteği (telefon, tablet, bilgisayar) ve Realtime canlı güncelleme.
- **Çevrimdışı Çalışabilirlik:** İnternet kesilse bile yerel hafızada (`localStorage`) kesintisiz çalışma.
- **Veri Güvenliği & Dışa Aktarma:** Tek tıkla JSON ve CSV satış raporu indirme.

## ⚙️ Kurulum ve Çalıştırma

1. Projeyi klonlayın veya indirin.
2. `config.example.js` dosyasının adını `config.js` yapın ve kendi Supabase bilgilerinizi girin:
   ```javascript
   window.ENV = {
     SUPABASE_URL: 'https://xyzcompany.supabase.co',
     SUPABASE_KEY: 'sb_publishable_...'
   };
   ```
3. `atolye.html` dosyasını herhangi bir web tarayıcısında açın.

> Not: `config.js` dosyası `.gitignore` ile korunmaktadır ve GitHub'a yüklenmez. Bilgilerinizi dilerseniz uygulama içerisindeki **Bulut & Ayarlar** sekmesinden de girebilirsiniz.
