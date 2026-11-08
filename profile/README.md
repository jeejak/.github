# Jeejak

**The back office for Indonesian marketplace sellers.** Built in Kediri, East Java, by the people who run one.

Jeejak is a family of small, focused apps that share one account and one backend. Each one does one job for a seller on Shopee, TikTok Shop or Tokopedia, works on its own, and plugs into the others. Start with the one you need.

| | What it does | Status |
|---|---|---|
| **JejakPaket** | Proof for every parcel: scan the waybill, photograph the packing, scan again at courier handover. When a buyer claims the item never arrived, export the order's evidence as one PDF. | Live on [Google Play](https://play.google.com/store/apps/details?id=id.jeejak.paket) and the [App Store](https://apps.apple.com/id/app/jejakpaket/id6820439104). Seller console at [paket.jeejak.id](https://paket.jeejak.id). |
| **Produk & Stok** | Product catalog, a stock ledger where every change is one line with who made it, and blind stock counts. | Shipped October 2026 inside JejakPaket. |
| **Pesanan, Keuangan, Laporan, Tim** | Orders, finance, reports, team. | Next. |

The free plan works on the phone without an account. Paid plans add cloud sync, multiple devices, the web console and teams.

## Open source

Two research projects from hackathons are public. Both ask one question: *will this packing photo hold up in a dispute?*

- [**proofmuse**](https://github.com/jeejak/proofmuse): the current one. Meta Muse Spark reads the photos, SAM finds the label, a Go rules engine decides and tells the seller in Indonesian what to re-shoot. Built for the Meta Global AI Developer Hackathon (Meta x Cerebral Valley, 2026). [Live demo](https://proofmuse.jeejak.id), no login.
- [**parcel-proof**](https://github.com/jeejak/parcel-proof): its predecessor on Gemini and Google Cloud, built for the AI Builder Cup 2026. [Live demo](https://jeejak-parcel-proof-run.web.app).

The product repos (the Flutter apps, the Go backend, the site, the plans) are private.

## Who makes it

A small team in Kediri, Indonesia. The first customer is our own family's online shop, which packs its parcels through JejakPaket every day.

- Website: [jeejak.id](https://jeejak.id)
- Email: [halo@jeejak.id](mailto:halo@jeejak.id)
- Pricing and plans: [jeejak.id/harga](https://jeejak.id/harga/)
