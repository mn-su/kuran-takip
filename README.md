# Kur'an-ı Kerim Takip

🔗 **[https://mn-su.github.io/kuran-takip/](https://mn-su.github.io/kuran-takip/)**

Kur'an-ı Kerim hatim takibini sade ve çevrimdışı destekli şekilde yapmanızı sağlayan Progressive Web App (PWA).

## Özellikler

- 📖 Mushaf sayfa düzeninde Arapça metin okuma
- 🇹🇷 Türkçe meal (Diyanet İşleri)
- 📊 Hatim ilerleme takibi
- 📴 Çevrimdışı çalışma (PWA + Service Worker)
- 📱 Mobil uyumlu, ana ekrana eklenebilir

## Veri Kaynakları

| Veri | Birincil Kaynak | Fallback |
|---|---|---|
| Arapça metin | [Tanzil](https://tanzil.net) (yerel) | — |
| Türkçe meal | [quran-json](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/) (CDN) | Tanzil tr.diyanet.xml (yerel) |
| Sure bilgileri | quran-json CDN | Tanzil quran-data.js (yerel) |

CDN erişilemez olduğunda uygulama yerel dosyalardan çalışmaya devam eder.

## Lisanslar

- **Tanzil Kur'an Metni:** [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/)
- **quran-json:** [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)
