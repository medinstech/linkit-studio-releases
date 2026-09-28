<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/assets/logo-dark.png">
    <img src=".github/assets/logo-light.png" alt="LinKit" width="150">
  </picture>
</p>

<h1 align="center">LinKit Studio</h1>

<p align="center">
  <b>Build a mechanism from LinKit parts on screen, then drive the machine you built.</b><br>
  <sub>LinKit parçalarıyla mekanizmanızı ekranda kurun, sonra kurduğunuz makineyi sürün.</sub>
</p>

<p align="center">
  <a href="https://github.com/medinstech/linkit-studio-releases/releases/latest"><img alt="Latest version" src="https://img.shields.io/github/v/release/medinstech/linkit-studio-releases?label=latest&color=ff7f00"></a>
  <img alt="Windows 10 / 11, 64-bit" src="https://img.shields.io/badge/Windows-10%20%7C%2011%20%C2%B7%2064--bit-0078D6">
  <img alt="Free" src="https://img.shields.io/badge/price-free-2ea44f">
  <img alt="English and Turkish" src="https://img.shields.io/badge/language-EN%20%7C%20TR-555">
</p>

<p align="center">
  <a href="https://github.com/medinstech/linkit-studio-releases/releases/latest"><b>⬇&nbsp;&nbsp;Download for Windows</b></a>
  &nbsp;·&nbsp; <a href="#english">English</a>
  &nbsp;·&nbsp; <a href="#türkçe">Türkçe</a>
  &nbsp;·&nbsp; <a href="https://www.medinstech.com/linkit/">medinstech.com/linkit</a>
</p>

<p align="center">
  <img src=".github/assets/start.png" alt="LinKit Studio's start page, with the LinKit 5-Bar Set" width="100%">
</p>

<table>
  <tr>
    <td width="33%"><img src=".github/assets/mechanism.png" alt="Building a five-bar on the grid baseplate"></td>
    <td width="33%"><img src=".github/assets/drive.png" alt="Driving the five-bar: a slider per motor and an X/Y target"></td>
    <td width="33%"><img src=".github/assets/parts.png" alt="The Parts page: a joint's size, range and connection faces"></td>
  </tr>
  <tr>
    <td align="center"><sub><b>Build</b> · Kur</sub></td>
    <td align="center"><sub><b>Drive</b> · Sür</sub></td>
    <td align="center"><sub><b>Parts</b> · Parçalar</sub></td>
  </tr>
</table>

---

<a id="english"></a>
## 🌎 English

**LinKit Studio** is a free Windows application from Medinstech: a sandbox for
building mechanisms from LinKit modules on a grid baseplate, and the control
application for the machines you build with it.

### What you can do with it

- **Build in 3D.** Drag LinKit parts onto the grid baseplate. The application
  recognises what you have assembled, and keeps a build list of the parts
  and bolts it takes.
- **Start from a set.** Open the LinKit 5-Bar Set in one click, or an example,
  and change it from there.
- **Drive it.** A slider for each motor, an X/Y target, and the area the
  mechanism can reach. On a five-bar: freehand sketching, a picture turned
  into a toolpath, G-code, and pick & place.
- **Read every part.** Its size, the range of its joint, and every face
  another part can connect to.
- **In English or Turkish,** one click apart.

No hardware is needed to build and try a mechanism on screen. Driving a real
machine needs one connected over USB or Wi-Fi.

### Download and install

