# HavenMC Launcher

HavenMC için Windows launcher arayüzü. Sunucu: `havenmc.mangoohost.live`.

## GitHub'da EXE üretme
1. Bu klasörü GitHub repository'ne yükle.
2. `.github/workflows/build-windows.yml` workflow'u çalıştır.
3. Actions > build-windows > Artifacts bölümünden `HavenMC-Launcher-Windows` dosyasını indir.
4. İçindeki `HavenMC Launcher_1.0.0_x64-setup.exe` kurulum dosyasıdır.

## Windows 7–11
Tauri'nin NSIS kurulumu için WebView2 bootstrapper gömülü ayarlandı. Windows 7'de WebView2'nin kurulabilmesi için internet/TLS 1.2 gerekebilir. Windows 10/11'de WebView2 genellikle sistemle birlikte gelir.

## Önemli
Bu paket **launcher arayüzü/prototipidir**. Gerçek Microsoft hesap girişi, Mojang asset/library indirme, Java runtime yönetimi ve Fabric/Forge/NeoForge kurulum motoru henüz bağlı değildir. Modrinth/CurseForge API alanları arayüzde hazırdır.
