# Pengarang Diri — Program Pembangunan Diri Malaysia

> Jelajah Masa Lalu. Kenali Masa Kini. Reka Masa Depan.

Website rasmi: [pengarangdiri.com.my](https://pengarangdiri.com.my)  
OnPay: [https://molife.onpay.my/order/form/8](https://molife.onpay.my/order/form/8)

---

## Struktur Fail

```
pengarang-diri/
│
├── index.html                  ← Landing page (halaman utama)
├── pengarang-diri.html         ← Workbook interaktif (produk)
├── pengarang-diri.pdf          ← Ebook PDF (produk)
│
├── assets/
│   ├── logo-square-tagline.png ← Logo utama (OnPay, Shopee)
│   ├── logo-square-tagline.jpg
│   ├── logo-square-dark.png
│   ├── logo-square-dark.jpg
│   ├── logo-square-cerah.png
│   ├── logo-square-cerah.jpg
│   ├── logo-banner-F.png       ← Banner header (1200x400)
│   ├── logo-banner-F.jpg
│   ├── logo-banner-B.png
│   ├── logo-banner-B.jpg
│   ├── logo-B-cerah.svg
│   ├── logo-F-banner.svg
│   └── logo-square-tagline.svg
│
├── admin/                      ← JANGAN upload ke GitHub (private)
│   ├── generate_customer.py    ← Script jana fail pelanggan
│   ├── email-template.html     ← Template email pelanggan
│   └── pelanggan-log.csv       ← Log semua pelanggan & password
│
└── README.md
```

---

## GitHub Pages

Website live di:
```
https://[username].github.io/pengarang-diri/
```

---

## Cara Jana Fail Pelanggan Baru

```bash
python3 admin/generate_customer.py
```

Pilih mod 1 (satu pelanggan) atau mod 2 (batch CSV).

---

## Nota Penting

- Folder `admin/` mengandungi maklumat sensitif — **jangan jadikan public**
- `pelanggan-log.csv` mengandungi password pelanggan — simpan dengan selamat
- Workbook interaktif (`pengarang-diri.html`) perlukan API key Anthropic untuk fungsi AI Refleksi
