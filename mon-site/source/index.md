---
title: WikisTesting
---
<div align = center>
  <img src="https://fastly.jsdelivr.net/gh/D-Sketon/blog-img/icon.png"/>
  <h1>hexo-theme-reimu</h1>
  <img alt="NPM License" src="https://img.shields.io/npm/l/hexo-theme-reimu">
  <img alt="NPM Version" src="https://img.shields.io/npm/v/hexo-theme-reimu">
  <img alt="NPM Downloads" src="https://img.shields.io/npm/dm/hexo-theme-reimu">
  <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/D-Sketon/hexo-theme-reimu">

💘 Hakurei Reimu 💘

[Démo](https://d-sketon.github.io)

[简体中文](https://github.com/D-Sketon/hexo-theme-reimu/blob/main/README.md) | English

<img src="https://cdn.jsdelivr.net/gh/D-Sketon/hexo-theme-reimu@main/_screenshot/Reimu.png"/>
</div>

---

> [!AVERTISSEMENT]
> Les versions inférieures à v1.0.0 sont dépréciées. Veuillez mettre à jour vers la version v1.0.0 ou supérieure dès que possible.

Un thème Hexo inspiré du style Hakurei Reimu.  
Une combinaison des thèmes [landscape](https://github.com/hexojs/hexo-theme-landscape), [Tangyuxian](https://github.com/tangyuxian/hexo-theme-tangyuxian) et [Shoka](https://github.com/amehime/hexo-theme-shoka).

| Framework                    | Dépôt                                                              | Version                                                                                                                                                                                     | Étoiles                                                                                              |
| ---------------------------- | ------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| [Hexo](https://hexo.io/)     | [hexo-theme-reimu](https://github.com/D-Sketon/hexo-theme-reimu)   | <img alt="version" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fgithub.com%2FD-Sketon%2Fhexo-theme-reimu%2Fraw%2Fmain%2Fpackage.json&query=%24.version&label=version">  | <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/D-Sketon/hexo-theme-reimu">  |
| [Hugo](https://gohugo.io)    | [hugo-theme-reimu](https://github.com/D-Sketon/hugo-theme-reimu)   | <img alt="version" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fgithub.com%2FD-Sketon%2Fhugo-theme-reimu%2Fraw%2Fmain%2Fpackage.json&query=%24.version&label=version">  | <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/D-Sketon/hugo-theme-reimu">  |
| [Astro](https://astro.build) | [astro-theme-reimu](https://github.com/D-Sketon/astro-theme-reimu) | <img alt="version" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fgithub.com%2FD-Sketon%2Fastro-theme-reimu%2Fraw%2Fmain%2Fpackage.json&query=%24.version&label=version"> | <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/D-Sketon/astro-theme-reimu"> |

**Les Issues et PR sont les bienvenus !**

## Fonctionnalités

### Fonctionnalités de base
- ✨ Fonctionnalités complètes de blog
- 🔄 Compatible avec Hexo 6+
- 📱 Mise en page responsive
- 🌙 Mode sombre
- 🅰️ Support i18n

### Code & Maths
- 🖥️ Coloration syntaxique & copie de code
- ➗ Support des formules mathématiques KaTeX / MathJax3
- 📊 Support des diagrammes Mermaid

### Recherche & Commentaires
- 🔍 Intégration Algolia
- 🔍 Recherche locale
- 💬 Plusieurs systèmes de commentaires :
  - Valine
  - Waline
  - Twikoo
  - Gitalk
  - Giscus
  - Disqus
  - Utterances
  - Beaudar

### Statistiques & Analytique
- 📊 Statistiques de lecture (Valine / Waline)
- 👥 Compteur de visiteurs (Busuanzi)

### Médias & Interactivité
- 🎵 Lecteur de musique :
  - Aplayer
  - Meting
- 🖼️ Chargement différé des images
- ⚡ Animations de chargement
- 🖱️ Effets de souris :
  - Effets d'animation
  - Style curseur Reimu
- 👾 Intégration Live2D / Live2D-widgets

### Navigation & Structure
- 📑 Table des matières
- 🔄 Support PJAX
- 🔧 ServiceWorker
- 📰 Flux RSS

### Design & Personnalisation
- 🎨 Support d'icônes :
  - Iconfont
  - FontAwesome7
- 🔗 Plugins de balises intégrés :
  - Liens internes
  - Liens externes
  - Liens d'amis
  - Carte de chaleur
  - Roulette de tags
  - Onglets
  - Galerie
- 🎨 Adaptation dynamique des couleurs du thème
- 🎨 Conteneurs personnalisés
- ©️ Déclaration de droits d'auteur
- 🌐 Configuration CDN personnalisée
- 📜 Police de caractères personnalisée
- 🎨 Fonctionnalité de carte de partage

## Installation

> Pour les débutants, vous pouvez utiliser directement [reimu-template](https://github.com/D-Sketon/reimu-template). Il est préinstallé avec hexo, hexo-theme-reimu et d'autres packages. Il suffit de cloner le dépôt, installer les dépendances et modifier la configuration pour obtenir un blog de base !

Via npm :

```bash
npm install hexo-theme-reimu --save
```

Ou cloner ce dépôt directement dans le dossier `/themes` et le renommer `reimu` :

```bash
git clone https://github.com/D-Sketon/hexo-theme-reimu.git
```

Puis modifier le thème dans `_config.yml` :

```yaml
theme: reimu
```

## Utilisation

<details>
<summary>Structure de base</summary>

### Structure de base

Pour assurer un affichage correct, référez-vous à `_example` et créez les dossiers `_data`, `about` et `friend` dans `source` (Note : il s'agit du dossier `source` à la racine de votre blog, pas celui du thème !)

**Exemple de structure de répertoire :**

```
source/
├── images/
│   └── favicon.ico        # Favicon du site
├── _data/
│   ├── avatar/
│   │   └── avatar.webp    # Fichier avatar
│   ├── covers.yml         # Liste d'URLs de couvertures
│   └── covers/            # Dossier de couvertures
├── about/                 # Page À propos
│   └── index.md
├── friend/                # Page liens d'amis
│   ├── index.md
│   └── _data.yml          # Données des liens d'amis
└── _posts/                # Dossier des articles
    └── xxxx.md
```

#### \_data

- Le dossier `avatar` contient l'avatar de l'auteur, nommé `avatar.webp` par défaut. Configurable dans `_config.yml` :

```yaml
avatar: "avatar.webp" # Par défaut, cherche dans le dossier avatar. Ne pas inclure le chemin.
```

- Le dossier `covers` contient les images de couverture
- `covers.yml` contient les URLs des couvertures

#### about

`index.md` sert de page **À propos**

#### friend

`index.md` sert de page **Amis**. Remplissez `_data.yml` pour afficher les cartes de liens d'amis.

</details>

<details>
<summary>Images de couverture, bannière et favicon</summary>

### Images de couverture, bannière et favicon

#### Images de couverture

La logique d'affichage de `banner` et `cover` est la suivante :

- L'image d'en-tête de l'article préfère le `banner` du Front-matter ; si absent, utilise `cover` pour la compatibilité.
- Si ni `banner` ni `cover` ne sont définis, l'image utilise le `cover` global dans `_config.yml`, puis le `banner` global.
- La couverture de la carte de liste préfère le `cover` du Front-matter (URL uniquement). Si absent, utilise les images aléatoires de `source/_data/covers` et `source/_data/covers.yml`.
- Si aucune couverture aléatoire n'est disponible, utilise le `banner` global.

Usage recommandé (image d'en-tête et couverture séparées) :

```yaml
---
title: Bonjour le monde
banner: https://example.com/post-header.webp
cover: https://example.com/post-card.webp
---
```

Usage rétrocompatible (cover uniquement) :

```yaml
---
title: Bonjour le monde
cover: https://example.com/cover.webp
---
```

#### Bannière

L'image de bannière est stockée dans `themes/reimu/source/images/banner.webp`, configurable dans `_config.yml` :

```yaml
banner: "/images/banner.webp"
```

#### Favicon

Le favicon est stocké dans `themes/reimu/source/images/favicon.ico`, configurable dans `_config.yml` :

```yaml
favicon: "/images/favicon.ico"
```

#### Articles épinglés

Ajoutez `sticky: true` au Front-matter de l'article pour l'épingler :

```yaml
---
title: Bonjour le monde
sticky: true
---
```

#### Résumé d'article

Désactivé par défaut. Vous pouvez afficher le résumé dans le sous-titre ou au début de l'article.

```yaml
summary:
  enable: false
  style: 'subtitle' # 'subtitle' ou 'blockquote'
```

</details>

<details>
<summary>Barre latérale</summary>

### Barre latérale

#### Position

Par défaut à droite. Modifiable dans `_config.yml` :

```yaml
sidebar:
  position: right # left | right | false
  menu: true # afficher le bouton de menu de la barre latérale (ignoré sur mobile)
  article:
    show_common: true # afficher la barre latérale commune sur les pages d'article (ignoré sur mobile)
```

Contrôlable aussi via le Front-matter (prioritaire sur la config globale) :

```yaml
---
sidebar: left # left | right | false
---
```

> Quand sidebar est `false`, la barre latérale est masquée, ainsi que le lecteur aplayer et les widgets.

#### Table des matières

Activée par défaut. Modifiable dans `_config.yml` :

```yaml
toc: true # true | false
```

Contrôlable aussi via le Front-matter :

```yaml
---
toc: true # true | false
---
```

Options supplémentaires :

```yaml
toc_options:
  list_number: true # Afficher les numéros de liste
  min_depth: 1 # Profondeur minimale
  max_depth: 6 # Profondeur maximale
```

#### Liens sociaux

Configurables dans `_config.yml` :

```yaml
social:
  github: https://github.com/votrenom
  bilibili: https://space.bilibili.com/votrenom
  tiktok: https://www.tiktok.com/@votrenom
```

#### Widgets

```yaml
widgets:
  # - category
  # - tag
  # - tagcloud
  # - archive
  # - recent_posts
```

Options supplémentaires :

```yaml
archive_type: "monthly" # monthly | yearly
show_count: false
recent_posts_limits: 5
only_show_capsule_in_index: false
uppercase_capsule: true
show_update_time: false
```

</details>

<details>
<summary>Pied de page</summary>

### Pied de page

#### Informations de base

```yaml
footer:
  since: 2020 # Année de départ affichée dans le copyright
  powered: true # Afficher les informations de copyright
  count: true # Afficher le nombre de mots et le temps de lecture
  busuanzi: true # Activer le compteur de visiteurs Busuanzi
```

#### Numéro ICP

Pour les sites hébergés en Chine continentale :

```yaml
icp:
  icpnumber: # Numéro ICP
  beian: # Numéro du Bureau de sécurité publique
  recordcode: # Code d'enregistrement
```

#### ICP Moe (v1.9.1+)

```yaml
moe_icp:
  icpnumber: # Numéro ICP Moe
```

</details>

<details>
<summary>Blocs de code</summary>

### Blocs de code

Assurez-vous que votre `_config.yml` externe contient :

(Hexo <7.0.0)

```yaml
highlight:
  enable: true
  wrap: true
  hljs: false
prismjs:
  enable: false
```

(Hexo >=7.0.0)

```yaml
syntax_highlighter: highlight.js
highlight:
  wrap: true
  hljs: false
```

Configuration de la copie dans `_config.yml` :

```yaml
clipboard:
  success: 
    en: Copy successfully (*^▽^*)
    zh-CN: 复制成功 (*^▽^*)
    zh-TW: 複製成功 (*^▽^*)
    ja: コピー成功 (*^▽^*)
  fail: 
    en: Copy failed (ﾟ⊿ﾟ)ﾂ
    zh-CN: 复制失败 (ﾟ⊿ﾟ)ﾂ
    zh-TW: 複製失敗 (ﾟ⊿ﾟ)ﾂ
    ja: コピー失敗 (ﾟ⊿ﾟ)ﾂ
  copyright:
    enable: false
    count: 50
    license_type: by-nc-sa
```

État d'expansion par défaut (v1.1.0+) :

```yaml
code_block:
  expand: true # true | false | nombre
```

</details>

<details>
<summary>Commentaires</summary>

### Commentaires

> Les commentaires peuvent être contrôlés individuellement via `comments` dans le Front-matter.

Configuration globale :

```yaml
comment:
  title: Dites quelque chose !
  default: waline # Système par défaut quand plusieurs sont activés
```

Pour [Valine](https://valine.js.org/) :

```yaml
valine:
  enable: true
  appId: "votre appId"
  appKey: "votre appKey"
  pageSize: 10
  avatar: mp
  placeholder: Laissez un commentaire
  guest_info: nick,mail,link
  recordIP: true
  highlight: true
  visitor: false
  serverURLs:
```

Pour [Waline](https://waline.js.org/) :

```yaml
waline:
  enable: true
  serverURL: "votre url serveur"
  locale: {}
  emoji:
    - https://unpkg.com/@waline/emojis@1.2.0/weibo
    - https://unpkg.com/@waline/emojis@1.2.0/bilibili
  meta:
    - nick
    - mail
    - link
  requiredMeta:
    - nick
    - mail
  wordLimit: 0
  pageSize: 10
  pageview: true
```

Pour [Twikoo](https://twikoo.js.org) :

```yaml
twikoo:
  enable: true
  envId:
  region:
```

Pour [Giscus](https://giscus.app/) :

```yaml
giscus:
  enable: true
  repo: "votre repo"
  repoId: "votre repoId"
  category: "votre catégorie"
  categoryId: "votre categoryId"
  mapping: mapping
  strict: 0
  reactionsEnabled: 1
  emitMetadata: 0
  inputPosition: bottom
  theme:
    light:
    dark:
```

Pour [Gitalk](https://gitalk.github.io/) :

```yaml
gitalk:
  enable: true
  clientID: "votre client ID"
  clientSecret: "votre client secret"
  repo: "votre repo"
  owner: "propriétaire du repo"
  admin: "propriétaire et collaborateurs"
  md5: false
```

Pour [Disqus](https://disqus.com/) :

```yaml
disqus:
  enable: true
  shortname: "votre shortname"
  count: true
```

Pour [Utterances](https://utteranc.es/) :

```yaml
utterances:
  enable: true
  repo: proprietaire/repo
  issue_term: title
  theme: github-light
```

Pour [Beaudar](https://beaudar.lipk.org/) :

```yaml
beaudar:
  enable: true
  repo: proprietaire/repo
  branch: main
  issue_term: title
  issue_number:
  theme: auto
  label:
  input_position: top
  comment_order: desc
  keep_theme:
  loading:
```

</details>

<details>
<summary>Recherche sur le site</summary>

### Recherche sur le site

> Ne pas activer Algolia et la recherche locale en même temps.

Pour [Algolia](https://www.algolia.com/), installez [@reimujs/hexo-algoliasearch](https://github.com/D-Sketon/hexo-algoliasearch) :

```bash
npm install @reimujs/hexo-algoliasearch --save
```

Configuration dans `_config.yml` externe :

```yml
algolia:
  appId: "votre applicationID"
  apiKey: "votre apiKey"
  adminApiKey: "votre adminApiKey"
  indexName: "votre indexName"
  chunkSize: 5000
  fields:
    - content:strip:truncate,0,500
    - excerpt:strip
    - gallery
    - permalink
    - photos
    - slug
    - tags
    - title
```

Dans `_config.yml` interne :

```yaml
algolia_search:
  enable: true
```

Puis générez l'index :

```bash
hexo algolia
```

Pour la recherche locale (intégrée depuis v1.5.0) :

```yaml
generator_search:
  enable: true
  field: post
  content: true
```

</details>

<details>
<summary>Formules mathématiques</summary>

### Formules mathématiques

Installez [@reimujs/hexo-renderer-markdown-it-plus](https://github.com/D-Sketon/hexo-renderer-markdown-it-plus) :

```bash
npm uninstall hexo-renderer-marked --save
npm install @reimujs/hexo-renderer-markdown-it-plus --save
```

Désactivé par défaut. Pour activer :

#### KaTeX (rendu côté serveur)

```yaml
math:
  enable: true
  katex:
    enable: true
    autoRender: false
```

#### KaTeX (rendu côté client)

```yaml
math:
  enable: true
  katex:
    enable: true
    autoRender: true
```

Ajoutez dans `_config.yml` externe :

```yaml
markdown_it_plus:
  rawLaTeX: true
```

#### MathJax3

```yaml
math:
  enable: true
  mathjax:
    enable: true
    options:
```

</details>

<details>
<summary>Diagrammes Mermaid</summary>

### Diagrammes Mermaid

Installez [hexo-filter-mermaid-diagrams](https://github.com/webappdevelp/hexo-filter-mermaid-diagrams) :

```bash
npm install hexo-filter-mermaid-diagrams --save
```

Dans `_config.yml` interne :

```yaml
mermaid:
  enable: true
  zoom: false
```

Ajoutez dans le Front-matter des articles concernés :

```yaml
---
title: Bonjour le monde
mermaid: true
---
```

</details>

<details>
<summary>RSS</summary>

### RSS

Installez [hexo-generator-feed](https://github.com/hexojs/hexo-generator-feed) :

```bash
npm install hexo-generator-feed --save
```

Puis ajoutez dans `_config.yml` interne :

```yaml
rss: atom.xml
```

</details>

<details>
<summary>i18n</summary>

### i18n

Cinq langues disponibles par défaut : `en`, `zh-CN`, `zh-TW`, `ja` et `pt-BR`. Changez la langue dans `_config.yml` externe :

```yaml
language: fr
```

Support multilingue expérimental (v1.4.0+) :

```yaml
i18n:
  enable: false
  type: [page, post]
  generator: [archive, category, tag, index]
  languages: [zh-CN, en]
```

Pour les articles multilingues, ajoutez `lang` dans le Front-matter :

```yaml
lang: en
```

</details>

<details>
<summary>Icônes</summary>

### Icônes

Par défaut, utilise l'iconfont intégré (v0.1.3+) :

```yml
icon_font: 4552607_0khxww3tj3q9
```

Pour utiliser FontAwesome, mettez `icon_font` à `false` :

```yml
fontawesome:
  high_priority:
    - src: webcache|@fortawesome/fontawesome-free@7.1.0/css/regular.min.css
      integrity: sha384-4qYppzjH8EiA+cGdaubu2vL7Rk8WGiqCSj7oRuP1uwtFWkfKNHD20lPfcrbQc8dU
    - src: webcache|@fortawesome/fontawesome-free@7.1.0/css/solid.min.css
      integrity: sha384-wbMWab3UDSPm2kvIgVOn/d9KPTecgPU1+Nb3zoQrm/oVu0EkPL6IaKinjbwW0rum
  low_priority:
    - src: webcache|@fortawesome/fontawesome-free@7.1.0/css/brands.min.css
      integrity: sha384-KTGeC2hIMzpeQakhsmzB9bZfhCD5xZZCgI1iZH6f/O457SxzlkzTQg/WXFNoi3ih
```

</details>

<details>
<summary>Fonctionnalités avancées</summary>

### Fonctionnalités avancées

#### Retour en haut

Activé par défaut :

```yaml
top:
  enable: true
  position: right # left | right
```

#### Mode sombre

```yaml
dark_mode:
  enable: auto # true | false | auto
```

#### Analytique

```yaml
baidu_analytics: false
google_analytics: false
clarity: false
```

#### Barre de progression Pace

Activée par défaut :

```yaml
pace:
  enable: true
```

#### Feux d'artifice

Activés par défaut :

```yaml
firework:
  enable: true
  disable_on_mobile: false
  options:
```

#### PJAX

Désactivé par défaut :

```yaml
pjax:
  enable: false
```

> PJAX ne peut pas être utilisé avec `relative_link: true` !

#### ServiceWorker

Désactivé par défaut :

```yaml
service_worker:
  enable: false
```

#### Live2D

Désactivé par défaut :

```yaml
live2d:
  enable: false
  position: left # left | right
```

#### Live2D Widgets

```yaml
live2d_widgets:
  enable: false
  position: left # left | right
```

#### Curseur Reimu

Activé par défaut :

```yml
reimu_cursor:
  enable: true
  cursor:
    default: ../images/cursor/reimu-cursor-default.png
    pointer: ../images/cursor/reimu-cursor-pointer.png
    text: ../images/cursor/reimu-cursor-text.png
```

#### Bannière responsive (v0.2.0+)

```yml
banner_srcset:
  enable: false
  srcset:
    - src: "/images/banner-600w.webp"
      media: "(max-width: 479px)"
    - src: "/images/banner-800w.webp"
      media: "(max-width: 799px)"
    - src: "/images/banner.webp"
      media: "(min-width: 800px)"
```

#### Notice de droits d'auteur (v0.2.0+)

```yml
article_copyright: 
  enable: false
  content:
    author:
    link:
    title:
    date:
    updated:
    license:
    license_type: by-nc-sa
```

#### Quicklink (v0.2.3+)

```yaml
quicklink:
  enable: false
  timeout: 3000
  priority: true
  ignores: []
```

#### Avertissement contenu périmé (v0.2.4+)

```yaml
outdate:
  enable: false
  daysAgo: 180
  message:
    en: This article was last updated on {time}. Please note that the content may no longer be applicable.
    zh-CN: 本文最后更新于 {time}，请注意文中内容可能已不适用。
    fr: Cet article a été mis à jour pour la dernière fois le {time}. Notez que le contenu peut ne plus être applicable.
```

#### Sponsoring (v0.3.2+)

```yaml
sponsor:
  enable: false
  tip:
    zh-CN: 请作者喝杯咖啡吧
    en: Buy me a coffee
    fr: Offrez un café à l'auteur
  icon:
    url: "../images/taichi.png"
    rotate: true
    mask: true
  qr:
    - name: Alipay
      src: "/sponsor/alipay.jpg"
```

#### Carte de catégories sur la page d'accueil (v1.0.0+)

```yaml
home_categories:
  enable: false
  content:
    - categories:
      cover:
```

#### Lecteur de musique (v1.2.0+)

```yaml
player:
  disable_on_mobile: false
  position: before_sidebar # before_sidebar / after_sidebar / after_widget
  aplayer:
    enable: true
    options:
      audio: []
      fixed:
      autoplay:
      loop:
      order:
      preload: 
      volume:
      mutex:
      listFolded:
      lrcType:
  meting:
    enable: true
    meting_api:
    options:
      id: 
      server: 
      type: 
      auto:
```

#### Partage (v1.3.0+)

```yaml
share:
  # - facebook
  # - twitter
  # - bluesky
  # - linkedin
  # - reddit
  # - weibo
  # - qq
  # - weixin
```

#### Injecteur (v1.5.1+)

```yaml
injector:
  head_begin:
  head_end:
  body_begin:
  body_end:
  sidebar_begin:
  sidebar_end:
```

#### Badge triangulaire (v1.10.2+)

```yaml
triangle_badge:
  enable: false
  icon: github
  link: https://github.com/D-Sketon/hexo-theme-reimu
```

#### Ancres de paragraphe (v1.12.5+)

```yaml
anchor:
  explicit:
    enable: false
    marker: "{#anchor-"
    prefix: "anchor-"
  auto:
    enable: false
    length: 60
```

</details>

<details>
<summary>Plugins de balises intégrés</summary>

### Plugins de balises intégrés

#### friendLink — Carte de lien d'ami

```markdown
{% friendsLink chemin %}
```

#### link (v1.11.0+)

```markdown
{% link slug|titre [titre] [couverture]|"auto" [échappement] %}
```

Version améliorée de `externalLinkCard` et `postLinkCard`. Recommandé.

#### tabs (v1.11.0+)

```markdown
{% tabs [ongletActif] ["center"] %}
<!-- NomOnglet -->
Contenu de l'onglet
<!-- NomOnglet -->
Contenu de l'onglet
{% endtabs %}
```

#### Galerie (v1.11.0+)

```markdown
{% gallery %}
![texte alternatif](url_image1)
![texte alternatif](url_image2)
{% endgallery %}
```

#### Grille (v1.11.1+)

```markdown
{% grid [largeur] [col] %}
<!-- cell -->
Contenu 1
<!-- cell -->
Contenu 2
{% endgrid %}
```

#### Bloc de citation d'alerte (v1.11.1+)

```markdown
{% alertBlockquote [type] [titre] %}
Contenu de la citation
{% endalertBlockquote %}
```

Types disponibles : `info`, `tip`, `important`, `warning`, `danger`

#### Bloc de détails (v1.11.1+)

```markdown
{% details [résumé] %}
Contenu des détails
{% enddetails %}
```

</details>

<details>
<summary>Conteneurs personnalisés</summary>

### Conteneurs personnalisés

Nécessite [@reimujs/hexo-renderer-markdown-it-plus](https://github.com/D-Sketon/hexo-renderer-markdown-it-plus).

```markdown
::: info
Ceci est une boîte d'information.
:::

::: tip
Ceci est un conseil.
:::

::: important
Ceci est important.
:::

::: warning
Ceci est un avertissement.
:::

::: danger
Ceci est un avertissement de danger.
:::

::: details INFO
Ceci est un bloc de détails.
:::
```

</details>

<details>
<summary>Personnalisation du thème</summary>

### Personnalisation du thème

#### Adaptation dynamique des couleurs (v1.7.0+, expérimental)

```yml
material_theme:
  enable: false
```

#### Couleurs personnalisées

```yaml
internal_theme:
  light:
    --red-0: "#ff0000"
    --red-1: "#ff5252"
    # ... (voir documentation complète)
  dark:
    --red-4: "rgba(255, 208, 208, 0.5)"
    # ... (voir documentation complète)
```

#### Polices personnalisées

```yaml
font:
  enable: true
  article:
    - Mulish
    - Noto Serif SC
  code:

local_font:
  article:
    - "-apple-system"
    - PingFang SC
    - sans-serif
  code:
    - Menlo
    - monospace

custom_font:
  enable: true
  article:
    - css: https://fontsapi.zeoseven.com/292/main/result.css
      name: LXGW WenKai
  code:
```

#### Icônes du menu

```yaml
menu:
  - name: accueil
    url: /
    icon:
  - name: archives
    url: /archives
    icon: f0c1
  - name: à propos
    url: /about
    icon:
  - name: amis
    url: /friend
    icon:
```

#### Icônes pied de page / retour en haut / sponsor

```yaml
footer:
  icon:
    url: "../images/taichi.png"
    rotate: true
    mask: true

top:
  icon:
    url: "../images/taichi.png"
    rotate: true
    mask: true
```

#### Icône de chargement

```yaml
preloader:
  enable: true
  text:
    zh-CN: 少女祈祷中...
    en: Chargement...
    fr: Chargement...
  icon:
  rotate: true
```

#### Animation de défilement

```yaml
animation:
  enable: true
  options:
    header:
    home:
    article:
    archive:
```

Effets disponibles : fade, flip, slide, zoom (et leurs variantes directionnelles)

#### Largeur maximale

```yaml
layout:
  max_width: 1350px
```

</details>

<details>
<summary>Vendor (CDN)</summary>

### Vendor

`vendor` stocke les ressources tierces. Formats supportés :

- `:cdn|:package@:version/:file` — ex. `cdn_jsdelivr_npm|katex@0.13.11/dist/katex.min.css`
- URL absolue commençant par `https://`
- Chemin local commençant par `/`

CDN disponibles :
```yaml
cdn_jsdelivr_gh: https://cdn.jsdelivr.net/gh/
cdn_jsdelivr_npm: https://cdn.jsdelivr.net/npm/
fastly_jsdelivr_npm: https://fastly.jsdelivr.net/npm/
unpkg: https://unpkg.com/
webcache: https://npm.webcache.cn/
```

Support SRI (vérification d'intégrité) :

```yaml
js:
  clipboard:
    src: webcache|clipboard@2.0.11/dist/clipboard.min.js
    integrity: sha384-J08i8An/QeARD9ExYpvphB8BsyOj3Gh2TSh1aLINKO3L0cMSH2dN3E22zFoXEi0Q
```

</details>

<details>
<summary>Champs Front-matter</summary>

### Champs Front-matter

| Champ       | Description                                              | Type                                               | Valeur par défaut                         | Version       |
| ----------- | -------------------------------------------------------- | -------------------------------------------------- | ----------------------------------------- | ------------- |
| title       | Titre                                                    | `string`                                           | Nom du fichier article                    | Hexo intégré  |
| date        | Date de création                                         | `date`                                             | Date de création du fichier               | Hexo intégré  |
| updated     | Date de mise à jour                                      | `date`                                             | Date de modification du fichier           | Hexo intégré  |
| tags        | Tags                                                     | `string[] \| string[][]`                           | -                                         | Hexo intégré  |
| categories  | Catégories                                               | `string[] \| string[][]`                           | -                                         | Hexo intégré  |
| permalink   | Lien permanent personnalisé                              | `string`                                           | -                                         | Hexo intégré  |
| excerpt     | Extrait de l'article                                     | `string`                                           | -                                         | Hexo intégré  |
| description | Description de l'article                                 | `string`                                           | -                                         | 0.0.1         |
| link        | Redirige vers un lien externe                            | `string`                                           | -                                         | 0.0.1         |
| sticky      | Épingler l'article                                       | `boolean`                                          | `false`                                   | 0.0.1         |
| photos      | Galerie photo de l'article                               | `string[]`                                         | -                                         | 0.0.1         |
| cover       | Couverture de l'article                                  | `https://example.com \| false \| rgb(255,117,117)` | Config globale si absent                  | 0.0.7         |
| mermaid     | Activer mermaid                                          | `boolean`                                          | `false`                                   | 0.2.0         |
| copyright   | Activer la notice de droits d'auteur                     | `boolean`                                          | Config globale si absent                  | 0.3.1         |
| sponsor     | Activer le sponsoring                                    | `boolean`                                          | Config globale si absent                  | 0.3.2         |
| comments    | Activer les commentaires                                 | `boolean`                                          | Config globale si absent                  | 0.3.2         |
| sidebar     | Position de la barre latérale                            | `false \| 'left' \| 'right'`                       | Config globale si absent                  | 1.3.0         |
| lang        | Langue de l'article (nécessite config i18n)              | `string`                                           | -                                         | 1.4.0         |
| toc         | Activer la table des matières                            | `boolean`                                          | Config globale si absent                  | 1.6.0         |
| outdated    | Marquer l'article comme périmé                           | `boolean`                                          | Config globale si absent                  | 1.10.1        |
| author      | Auteur de l'article                                      | `string`                                           | Config globale si absent                  | 1.10.2        |
| keywords    | Mots-clés SEO                                            | `string[] \| string`                               | Config globale si absent                  | 1.10.4        |
| banner      | Image de bannière                                        | `https://example.com \| false \| rgb(255,117,117)` | -                                         | 1.12.2        |

</details>

## Contributeurs

[![](https://contributors-img.web.app/image?repo=D-Sketon/hexo-theme-reimu)](https://github.com/D-Sketon/hexo-theme-reimu/graphs/contributors)

## Projets liés

| Nom du package                                                                                        | Version                                                                              | npm                                                                                     | jsdelivr                                                                                         |
| ----------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| [hexo-theme-reimu](https://github.com/D-Sketon/hexo-theme-reimu)                                      | ![NPM Version](https://img.shields.io/npm/v/hexo-theme-reimu)                        | ![NPM Downloads](https://img.shields.io/npm/dm/hexo-theme-reimu)                        | ![jsDelivr Hits](https://img.shields.io/jsdelivr/npm/hm/hexo-theme-reimu)                        |
| [theme-shokax-pjax](https://github.com/theme-shoka-x/theme-shokax-pjax)                               | ![NPM Version](https://img.shields.io/npm/v/theme-shokax-pjax)                       | ![NPM Downloads](https://img.shields.io/npm/dm/theme-shokax-pjax)                       | ![jsDelivr Hits](https://img.shields.io/jsdelivr/npm/hm/theme-shokax-pjax)                       |
| [mouse-firework](https://github.com/D-Sketon/mouse-firework)                                          | ![NPM Version](https://img.shields.io/npm/v/mouse-firework)                          | ![NPM Downloads](https://img.shields.io/npm/dm/mouse-firework)                          | ![jsDelivr Hits](https://img.shields.io/jsdelivr/npm/hm/mouse-firework)                          |

## Historique des étoiles

[![Star History Chart](https://api.star-history.com/svg?repos=D-Sketon/hexo-theme-reimu&type=date&legend=top-left)](https://www.star-history.com/#D-Sketon/hexo-theme-reimu&type=date&legend=top-left)

## Licence

MIT