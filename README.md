# LinKit Studio

🌎 [English](#english) | 🇹🇷 [Türkçe](#türkçe)

---

<a id="english"></a>
## 🌎 English

**LinKit Studio** is a free Windows application from Medinstech: a sandbox for
building mechanisms from LinKit modules on a grid baseplate, and the control
application for the machines you build with it.

This repository hosts the **installers only**. The application is free to
download and use; its source code is not published.

### Download

**[Latest version →](https://github.com/medinstech/linkit-studio-releases/releases/latest)**

Download `LinKit_Studio_Setup_<version>.exe` from the release and run it.
Product page: [medinstech.com/linkit](https://www.medinstech.com/linkit/)

### Installing

- Windows, 64-bit.
- Installs for your user account only, so it needs no administrator rights.
  It goes to `%LOCALAPPDATA%\Programs\Medinstech\LinKit Studio`.
- To remove it, use Windows *Settings → Apps*. Your own parts library, in
  `%LOCALAPPDATA%\Medinstech\LinkitSandbox`, is left in place.

### What each release contains

| File | What it is |
|---|---|
| `LinKit_Studio_Setup_<version>.exe` | The installer |
| `LICENSE.txt` | The licence agreement for that version (also shown by the installer) |
| `THIRD-PARTY-LICENSES.md` | The open-source components inside the application and their licences |
| `build-manifest.txt` | The exact library versions that build was made from |

### Licence

Free to use, including commercially, on any number of your own devices. The
source code is not published. The full terms are in `LICENSE.txt` in each
release.

The application contains third-party components under their own licences —
among them Qt, via PySide6, under the LGPL v3. `THIRD-PARTY-LICENSES.md`
explains what that entitles you to and how to obtain those sources.

### Safety

LinKit Studio commands physical machinery that can move without warning. You are
responsible for operating your hardware safely. Never rely on the software alone
as a safety measure.

---

<a id="türkçe"></a>
## 🇹🇷 Türkçe

**LinKit Studio**, Medinstech'in ücretsiz Windows uygulamasıdır: LinKit
modülleriyle bir ızgara taban plakası üzerinde mekanizma kurmak için bir
sandbox ve kurduğunuz makineleri kontrol eden uygulama.

Bu depoda **yalnızca kurulum dosyaları** bulunur. Uygulamayı indirmek ve
kullanmak ücretsizdir; kaynak kodu yayınlanmamaktadır.

### İndirme

**[En son sürüm →](https://github.com/medinstech/linkit-studio-releases/releases/latest)**

Sürümün içinden `LinKit_Studio_Setup_<sürüm>.exe` dosyasını indirip çalıştırın.
Ürün sayfası: [medinstech.com/linkit](https://www.medinstech.com/linkit/)

### Kurulum

- Windows, 64-bit.
- Yalnızca sizin kullanıcı hesabınıza kurulur, yönetici yetkisi gerekmez.
  Kurulum yeri: `%LOCALAPPDATA%\Programs\Medinstech\LinKit Studio`.
- Kaldırmak için Windows *Ayarlar → Uygulamalar*'ı kullanın.
  `%LOCALAPPDATA%\Medinstech\LinkitSandbox` altındaki kendi parça
  kütüphaneniz silinmez.

### Her sürümde neler var

| Dosya | Ne olduğu |
|---|---|
| `LinKit_Studio_Setup_<sürüm>.exe` | Kurulum dosyası |
| `LICENSE.txt` | O sürümün lisans sözleşmesi (kurulumda da gösterilir) |
| `THIRD-PARTY-LICENSES.md` | Uygulamanın içindeki açık kaynak bileşenler ve lisansları |
| `build-manifest.txt` | O derlemenin yapıldığı kütüphane sürümlerinin tam listesi |

### Lisans

Ticari kullanım dahil, kendi cihazlarınızın tamamında ücretsiz kullanılabilir.
Kaynak kodu yayınlanmamaktadır. Tam koşullar her sürümdeki `LICENSE.txt`
dosyasındadır.

Uygulama kendi lisanslarına tabi üçüncü taraf bileşenler içerir; bunların
arasında PySide6 üzerinden LGPL v3 lisanslı Qt de var.
`THIRD-PARTY-LICENSES.md` bunun size hangi hakları verdiğini ve kaynak
kodlarına nasıl ulaşacağınızı anlatır.

### Güvenlik

LinKit Studio, uyarı vermeden hareket edebilen fiziksel makineleri kontrol eder.
Donanımınızın güvenli kullanımından siz sorumlusunuz. Güvenlik için hiçbir
zaman yalnızca yazılıma güvenmeyin.