1. Open the **[latest version](https://github.com/medinstech/linkit-studio-releases/releases/latest)**
   and download `LinKit_Studio_Setup_<version>.exe`.
2. Run it, and choose English or Turkish. It installs for your user account
   only, so it needs no administrator rights.
3. If Windows SmartScreen stops it, see [Signed by Medinstech](#signed-by-medinstech).

**Requirements:** Windows 10 or 11, 64-bit; about 650 MB of disk space; a
graphics driver with OpenGL 3.2 or later, which any recent computer has.

It installs to `%LOCALAPPDATA%\Programs\Medinstech\LinKit Studio`. To remove
it, use Windows *Settings → Apps*. Your own parts library, in
`%LOCALAPPDATA%\Medinstech\LinkitSandbox`, is left in place.

### Updates

A few seconds after it opens, LinKit Studio checks this repository for a newer
version. If there is one, it tells you once, and an **Update** button stays at
the top of the window; either downloads the new installer. Nothing is installed
without you. The check downloads one small file from GitHub and sends nothing
about you or your projects. It can be turned off in *Settings › Application*.

### Signed by Medinstech

The installer and the application are signed with Medinstech's code-signing
certificate. Windows shows the publisher as *Medinstech Mühendislik ve
Teknoloji Anonim Şirketi*; if it shows anything else, do not run the file.

A new release can still meet a Windows SmartScreen warning until enough people
have run it. Choose *More info*, check that the publisher is the one above, and
then *Run anyway*.

### What each release contains

| File | What it is |
|---|---|
| `LinKit_Studio_Setup_<version>.exe` | The installer |
| `LICENSE.txt`, `LICENSE.tr.txt` | The licence agreement for that version, in English and Turkish (the installer shows it in the language you choose) |
| `THIRD-PARTY-LICENSES.md` | The open-source components inside the application, and what their licences entitle you to |
| `THIRD-PARTY-NOTICES.txt` | The full licence text of every open-source component inside the application |
| `build-manifest.txt` | The exact library versions that build was made from |
| `latest.json` | What the application reads to learn that a newer version exists |

### Reporting a problem

Use **Report a problem** in the application (on the start page, or in
*Settings › Application*): it opens a form here with the version and your
Windows already filled in. You can also
[open one directly](https://github.com/medinstech/linkit-studio-releases/issues/new/choose).
Reports need a GitHub account.

### Licence

Free to use, including commercially, on any number of your own devices. The
full terms are in `LICENSE.txt` in each release, and in Turkish in
`LICENSE.tr.txt`.

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

### Neler yapabilirsiniz

- **3B olarak kurun.** LinKit parçalarını ızgara taban plakasına sürükleyin.
  Uygulama neyi kurduğunuzu tanır; gereken parçaların ve cıvataların listesini
  de çıkarır.
- **Bir setten başlayın.** LinKit 5-Bar Seti'ni ya da bir örneği tek tıkla
  açın, oradan değiştirin.
- **Sürün.** Her motor için bir kaydırıcı, bir X/Y hedefi ve mekanizmanın
  erişebildiği alan. 5-Bar'da serbest çizim, görselden takım yolu, G-code ve
  al-bırak.
- **Her parçayı inceleyin.** Ölçüleri, ekleminin aralığı ve başka bir parçanın
  bağlanabileceği her yüzü.
- **Türkçe ya da İngilizce,** aralarında tek tık.

Bir mekanizmayı ekranda kurup denemek için donanım gerekmez. Gerçek bir makineyi
sürmek için USB ya da Wi-Fi ile bağlı bir makine gerekir.

### İndirme ve kurulum

1. **[En son sürümü](https://github.com/medinstech/linkit-studio-releases/releases/latest)**
   açın ve `LinKit_Studio_Setup_<sürüm>.exe` dosyasını indirin.
2. Çalıştırın, Türkçe ya da İngilizce'yi seçin. Yalnızca sizin kullanıcı
   hesabınıza kurulur, yönetici yetkisi gerekmez.
3. Windows SmartScreen durdurursa [Medinstech imzalı](#medinstech-imzalı)
   bölümüne bakın.

**Gereksinimler:** Windows 10 ya da 11, 64-bit; yaklaşık 650 MB disk alanı;
OpenGL 3.2 veya üstünü destekleyen bir ekran kartı sürücüsü (yeni her
bilgisayarda vardır).

Kurulum yeri: `%LOCALAPPDATA%\Programs\Medinstech\LinKit Studio`. Kaldırmak için
Windows *Ayarlar → Uygulamalar*'ı kullanın.
`%LOCALAPPDATA%\Medinstech\LinkitSandbox` altındaki kendi parça kütüphaneniz
silinmez.

### Güncellemeler

LinKit Studio açıldıktan birkaç saniye sonra bu depoda daha yeni bir sürüm olup
olmadığına bakar. Varsa bunu bir kez haber verir ve pencerenin üstünde bir
**Güncelleme** düğmesi kalır; ikisi de yeni kurulum dosyasını indirir. Sizden
habersiz hiçbir şey kurulmaz. Kontrol, GitHub'dan küçük bir dosya indirir;
sizin veya projeleriniz hakkında hiçbir bilgi göndermez. *Ayarlar › Uygulama*'dan
kapatılabilir.

### Medinstech imzalı

Kurulum dosyası ve uygulama, Medinstech'in kod imzalama sertifikasıyla
imzalıdır. Windows yayıncıyı *Medinstech Mühendislik ve Teknoloji Anonim
Şirketi* olarak gösterir; başka bir şey gösteriyorsa dosyayı çalıştırmayın.

Yeni bir sürüm, yeterince kişi çalıştırana kadar yine de Windows SmartScreen
uyarısıyla karşılaşabilir. *Ek bilgi*'yi seçin, yayıncının yukarıdaki olduğunu
kontrol edin, sonra *Yine de çalıştır*'a basın.

### Her sürümde neler var

| Dosya | Ne olduğu |
|---|---|
| `LinKit_Studio_Setup_<sürüm>.exe` | Kurulum dosyası |
| `LICENSE.txt`, `LICENSE.tr.txt` | O sürümün lisans sözleşmesi, İngilizce ve Türkçe (kurulum seçtiğiniz dildekini gösterir) |
| `THIRD-PARTY-LICENSES.md` | Uygulamanın içindeki açık kaynak bileşenler ve lisanslarının size tanıdığı haklar |
| `THIRD-PARTY-NOTICES.txt` | Uygulamanın içindeki her açık kaynak bileşenin tam lisans metni |
| `build-manifest.txt` | O derlemenin yapıldığı kütüphane sürümlerinin tam listesi |
| `latest.json` | Uygulamanın yeni sürüm olduğunu öğrenmek için okuduğu dosya |

### Hata bildirimi

Uygulamadaki **Hata bildir** düğmesini kullanın (başlangıç sayfasında veya
*Ayarlar › Uygulama*'da): burada, sürüm ve Windows bilgisi önceden
doldurulmuş bir form açar. Formu
[doğrudan da açabilirsiniz](https://github.com/medinstech/linkit-studio-releases/issues/new/choose).
Bildirim için GitHub hesabı gerekir.

### Lisans

Ticari kullanım dahil, kendi cihazlarınızın tamamında ücretsiz kullanılabilir.
Tam koşullar her sürümdeki `LICENSE.tr.txt` (Türkçe) ve `LICENSE.txt`
(İngilizce) dosyalarındadır.

Uygulama kendi lisanslarına tabi üçüncü taraf bileşenler içerir; bunların
arasında PySide6 üzerinden LGPL v3 lisanslı Qt de var.
`THIRD-PARTY-LICENSES.md` bunun size hangi hakları verdiğini ve kaynak
kodlarına nasıl ulaşacağınızı anlatır.

### Güvenlik

LinKit Studio, uyarı vermeden hareket edebilen fiziksel makineleri kontrol eder.
Donanımınızın güvenli kullanımından siz sorumlusunuz. Güvenlik için hiçbir
zaman yalnızca yazılıma güvenmeyin.

---

<p align="center">
  <sub>LinKit Studio is made by <a href="https://www.medinstech.com/">Medinstech</a>. · LinKit Studio, <a href="https://www.medinstech.com/">Medinstech</a> tarafından geliştirilmektedir.</sub>
</p>
