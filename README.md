# Lert Noi Jaew – Online Menu Web App

**Live site:** https://lert-noi-jaew.web.app

Website for my family's Isaan food shop at Phon Municipal Fresh Market (Building 5), Phon District, Khon Kaen, Thailand.

## Versions
| File | Description |
|---|---|
| `public/index.html` | **Live version** – menu showcase with photos and prices, Facebook contact, shop video and gallery |
| `backup/index_order_version.html` | **Ordering version** (earlier prototype) – full online ordering flow |

## Features (ordering version)
- Shopping cart and checkout flow in vanilla JavaScript (add/remove items, quantity, order summary)
- LINE LIFF integration: customer login, profile retrieval, sending order summaries to LINE chat
- PromptPay QR payment generation – EMVCo TLV payload and CRC16 checksum implemented from scratch
- Bank transfer option with copy-to-clipboard

## Tech Stack
HTML, CSS, JavaScript (no framework), LINE LIFF SDK, Firebase Hosting

## Deploy
```bash
firebase deploy --project lert-noi-jaew
```
