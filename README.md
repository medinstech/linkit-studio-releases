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

### Updates

A few seconds after it opens, LinKit Studio checks this repository for a newer
version. If there is one, an **Update** button appears at the top of the window,
and clicking it downloads the new installer. Nothing is installed without you.
The check downloads one small file from GitHub and sends nothing about you or
your projects. It can be turned off in *Settings › Application*.

### Signed by Medinstech

The installer and the application are signed with Medinstech's code-signing
certificate. Windows shows the publisher as *Medinstech Mühendislik ve
Teknoloji Anonim Şirketi*; if it shows anything else, do not run the file.

### What each release contains

| File | What it is |
|---|---|
| `LinKit_Studio_Setup_<version>.exe` | The installer |
| `LICENSE.txt` | The licence agreement for that version (also shown by the installer) |
| `THIRD-PARTY-LICENSES.md` | The open-source components inside the application and their licences |
| `build-manifest.txt` | The exact library versions that build was made from |
| `latest.json` | What the application reads to learn that a newer version exists |

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

### Güncellemeler

LinKit Studio açıldıktan birkaç saniye sonra bu depoda daha yeni bir sürüm olup
olmadığına bakar. Varsa pencerenin üstünde bir **Güncelleme** düğmesi çıkar;
tıklayınca yeni kurulum dosyası iner. Sizden habersiz hiçbir şey kurulmaz.
Kontrol, GitHub'dan küçük bir dosya indirir; sizin veya projeleriniz hakkında
hiçbir bilgi göndermez. *Ayarlar › Uygulama*'dan kapatılabilir.

### Medinstech imzalı

Kurulum dosyası ve uygulama, Medinstech'in kod imzalama sertifikasıyla
imzalıdır. Windows yayıncıyı *Medinstech Mühendislik ve Teknoloji Anonim
Şirketi* olarak gösterir; başka bir şey gösteriyorsa dosyayı çalıştırmayın.

### Her sürümde neler var

| Dosya | Ne olduğu |
|---|---|
| `LinKit_Studio_Setup_<sürüm>.exe` | Kurulum dosyası |
| `LICENSE.txt` | O sürümün lisans sözleşmesi (kurulumda da gösterilir) |
| `THIRD-PARTY-LICENSES.md` | Uygulamanın içindeki açık kaynak bileşenler ve lisansları |
| `build-manifest.txt` | O derlemenin yapıldığı kütüphane sürümlerinin tam listesi |
| `latest.json` | Uygulamanın yeni sürüm olduğunu öğrenmek için okuduğu dosya |

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
