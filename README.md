# 🎬 Bugün Ne İzlesem? - Ruh Hali Tabanlı Film Öneri Asistanı

Kullanıcının o anki ruh haline (*Kafa Dağıtmalık, Beyin Yakan, Adrenalin, Duygusal, Gerilim, Nostaljik*) ve zaman kısıtına göre film önerileri sunan, fragman oynatabilen ve kişisel izleme listesi oluşturabilen dinamik web uygulaması.

## 🚀 Kullanılan Teknolojiler ve API'ler
- **HTML5 & Tailwind CSS:** Modern, karanlık tema (dark mode) ve mobil uyumlu (responsive) arayüz tasarımı.
- **Vanilla JavaScript (ES6+):** `async/await` ve `fetch()` ile asenkron API iletişimi ve DOM manipülasyonu.
- **TMDB (The Movie Database) REST API:** Tür, puan, yıl ve süre parametrelerine göre dinamik film keşfi (`/discover/movie`) ve video verileri (`/movie/{id}/videos`).
- **YouTube Embed API:** Seçilen filmlerin fragmanlarının uygulama içinde doğrudan oynatılması.
- **Web Storage API (`localStorage`):** Kullanıcının izleme listesinin ve API anahtarının tarayıcıda kalıcı olarak saklanması.

## 🛠️ Kurulum ve Çalıştırma
1. `index.html` dosyasını herhangi bir modern web tarayıcısında açın (veya VS Code Live Server ile çalıştırın).
2. Uygulama varsayılan olarak **Demo Modu**nda zengin bir yerel film veri tabanıyla anında çalışır.
3. Sağ üstteki **Demo Modu** butonuna tıklayıp kendi ücretsiz [TMDB API (v3)](https://www.themoviedb.org/settings/api) anahtarınızı girerek gerçek zamanlı REST API modunu aktif edebilirsiniz.
