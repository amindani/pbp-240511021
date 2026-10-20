# Analisis Komparatif Komputasi Platform

| Aspek Komparasi | Platform Web | Platform Desktop | Platform Mobile |
| :--- | :--- | :--- | :--- |
| **Bahasa Pemrograman Utama** | JavaScript (Node.js/Frontend), TypeScript, WebAssembly (C++/Rust) | C#, C++, Java, Rust, Swift (macOS/Cocoa), Python | Kotlin (Android Native), Swift (iOS Native), Dart, JavaScript/JSX |
| **Pola Arsitektur Perangkat Lunak** | Client-Server, Single Page Application (SPA), Micro-frontends, PWA | Monolitik Lokal, Native GUI Architecture, Client-Server (Heavy/Thick Client) | Model-View-ViewModel (MVVM), Clean Architecture, REST/GraphQL Client |
| **Mekanisme Distribusi & Pengoperasian** | Penyediaan via Server Web / Content Delivery Network (CDN) melalui peramban (browser) | Berkas biner (*installer*) mandiri (`.exe`, `.dmg`, `.AppImage`) atau toko aplikasi OS | Distribusi resmi via platform store (Google Play Store & Apple App Store) |
| **Keunggulan Utama** | Bebas akses tanpa proses instalasi lokal, pembaruan versi terpusat secara *real-time*, hemat ruang penyimpanan lokal | Akses komputasi mendalam ke hardware (CPU/GPU), operasi cepat tanpa dependensi jaringan, kontrol memori tinggi | Sangat portabel, pemanfaatan penuh sensor fisik (GPS, Gyroscope, NFC), serta sistem notifikasi bawaan |
| **Keterbatasan Utama** | Terisolasi dalam *sandbox* browser, kinerja terbatas pada pemrosesan grafis berat, dependensi penuh pada stabilitas koneksi | Kurang fleksibel antar-OS (perlu kompilasi ulang), instalasi dan pembaruan patch memerlukan tindakan pengguna | Keterbatasan daya baterai dan memori RAM, batasan kebijakan ketat dari pengelola toko aplikasi |
| **Contoh Implementasi Real** | Notion Web, Canva, Google Maps Web | Blender, Slack Desktop, Microsoft Excel Desktop | Tokopedia, Spotify Mobile, Grab |

---

## Sumber Referensi & Literatur

1. **W3C (World Wide Web Consortium).** *Web Architecture and Standards.*  
   URL: https://www.w3.org/TR/webarch/
2. **Apple Developer Documentation.** *Human Interface Guidelines & iOS Architecture.*  
   URL: https://developer.apple.com/documentation/
3. **Google Developers.** *Progressive Web Apps & Web Platform Capability.*  
   URL: https://web.dev/explore/progressive-web-apps
