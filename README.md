# ICT Bozor Tahlilchisi — XAU/USD

ICT (Inner Circle Trader) metodologiyasi asosida narx ma'lumotini (OHLC) tahlil qiladigan, market structure (BOS/CHoCH), order block, fair value gap va liquidity zonalarni aniqlab, Entry/Stop Loss/Take Profit taklif qiladigan veb-vosita.

**Bu ta'lim va tahliliy vosita, moliyaviy maslahat emas.**

## Ishlatish

Sayt to'liq statik (server kerak emas) — `index.html` faylini istalgan brauzerda ochish kifoya, yoki quyidagi "Joylashtirish" bo'limidagi manzil orqali onlayn oching.

1. **Demo ma'lumot** bilan mexanizmni sinab ko'ring, yoki
2. **CSV yuklab** (TradingView, MT5 History Center, yoki Dukascopy Historical Data Export'dan olingan) haqiqiy tahlil qiling.

## Joylashtirish (GitHub Pages)

Ushbu repo GitHub Pages orqali joylashtirilgan bo'lsa, sayt quyidagi manzilda ishlaydi:

```
https://<GITHUB-USERNAME>.github.io/<REPO-NOMI>/
```

## Yangilash

`index.html` faylini tahrirlab, o'zgarishlarni push qiling — GitHub Pages avtomatik ravishda 1-2 daqiqada yangilaydi.

## Texnik tuzilma

- Bitta mustaqil `index.html` fayl (HTML + CSS + vanilla JavaScript)
- Grafik uchun [lightweight-charts](https://github.com/tradingview/lightweight-charts) (CDN orqali)
- Tashqi backend yo'q — barcha tahlil brauzerning o'zida (client-side) bajariladi
- Ma'lumot faqat foydalanuvchi tomonidan CSV/qo'lda kiritiladi (jonli API ulanishi yo'q)
