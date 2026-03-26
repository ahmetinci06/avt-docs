# 📄 AVT Racing — Dökümanlar & Sponsorluk

## 📊 İlerleme & Çalışma Akışı

- [🔄 WORKFLOW.md](WORKFLOW.md) — Çalışma akışı ve PR kuralları
- [📊 PROGRESS.md](PROGRESS.md) — Görev durumları ve ilerleme
- [🐛 BUGS.md](BUGS.md) — Bug raporları ve debug takibi

> Her değişiklik PR ile yapılır. Review: @ahmetinci06 & Yaver (AI CTO)

---



> **avt-docs** — Sponsorluk materyalleri, sosyal medya içerikleri, TEKNOFEST dökümanları ve genel ekip raporlarının deposu.

[![Ana Hub](https://img.shields.io/badge/Ana%20Hub-avt--hub--dev-blue)](https://github.com/ahmetinci06/avt-hub-dev)
[![TEKNOFEST 2026](https://img.shields.io/badge/TEKNOFEST-2026-red)](https://teknofest.org)

---

## 📋 Hakkında

Bu repo, AVT Racing takımının tüm yazışmalar, sponsorluk materyalleri, tanıtım içerikleri, TEKNOFEST başvuru dökümanları ve ekip raporlarını barındırır.

**Merkezi Hub:** [avt-hub-dev](https://github.com/ahmetinci06/avt-hub-dev)

---

## 👥 Sponsorluk & Sosyal Medya Ekibi

| İsim | Rol |
|------|-----|
| Ceren Atasoy | Sponsorluk & Sosyal Medya |
| Sezin Gülbahçe | Sponsorluk & Sosyal Medya |
| Yaprak İleez | Sponsorluk & Sosyal Medya |
| Gülce Yılmaz | Sponsorluk & Sosyal Medya |

---

## 📁 Klasör Yapısı

```
avt-docs/
├── sponsorship/                # Sponsorluk materyalleri
│   ├── sponsorship-kit/        # Sponsorluk paketi
│   ├── presentations/          # Sponsor sunumları
│   ├── contracts/              # Sözleşme şablonları
│   └── correspondence/         # Yazışmalar (anonim)
├── social-media/               # Sosyal medya içerikleri
│   ├── templates/              # Görsel şablonlar
│   ├── content-calendar/       # İçerik takvimi
│   └── assets/                 # Logolar, görseller
├── teknofest/                  # TEKNOFEST başvuru dökümanları
│   ├── 2026/
│   │   ├── application/        # Başvuru formu
│   │   ├── technical-report/   # Teknik rapor
│   │   └── presentation/       # Sunum
│   └── rules/                  # Yarışma kuralları
├── team/                       # Ekip dökümanları
│   ├── meeting-notes/          # Toplantı notları
│   ├── reports/                # Haftalık/aylık raporlar
│   └── photos/                 # Ekip fotoğrafları
├── branding/                   # Marka kimliği
│   ├── logo/                   # Logo dosyaları (SVG, PNG)
│   ├── colors.md               # Renk paleti
│   └── fonts/                  # Yazı tipleri
├── templates/                  # Döküman şablonları
└── docs/
    ├── GITHUB-GUIDE.md
    └── content-guidelines.md   # İçerik yönergeleri
```

---

## 📱 Sosyal Medya Kanalları

| Platform | Kullanım |
|----------|----------|
| Instagram | Araç geliştirme süreci, ekip haberleri |
| LinkedIn | Sponsorluk, kurumsal iletişim |
| Twitter/X | Günlük güncellemeler, yarışma haberleri |
| YouTube | Test videoları, tanıtım filmleri |

---

## 🤝 Sponsorluk Süreci

```
1. Potansiyel sponsor listesi oluştur
   └── sponsorship/sponsorship-kit/ klasörüne ekle

2. Sponsorluk kiti hazırla
   └── Şablonlar: sponsorship/sponsorship-kit/template.pptx

3. İlk iletişim
   └── Yazışmaları: sponsorship/correspondence/ klasörüne ekle

4. Sunum yap
   └── Sunumlar: sponsorship/presentations/ klasörüne ekle

5. Sözleşme
   └── Şablon: sponsorship/contracts/ klasöründe
```

---

## 📅 İçerik Takvimi

İçerik takvimi `social-media/content-calendar/` klasöründe Excel veya Google Sheets olarak tutulur.

**Önerilen yayın sıklığı:**
- Instagram: Haftada 3-4 gönderi
- LinkedIn: Haftada 1-2 gönderi
- Twitter: Günde 1-2 tweet

---

## 🌿 Branch Yapısı

```
main          ← Onaylanmış, final dökümanlar
  └── develop ← Aktif çalışmalar
        ├── docs/sponsor-paketi-v2
        ├── docs/teknofest-basvuru
        └── content/haftalik-icerik
```

### Branch İsimlendirme
```
docs/<konu>         # Döküman ekle/güncelle
content/<tarih>     # Sosyal medya içeriği
design/<materyal>   # Tasarım materyali
```

---

## ⚠️ Gizlilik Kuralları

- Sponsor sözleşmeleri ve gizli yazışmaları commit etme — sadece şablonları ekle
- Kişisel iletişim bilgilerini dosyalara ekleme
- TEKNOFEST başvuru dökümanları final hale gelmeden `develop`'ta tut

---

## 🚀 Hızlı Başlangıç

```bash
git clone git@github.com:ahmetinci06/avt-docs.git
cd avt-docs
git checkout develop
git checkout -b docs/eklediğin-döküman
```

Detaylı rehber: [docs/GITHUB-GUIDE.md](docs/GITHUB-GUIDE.md)

---

## 📚 Kaynaklar

- [CONTRIBUTING.md](CONTRIBUTING.md)
- [docs/GITHUB-GUIDE.md](docs/GITHUB-GUIDE.md)
- [Ana Hub — avt-hub-dev](https://github.com/ahmetinci06/avt-hub-dev)

---

*🏎️ AVT Racing — TEKNOFEST 2026 | Sponsorluk & Sosyal Medya Ekibi*