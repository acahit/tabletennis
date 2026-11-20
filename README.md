# PingPong Pro — Masa Tenisi Turnuva & Canlı Skor Yönetimi

Tek dosyalık (`index.html`), kurulum gerektirmeyen ve **%100 çevrimdışı çalışabilen** masa tenisi turnuva ağacı ve canlı skor tabelası uygulaması.

## Özellikler

- **Açık & Koyu Tema:** Gündüz / aydınlık salonlar için açık tema, projektör / arena için koyu tema (tek tıkla değişir, tercihi hatırlar).
- **Esnek Maç Kuralları:**
  - Set formatı: **1 Set (Bo1)**, **Bo3 (2 set)**, **Bo5 (3 set)**, **Bo7 (4 set)**
  - Set puanı: **11** (resmi ITTF), **21** (klasik) veya **5–50** arası özel puan
  - Servis değişim sıklığı: Her 1, 2, 3 veya 5 sayıda (Deuce durumunda otomatik her 1 sayıda)
  - 2 fark (Deuce) kuralı açma/kapama
  - Otomatik ITTF saha değişimi (her set sonunda ve karar setinde yarı puanda — 11'lik sette 5. sayıda, 21'lik sette 10. sayıda)
- **Çoklu Masa & Canlı Skor Tabelası:**
  - Aynı anda **8 masaya kadar** paralel canlı maç takibi
  - Dev dokunmatik sayı alanı (+1 için rakama veya butona dokunun), `-1` ile set bitişini dahi geri alma ve 200 adımlık **Geri Al** (`Ctrl+Z` / `Z`)
  - Maç kronometresi, oyuncu başına **60 sn Mola (Timeout)** sayacı ve kapatılabilir **Web Audio** ses efektleri
  - Tam ekran **Projektör Modu** (`F`)
- **Turnuva Ağacı & İçe/Dışa Aktarma:**
  - 4–64 oyuncu arası tek eleme ağacı, seribaşı sırasıyla otomatik dengeli `BAY` dağıtımı
  - Türkçe karakter destekli oyuncu arama/vurgulama
  - Challonge JSON/CSV ve uygulama JSON yedek içe/dışa aktarma
  - Tarayıcı `localStorage` ile otomatik kayıt

## Klavye Kısayolları (Canlı Skor Sekmesi)

| Tuş | İşlev |
| --- | --- |
| `Q` veya `←` | Sol oyuncu +1 |
| `A` | Sol oyuncu -1 |
| `P` veya `→` | Sağ oyuncu +1 |
| `L` | Sağ oyuncu -1 |
| `S` | Saha değiştir |
| `Z` veya `Ctrl+Z` | Son hareketi geri al |
| `F` | Projektör modu (Tam ekran) |
| `1` – `8` | Masalar arası geçiş |
| `Esc` | Modal / Tam ekran kapat |

## Hızlı Kullanım / Deploy

1. **Çevrimdışı (Anında):** `index.html` dosyasını indirip tarayıcıda açın. İnternet olmadan da çalışır.
2. **GitHub Pages:** Depo ayarlarından **Settings → Pages → Branch: `main` / `/ (root)` → Save** seçin. 1 dakika içinde canlı linkiniz hazır olur.