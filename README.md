<div align="center">

# 📦 Docs Hub

### Yayına Hazır İçerik Deposu / Publish-Ready Content Repository

[![Type](https://img.shields.io/badge/type-Documentation-informational?style=for-the-badge)](#)
[![Format](https://img.shields.io/badge/format-HTML%20%7C%20PDF%20%7C%20DOCX%20%7C%20Markdown%20%7C%20more-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
&nbsp;


[🇹🇷] Yayına hazır (çevrimiçi) her türlü içeriğin barındırıldığı merkezi bir depo; bu içerikler arasında çeşitli mobil, masaüstü ve web uygulamalarına ait kullanıcı kılavuzları, gizlilik politikaları, veri güvenliği bildirimleri, reklam politikaları ve hedef kitle bilgileri de yer almaktadır.

[🇬🇧] A central repository hosting all kinds of publish-ready (online) content; these contents include, among others, user guides, privacy policies, data security notices, ad policies, and target audience information belonging to various mobile, desktop, and web applications.

&nbsp;
🔗 **Geliştirici / Developer:** [Abdulkadir Güngör](https://abdulkadirgungor.com/)

</div>

---

<div align="center">
  
## 📌 Hakkında / About

</div>

[🇹🇷] Bu depo, yalnızca uygulamalarla sınırlı olmayan, yayına hazır her türlü içeriğin barındırılabileceği genel amaçlı bir platformdur. Şu an için ağırlıklı olarak geliştirilen mobil, masaüstü ve web uygulamalarına ait resmi belgeleri platform bazında düzenli bir şekilde barındırır. Her belge doğrudan tarayıcıda görüntülenebilecek şekilde **HTML** formatında hazırlanır ve GitHub Pages veya benzeri bir statik barındırma üzerinden **online** olarak yayınlanır. Bu sayede her uygulama, mağaza gereksinimleri (Google Play, App Store, Microsoft Store vb.) için gereken gizlilik politikası, veri güvenliği beyanı ve diğer belgelere tek, sabit bir bağlantı (URL) üzerinden erişim sağlayabilir.

[🇬🇧] *This repository is a general-purpose platform for hosting any kind of publish-ready content, not limited to applications. It currently mainly hosts the official documents for developed mobile, desktop, and web applications, organized by platform. Every document is prepared in **HTML** format so it can be viewed directly in a browser, and is published **online** via GitHub Pages or a similar static host. This allows each application to provide a single, stable URL for the privacy policy, data security notice, and other documents required by store guidelines (Google Play, App Store, Microsoft Store, etc.).*

---

<div align="center">
  
## 📁 Klasör Yapısı / Folder Structure

</div>

[🇹🇷] Uygulamalara ait belgeler, `apps` → platform → uygulama adı → belge (`.html`) hiyerarşisiyle organize edilir. Uygulama dışı içerikler için ise depo kökünde ayrı klasörler açılabilir.

[🇬🇧] *Application-related documents are organized in an `apps` → platform → app name → document (`.html`) hierarchy. Non-application content can be organized under separate top-level folders as needed.*

```
├── apps/
│   ├── android/
│   │   └── app-name/
│   │       ├── index.html
│   │       ├── user-guide.html
│   │       ├── privacy-policy.html
│   │       ├── data-security.html
│   │       ├── ad-policy.html
│   │       ├── target-audience.html
│   │       └── ...
│   │
│   ├── appstore/
│   │   └── app-name/
│   │       ├── index.html
│   │       ├── user-guide.html
│   │       ├── privacy-policy.html
│   │       ├── data-security.html
│   │       ├── ad-policy.html
│   │       ├── target-audience.html
│   │       └── ...
│   │
│   ├── windows/
│   │   └── app-name/
│   │       └── ...
│   │
│   └── linux/
│       └── app-name/
│           └── ...
│
└── (diğer içerik türleri için ek klasörler / additional folders for other content types)
```

<div align="center">

| Klasör / Folder             | Platform                  |
| ---------------------------- | -------------------------- |
| `/apps/android/app-name/`    | Android (Google Play)     |
| `/apps/appstore/app-name/`   | iOS / macOS (App Store)   |
| `/apps/windows/app-name/`    | Windows (Microsoft Store) |
| `/apps/linux/app-name/`      | Linux                     |

</div>

[🇹🇷] Her uygulama klasörü aşağıdaki belge türlerinden ihtiyaç duyulanları içerebilir:

[🇬🇧] *Each application folder may include the relevant documents from the list below:*

<div align="center">

| Dosya / File            | Açıklama / Description                                                                        |
| ------------------------ | ------------------------------------------------------------------------------------------------ |
| `user-guide.html`        | [🇹🇷] Kurulum, kullanım ve SSS · [🇬🇧] *Installation, usage & FAQ*                              |
| `privacy-policy.html`    | [🇹🇷] Toplanan veriler ve kullanıcı hakları · [🇬🇧] *Data collected & user rights*              |
| `data-security.html`     | [🇹🇷] Veri saklama, koruma ve işleme yöntemleri · [🇬🇧] *Data storage, protection & processing* |
| `ad-policy.html`         | [🇹🇷] Reklam sağlayıcıları ve izin mekanizmaları · [🇬🇧] *Ad providers & consent mechanisms*    |
| `target-audience.html`   | [🇹🇷] Yaş grubu ve uygunluk beyanı · [🇬🇧] *Age range & suitability declaration*                |

</div>

[🇹🇷] Not: Uygulamalarla ilişkili olmayan yayına hazır içerikler (örn. genel duyurular, kılavuzlar, politika metinleri vb.) `apps/` dışında, konusuna uygun ayrı klasörler altında barındırılabilir.

[🇬🇧] *Note: Publish-ready content unrelated to applications (e.g. general announcements, guides, policy texts, etc.) can be hosted outside of `apps/`, under separate folders suited to their subject.*

---

<div align="center">
  
## 🌐 Yayınlama / Publishing

</div>

[🇹🇷] Depo, **GitHub Pages** üzerinden `docs.abdulkadirgungor.com` alan adıyla statik olarak yayınlanır. Her belgeye, uygulamanın mağaza kaydından veya uygulama içinden aşağıdaki gibi bir URL şablonuyla doğrudan bağlantı verilebilir:

[🇬🇧] *The repository is served as a static site via **GitHub Pages** under the `docs.abdulkadirgungor.com` domain. Each document can be linked directly from the app's store listing or from within the app using a URL pattern like the following:*

```
https://docs.abdulkadirgungor.com/apps/<platform>/<app-name>/<document>.html

Örnek / Example:
https://docs.abdulkadirgungor.com/apps/android/app-name/privacy-policy.html
```

---

<div align="center">

## ➕ Yeni İçerik Ekleme / Adding New Content

</div>


[🇹🇷]

1. Uygulamaya ait bir belge ekleniyorsa, ilgili platform klasörüne (`apps/android/`, `apps/appstore/`, `apps/windows/`, `apps/linux/`) uygulama adıyla yeni bir alt klasör açın; uygulama dışı bir içerikse konusuna uygun bir klasör oluşturun.
2. İhtiyaç duyulan `.html` belgelerini bu klasöre ekleyin.
3. Belgeleri Türkçe ve İngilizce içerecek şekilde (bu README'deki gibi) hazırlayın.
4. Depoyu güncelleyin; GitHub Pages değişiklikleri otomatik olarak yayınlar.

[🇬🇧]

1. *If adding an application document, create a new subfolder named after the app inside the relevant platform folder (`apps/android/`, `apps/appstore/`, `apps/windows/`, `apps/linux/`); for non-application content, create a folder suited to its subject.*
2. *Add the required `.html` documents to this folder.*
3. *Prepare the documents in both Turkish and English (as in this README).*
4. *Push the changes; GitHub Pages will publish the update automatically.*
</div>

---
<div align="center">

## 👤 İletişim / Contact

**Abdulkadir Güngör**

[🇹🇷] Full Stack Geliştirici | Yapay Zeka, Veri Bilimi ve Robotik Uzmanı | Siber Güvenlik, İSG ve İnşaat Yüksek Mühendisi

[🇬🇧] Full Stack Developer | AI, Data Science & Robotics Specialist | Cybersecurity, OHS & MSc in Civil Engineering

📍 İstanbul, Türkiye

[![Email](https://img.shields.io/badge/Email-a.kadir.gungor.86%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:a.kadir.gungor.86@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-abdulkadir--güngör-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdulkadir-güngör/)
[![GitHub](https://img.shields.io/badge/GitHub-abdulkadirgungor86-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/abdulkadirgungor86)
[![Calendly](https://img.shields.io/badge/Randevu-Calendly-006BFF?style=flat-square&logo=calendly&logoColor=white)](https://calendly.com/a-kadir-gungor-86/30min)
[![Website](https://img.shields.io/badge/Web%20Sitesi-abdulkadirgungor.com-4285F4?style=flat-square&logo=googlechrome&logoColor=white)](https://abdulkadirgungor.com/)

</div>

---

<div align="center">

## 📄 Lisans / License

[🇹🇷] 2026 · Abdulkadir Güngör © · Tüm hakları saklıdır.

[🇬🇧] *2026 · Abdulkadir Güngör © · All rights reserved.*

---

⭐ Beğendiyseniz yıldız vermeyi unutmayın! / If you like it, don't forget to star it!

</div>
