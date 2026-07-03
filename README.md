# Hospital Management System

React ve Vite ile geliştirilmiş, rol tabanlı erişim kontrolüne sahip hastane yönetim sistemi.

## Özellikler

Sistemde dört farklı kullanıcı rolü bulunmaktadır:

**Hasta**
- Randevu alma ve randevuları görüntüleme
- Reçete görüntüleme
- Test sonuçlarını takip etme
- Bağımlı profil yönetimi

**Doktor**
- Hasta kayıtlarını görüntüleme
- Program/takvim yönetimi
- Reçete yönetimi
- Dashboard ile genel özet

**Hemşire**
- Hasta kayıtları ve takip
- Program görüntüleme
- Bakım veren yönetimi
- Dashboard

**Ön Büro**
- Randevu yönetimi (manuel randevu dahil)
- Personel yönetimi
- Doktor program yönetimi
- Test durum takibi

## Teknolojiler

- **React 19** — UI
- **React Router v7** — Sayfa yönlendirme
- **Tailwind CSS v4** — Stil
- **Heroicons** — İkonlar
- **Vite** — Build aracı

## Kurulum

```bash
npm install
npm run dev
```

Uygulama `http://localhost:5173` adresinde çalışır.

## Diğer Komutlar

```bash
npm run build    # Production build
npm run preview  # Build sonrasını önizleme
npm run lint     # ESLint kontrolü
```

## Proje Yapısı

```
src/
├── components/     # Paylaşılan bileşenler (Navbar, Layout, AuthShell vb.)
├── context/        # AppContext — global state yönetimi
├── data/           # Mock veri (mockData.js)
├── pages/
│   ├── doktor/     # Doktor sayfaları
│   ├── hasta/      # Hasta sayfaları
│   ├── hemsire/    # Hemşire sayfaları
│   └── onBuro/     # Ön büro sayfaları
└── utils/          # Yardımcı fonksiyonlar
```
