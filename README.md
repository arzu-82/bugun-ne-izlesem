# 🎬 Bugün Ne İzlesem? - Ruh Hali Tabanlı Film Öneri Asistanı

Kullanıcının o anki ruh haline (*Kafa Dağıtmalık, Beyin Yakan, Adrenalin, Duygusal, Gerilim, Nostaljik*) ve zaman kısıtına göre **TMDB REST API** üzerinden gerçek zamanlı film önerileri sunan, YouTube fragmanlarını oynatabilen ve kişisel izleme listesi oluşturabilen dinamik web uygulaması.

## 🚀 Kullanılan Teknolojiler ve API'ler
- **HTML5 & Tailwind CSS:** Modern, karanlık tema (dark mode) ve mobil uyumlu (responsive) arayüz tasarımı.
- **Vanilla JavaScript (ES6+):** `async/await` ve `fetch()` ile asenkron REST API iletişimi ve dinamik DOM manipülasyonu.
- **TMDB (The Movie Database) REST API:** Tür, puan, yıl ve süre parametrelerine göre canlı film keşfi (`/discover/movie`) ve çok dilli fragman verileri (`/movie/{id}/videos`).
- **YouTube Embed API:** Seçilen filmlerin fragmanlarının uygulama içinde doğrudan oynatılması.
- **Web Storage API (`localStorage`):** Kullanıcının izleme listesinin tarayıcıda kalıcı olarak saklanması.

## 🌐 Canlı Demo
Proje GitHub Pages üzerinde yayınlanmaktadır: `https://arzu-02.github.io/bugun-ne-izlesem/`
