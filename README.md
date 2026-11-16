<div align="center">
  <h3>🌍 Choose your language / Choisissez votre langue / Scegli la lingua / Dilinizi seçin</h3>
  <a href="#english">🇬🇧 English</a> | <a href="#francais">🇫🇷 Français</a> | <a href="#italiano">🇮🇹 Italiano</a> | <a href="#turkce">🇹🇷 Türkçe</a>
</div>

---

<div id="english"></div>
🇬🇧<br>

# 🚀 Flexweg Deployer | Instant HTML Publishing

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Single File](https://img.shields.io/badge/Single_HTML_File-6366f1?style=for-the-badge&logo=googlechrome&logoColor=white)

A lightweight, fast, client-side web interface delivered as a **single HTML file** to publish and share static HTML pages in seconds via the Flexweg API. Paste your code or drag-and-drop an `.html` file to generate an instant, shareable preview link — no account, no build tools, and no local server required.

## ✨ Features

- **Dual Input Modes**: Switch seamlessly between pasting raw HTML code directly into a monospace editor or uploading `.html` / `.htm` files.
- **Drag & Drop Support**: Intuitive dropzone with visual hover feedback and file validation.
- **Instant Deployment**: Sends HTML content directly to the Flexweg publishing endpoint (`https://www.flexweg.com/ai/publish`) via asynchronous `fetch` requests.
- **One-Click Actions**: Copy the generated URL to your clipboard with visual confirmation or open the live page directly in a new tab.
- **Ephemeral Hosting**: Generated links remain active for **60 minutes**, making it ideal for quick previews, sharing prototypes, or testing snippets.
- **Modern Dark UI**: Sleek Slate & Indigo theme with smooth tab transitions, loading spinner states, and clear success/error feedback boxes.
- **Zero Dependencies**: 100% standalone — no frameworks, no npm packages, and no external CDN scripts required.

## 🛠️ Tech Stack

- **HTML5**: Semantic structure and native FileReader API for client-side file parsing.
- **CSS3**: CSS Custom Properties (variables), Flexbox layout, keyframe animations, and responsive design.
- **JavaScript (Vanilla)**: Asynchronous `fetch` API, Clipboard API, drag-and-drop event handling, and dynamic DOM state management.

## 📁 Project Structure

```
flexweg-deployer/
└── index.html    # The entire application (HTML + CSS + JS in one file)
```

> ⚠️ This project is a **standalone single-file app**. No build step, no separate assets — just open it in a browser and it works.

## 🚀 Installation & Usage

This project is 100% static: no build step, no npm, no backend setup.

1. Download or clone the repository:
   ```bash
   git clone [https://github.com/Bstudio136/flexweg-deployer.git](https://github.com/Bstudio136/flexweg-deployer.git)
   ```
2. Open `index.html` directly in any modern web browser.
3. Choose **📝 Coller le code** (Paste code) or **📂 Fichier HTML** (Upload file).
4. Click **🚀 Déployer sur Flexweg**.
5. Copy or open your temporary live link (valid for 60 minutes).

## ⚙️ Configuration & Notes

- **API Endpoint**: Deployments are sent via `POST` (JSON payload `{ "html": "..." }`) to `https://www.flexweg.com/ai/publish`.
- **Link Expiration**: Hosted pages automatically expire after **60 minutes**. Do not use this tool for permanent production hosting.
- **Accepted Formats**: File upload strictly validates `.html` and `.htm` extensions.

## 👨‍💻 Author

**Bstudio136**

- 🐙 GitHub : [@Bstudio136](https://github.com/Bstudio136)
- 🎵 TikTok : [@bstudio136](https://tiktok.com/@bstudio136)
- 🐦 Twitter / X : [@Bstudio136](https://x.com/Bstudio136)
- 📺 YouTube : [@Bstudio136](https://www.youtube.com/@Bstudio136)

## 📄 License

This project is under the MIT License. You are free to use and modify it for your own needs.

<a href="https://hiddenswap.com/pay/AgRPwfFe" target="_blank" rel="noopener"><img src="https://hiddenswap.com/pay/AgRPwfFe/button.svg" alt="Donate with any coin" width="247" height="44"></a>

---

<div id="francais"></div>
🇫🇷<br>

# 🚀 Flexweg Deployer | Publication HTML Instantanée

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Single File](https://img.shields.io/badge/Fichier_HTML_Unique-6366f1?style=for-the-badge&logo=googlechrome&logoColor=white)

Une interface web légère, rapide et 100% côté client, livrée en **un seul fichier HTML**, permettant de publier et partager des pages HTML statiques en quelques secondes via l'API Flexweg. Collez votre code ou glissez-déposez un fichier `.html` pour générer un lien de prévisualisation instantané — sans compte, sans outil de build et sans serveur local.

## ✨ Fonctionnalités

- **Double Mode de Saisie** : Basculez facilement entre le collage direct de code HTML dans un éditeur monospace et l'importation de fichiers `.html` / `.htm`.
- **Glisser-Déposer (Drag & Drop)** : Zone de dépôt intuitive avec retour visuel au survol et validation du format de fichier.
- **Déploiement Instantané** : Envoie le contenu HTML directement vers l'API de publication Flexweg (`https://www.flexweg.com/ai/publish`) via des requêtes asynchrones `fetch`.
- **Actions en Un Clic** : Copiez l'URL générée dans le presse-papiers avec confirmation visuelle ou ouvrez la page en direct dans un nouvel onglet.
- **Hébergement Éphémère** : Les liens générés restent actifs pendant **60 minutes**, idéal pour des aperçus rapides, le partage de prototypes ou le test de code.
- **Interface Sombre Moderne** : Thème élégant Slate & Indigo avec transitions d'onglets fluides, indicateur de chargement et encarts de statut clairs (succès/erreur).
- **Zéro Dépendance** : 100% autonome — aucun framework, aucun paquet npm et aucun script CDN externe requis.

## 🛠️ Technologies Utilisées

- **HTML5** : Structure sémantique et API native `FileReader` pour la lecture des fichiers côté client.
- **CSS3** : Variables CSS personnalisées, mise en page Flexbox, animations `@keyframes` et design responsive.
- **JavaScript (Vanilla)** : API `fetch` asynchrone, API Clipboard, gestion des événements glisser-déposer et manipulation dynamique du DOM.

## 📁 Structure du Projet

```
flexweg-deployer/
└── index.html    # L'application complète (HTML + CSS + JS dans un seul fichier)
```

> ⚠️ Ce projet est une **application autonome en un seul fichier**. Aucune étape de build, aucun asset séparé — ouvrez-la dans un navigateur et ça fonctionne.

## 🚀 Installation & Utilisation

Ce projet est 100% statique : aucune étape de build, pas de npm, pas de backend.

1. Téléchargez ou clonez le dépôt :
   ```bash
   git clone [https://github.com/Bstudio136/flexweg-deployer.git](https://github.com/Bstudio136/flexweg-deployer.git)
   ```
2. Ouvrez `index.html` directement dans n'importe quel navigateur web moderne.
3. Choisissez **📝 Coller le code** ou **📂 Fichier HTML**.
4. Cliquez sur **🚀 Déployer sur Flexweg**.
5. Copiez ou ouvrez votre lien temporaire en direct (valable 60 minutes).

## ⚙️ Configuration & Notes

- **Point de Terminaison API** : Les déploiements sont envoyés via `POST` (charge utile JSON `{ "html": "..." }`) vers `https://www.flexweg.com/ai/publish`.
- **Expiration des Liens** : Les pages hébergées expirent automatiquement après **60 minutes**. Ne pas utiliser cet outil pour un hébergement de production permanent.
- **Formats Acceptés** : L'import de fichier valide strictement les extensions `.html` et `.htm`.

## 👨‍💻 Auteur

**Bstudio136**

- 🐙 GitHub : [@Bstudio136](https://github.com/Bstudio136)
- 🎵 TikTok : [@bstudio136](https://tiktok.com/@bstudio136)
- 🐦 Twitter / X : [@Bstudio136](https://x.com/Bstudio136)
- 📺 YouTube : [@Bstudio136](https://www.youtube.com/@Bstudio136)

## 📄 Licence

Ce projet est sous licence MIT. Vous êtes libre de l'utiliser et de le modifier pour vos propres besoins.

<a href="https://hiddenswap.com/pay/AgRPwfFe" target="_blank" rel="noopener"><img src="https://hiddenswap.com/pay/AgRPwfFe/button.svg" alt="Donate with any coin" width="247" height="44"></a>

---

<div id="italiano"></div>
🇮🇹<br>

# 🚀 Flexweg Deployer | Pubblicazione HTML Istantanea

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Single File](https://img.shields.io/badge/Singolo_File_HTML-6366f1?style=for-the-badge&logo=googlechrome&logoColor=white)

Un'interfaccia web leggera, veloce e 100% lato client, distribuita come **un singolo file HTML**, per pubblicare e condividere pagine HTML statiche in pochi secondi tramite l'API Flexweg. Incolla il tuo codice o trascina un file `.html` per generare subito un link condivisibile — nessun account, nessuno strumento di build e nessun server locale richiesto.

## ✨ Funzionalità

- **Doppia Modalità di Input**: Passa facilmente dall'incollare codice HTML grezzo in un editor monospace al caricamento di file `.html` / `.htm`.
- **Supporto Drag & Drop**: Area di trascinamento intuitiva con feedback visivo al passaggio del mouse e convalida del file.
- **Distribuzione Istantanea**: Invia il contenuto HTML direttamente all'endpoint di pubblicazione Flexweg (`https://www.flexweg.com/ai/publish`) tramite richieste asincrone `fetch`.
- **Azioni con Un Clic**: Copia l'URL generato negli appunti con conferma visiva oppure apri direttamente la pagina live in una nuova scheda.
- **Hosting Temporaneo**: I link generati rimangono attivi per **60 minuti**, ideali per anteprime rapide, condivisione di prototipi o test di codice.
- **Interfaccia Scura Moderna**: Elegante tema Slate & Indigo con transizioni fluide tra le schede, indicatore di caricamento e riquadri chiari per successo ed errori.
- **Zero Dipendenze**: 100% autonomo — nessun framework, nessun pacchetto npm e nessuno script CDN esterno richiesto.

## 🛠️ Tecnologie Utilizzate

- **HTML5**: Struttura semantica e API nativa `FileReader` per la lettura dei file lato client.
- **CSS3**: Variabili CSS personalizzate, layout Flexbox, animazioni `@keyframes` e design responsive.
- **JavaScript (Vanilla)**: API `fetch` asincrona, API Clipboard, gestione degli eventi drag-and-drop e gestione dinamica dello stato del DOM.

## 📁 Struttura del Progetto

```
flexweg-deployer/
└── index.html    # L'intera applicazione (HTML + CSS + JS in un unico file)
```

> ⚠️ Questo progetto è un'**applicazione autonoma in un unico file**. Nessuna fase di build, nessun asset separato — aprilo nel browser e funziona.

## 🚀 Installazione e Utilizzo

Questo progetto è 100% statico: nessuna fase di build, niente npm, nessun backend.

1. Scarica o clona il repository:
   ```bash
   git clone [https://github.com/Bstudio136/flexweg-deployer.git](https://github.com/Bstudio136/flexweg-deployer.git)
   ```
2. Apri `index.html` direttamente in un qualsiasi browser web moderno.
3. Scegli **📝 Coller le code** (Incolla codice) o **📂 Fichier HTML** (Carica file).
4. Clicca su **🚀 Déployer sur Flexweg**.
5. Copia o apri il tuo link temporaneo live (valido per 60 minuti).

## ⚙️ Configurazione e Note

- **Endpoint API**: Le pubblicazioni vengono inviate tramite `POST` (payload JSON `{ "html": "..." }`) a `https://www.flexweg.com/ai/publish`.
- **Scadenza dei Link**: Le pagine ospitate scadono automaticamente dopo **60 minuti**. Non utilizzare questo strumento per hosting di produzione permanente.
- **Formati Accettati**: Il caricamento dei file convalida rigorosamente le estensioni `.html` e `.htm`.

## 👨‍💻 Autore

**Bstudio136**

- 🐙 GitHub : [@Bstudio136](https://github.com/Bstudio136)
- 🎵 TikTok : [@bstudio136](https://tiktok.com/@bstudio136)
- 🐦 Twitter / X : [@Bstudio136](https://x.com/Bstudio136)
- 📺 YouTube : [@Bstudio136](https://www.youtube.com/@Bstudio136)

## 📄 Licenza

Questo progetto è rilasciato sotto licenza MIT. Sei libero di usarlo e modificarlo per le tue esigenze.

<a href="https://hiddenswap.com/pay/AgRPwfFe" target="_blank" rel="noopener"><img src="https://hiddenswap.com/pay/AgRPwfFe/button.svg" alt="Donate with any coin" width="247" height="44"></a>

---

<div id="turkce"></div>
🇹🇷<br>

# 🚀 Flexweg Deployer | Anında HTML Yayınlama

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Single File](https://img.shields.io/badge/Tek_HTML_Dosyas%C4%B1-6366f1?style=for-the-badge&logo=googlechrome&logoColor=white)

Flexweg API aracılığıyla statik HTML sayfalarını saniyeler içinde yayınlamak ve paylaşmak için **tek bir HTML dosyası** olarak sunulan hafif, hızlı ve %100 istemci taraflı bir web arayüzü. Anında paylaşılabilir bir önizleme bağlantısı oluşturmak için kodunuzu yapıştırın veya bir `.html` dosyasını sürükleyip bırakın — hesap, derleme aracı veya yerel sunucu gerekmez.

## ✨ Özellikler

- **Çift Giriş Modu**: Ham HTML kodunu doğrudan monospace editöre yapıştırma ile `.html` / `.htm` dosyalarını yükleme arasında sorunsuzca geçiş yapın.
- **Sürükle ve Bırak Desteği**: Görsel üzerine gelme geri bildirimi ve dosya doğrulamasına sahip sezgisel bırakma alanı.
- **Anında Yayınlama**: HTML içeriğini asenkron `fetch` istekleri aracılığıyla doğrudan Flexweg yayınlama uç noktasına (`https://www.flexweg.com/ai/publish`) gönderir.
- **Tek Tıkla İşlemler**: Oluşturulan URL'yi görsel onayla panonuza kopyalayın veya canlı sayfayı doğrudan yeni bir sekmede açın.
- **Geçici Barındırma**: Oluşturulan bağlantılar **60 dakika** boyunca aktif kalır; hızlı önizlemeler, prototip paylaşımı veya kod testleri için idealdir.
- **Modern Karanlık Arayüz**: Akıcı sekme geçişleri, yükleme göstergesi ve net başarı/hata bildirim kutuları ile şık Slate & Indigo teması.
- **Sıfır Bağımlılık**: %100 bağımsız — framework, npm paketi veya harici CDN betiği gerektirmez.

## 🛠️ Kullanılan Teknolojiler

- **HTML5**: Semantik yapı ve istemci taraflı dosya okuma için yerel `FileReader` API'si.
- **CSS3**: Özel CSS değişkenleri, Flexbox düzeni, `@keyframes` animasyonları ve duyarlı (responsive) tasarım.
- **JavaScript (Vanilla)**: Asenkron `fetch` API, Clipboard API, sürükle-bırak olay yönetimi ve dinamik DOM durum yönetimi.

## 📁 Proje Yapısı

```
flexweg-deployer/
└── index.html    # Tüm uygulama (HTML + CSS + JS tek bir dosyada)
```

> ⚠️ Bu proje **bağımsız, tek dosyalık bir uygulamadır**. Derleme adımı veya ayrı varlıklar yoktur — tarayıcıda açmanız yeterlidir.

## 🚀 Kurulum ve Kullanım

Bu proje %100 statiktir: derleme adımı yok, npm yok, arka uç (backend) kurulumu yok.

1. Depoyu indirin veya klonlayın:
   ```bash
   git clone [https://github.com/Bstudio136/flexweg-deployer.git](https://github.com/Bstudio136/flexweg-deployer.git)
   ```
2. `index.html` dosyasını herhangi bir modern web tarayıcısında doğrudan açın.
3. **📝 Coller le code** (Kodu yapıştır) veya **📂 Fichier HTML** (HTML dosyası yükle) sekmesini seçin.
4. **🚀 Déployer sur Flexweg** butonuna tıklayın.
5. Geçici canlı bağlantınızı kopyalayın veya açın (60 dakika boyunca geçerlidir).

## ⚙️ Yapılandırma ve Notlar

- **API Uç Noktası**: Yayınlamalar `POST` yöntemiyle (JSON yükü `{ "html": "..." }`) `https://www.flexweg.com/ai/publish` adresine gönderilir.
- **Bağlantı Süresi**: Barındırılan sayfaların süresi **60 dakika** sonra otomatik olarak dolar. Kalıcı üretim barındırması için kullanmayın.
- **Kabul Edilen Formatlar**: Dosya yükleme yalnızca `.html` ve `.htm` uzantılarını doğrular.

## 👨‍💻 Yazar

**Bstudio136**

- 🐙 GitHub : [@Bstudio136](https://github.com/Bstudio136)
- 🎵 TikTok : [@bstudio136](https://tiktok.com/@bstudio136)
- 🐦 Twitter / X : [@Bstudio136](https://x.com/Bstudio136)
- 📺 YouTube : [@Bstudio136](https://www.youtube.com/@Bstudio136)

## 📄 Lisans

Bu proje MIT Lisansı altındadır. Kendi ihtiyaçlarınız doğrultusunda kullanmakta ve değiştirmekte özgürsünüz.

<a href="https://hiddenswap.com/pay/AgRPwfFe" target="_blank" rel="noopener"><img src="https://hiddenswap.com/pay/AgRPwfFe/button.svg" alt="Donate with any coin" width="247" height="44"></a>
