  
<h1 align="center"> Data Wheel • Mini Use Cases</h1>

<p align="center">
This repository showcases DMBOK use cases applied to public datasets(Chinook, Northwind, OpenFoodFacts, etc.). To demonstrate, in a concrete and traceable way, how I apply data governance & curation: policies, glossary, quality, security, architecture, and more.
</p>









<!-- ========================= -->
<!-- 🌌 DMBOK2 Data Wheel (EN) -->
<!-- Metallic style • Clickable petals -->
<!-- ========================= -->
<p align="center">
<svg viewBox="0 0 220 220" width="560" xmlns="http://www.w3.org/2000/svg"
     xmlns:xlink="http://www.w3.org/1999/xlink" role="img" aria-labelledby="title desc">
  <title id="title">DMBOK2 Data Wheel — Clickable Petals</title>
  <desc id="desc">Interactive SVG wheel with 11 metallic petals linking to each DMBOK2 chapter folder.</desc>

  <!-- ===== Gradients & Styles (metallic) ===== -->
  <defs>
    <!-- Background radial metallic -->
    <radialGradient id="bgRad" cx="50%" cy="50%" r="60%">
      <stop offset="0%"  stop-color="#151a22"/>
      <stop offset="55%" stop-color="#0f141c"/>
      <stop offset="100%" stop-color="#0a0f17"/>
    </radialGradient>

    <!-- Generic steel gradient for segments (will be tinted with opacity) -->
    <linearGradient id="steel" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%"   stop-color="#e7ecef"/>
      <stop offset="40%"  stop-color="#c8d0d8"/>
      <stop offset="60%"  stop-color="#f8fafc"/>
      <stop offset="100%" stop-color="#b4bec8"/>
    </linearGradient>

    <!-- Inner hub gradient -->
    <linearGradient id="hub" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#222833"/>
      <stop offset="100%" stop-color="#141a24"/>
    </linearGradient>

    <style>
      a:hover path { filter: brightness(1.12); }
      text { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Ubuntu, "Helvetica Neue", Arial, sans-serif; }
      .lbl { fill:#0b0f15; font-size:4px; font-weight:700; text-anchor:middle; }
      .tick { fill:#0b0f15; font-size:3.3px; font-weight:600; text-anchor:middle; }
    </style>
  </defs>

  <!-- ===== Background disc ===== -->
  <circle cx="110" cy="110" r="108" fill="url(#bgRad)"/>

  <!-- ===== Petal template (11 slices, ~32.727° each) =====
       Base wedge path from center to top; others are rotations.
       Each path uses steel gradient + a subtle colored overlay via fill-opacity. -->

  <!-- 1. Data Governance -->
  <a xlink:href="./01-data-governance/" target="_blank">
    <g>
      <path d="M110,110 L110,14 A96,96 0 0,1 163.4,28.3 Z" fill="url(#steel)"/>
      <path d="M110,110 L110,14 A96,96 0 0,1 163.4,28.3 Z" fill="#8ee3d6" fill-opacity="0.35"/>
      <title>1. Data Governance</title>
    </g>
  </a>

  <!-- 2. Data Architecture -->
  <a xlink:href="./02-data-architecture/" target="_blank">
    <g transform="rotate(32.727 110 110)">
      <path d="M110,110 L110,14 A96,96 0 0,1 163.4,28.3 Z" fill="url(#steel)"/>
      <path d="M110,110 L110,14 A96,96 0 0,1 163.4,28.3 Z" fill="#9bc4ff" fill-opacity="0.35"/>
      <title>2. Data Architecture</title>
    </g>
  </a>

  <!-- 3. Data Modeling & Design -->
  <a xlink:href="./03-data-modeling-design/" target="_blank">
    <g transform="rotate(65.454 110 110)">
      <path d="M110,110 L110,14 A96,96 0 0,1 163.4,28.3 Z" fill="url(#steel)"/>
      <path d="M110,110 L110,14 A96,96 0 0,1 163.4,28.3 Z" fill="#ffb0a8" fill-opacity="0.35"/>
      <title>3. Data Modeling & Design</title>
    </g>
  </a>

  <!-- 4. Data Storage & Operations -->
  <a xlink:href="./04-data-storage-operations/" target="_blank">
    <g transform="rotate(98.181 110 110)">
      <path d="M110,110 L110,14 A96,96 0 0,1 163.4,28.3 Z" fill="url(#steel)"/>
      <path d="M110,110 L110,14 A96,96 0 0,1 163.4,28.3 Z" fill="#fde68a" fill-opacity="0.45"/>
      <title>4. Data Storage & Operations</title>
    </g>
  </a>

  <!-- 5. Data Security -->
  <a xlink:href="./05-data-security/" target="_blank">
    <g transform="rotate(130.908 110 110)">
      <path d="M110,110 L110,14 A96,96 0 0,1 163.4,28.3 Z" fill="url(#steel)"/>
      <path d="M110,110 L110,14 A96,96 0 0,1 163.4,28.3 Z" fill="#c7b7ff" fill-opacity="0.35"/>
      <title>5. Data Security</title>
    </g>
  </a>

  <!-- 6. Data Integration & Interoperability -->
  <a xlink:href="./06-data-integration-interoperability/" target="_blank">
    <g transform="rotate(163.635 110 110)">
      <path d="M110,110 L110,14 A96,96 0 0,1 163.4,28.3 Z" fill="url(#steel)"/>
      <path d="M110,110 L110,14 A96,96 0 0,1 163.4,28.3 Z" fill="#9ff2b8" fill-opacity="0.35"/>
      <title>6. Data Integration & Interoperability</title>
    </g>
  </a>

  <!-- 7. Document & Content Management -->
  <a xlink:href="./07-document-content-management/" target="_blank">
    <g transform="rotate(196.362 110 110)">
      <path d="M110,110 L110,14 A96,96 0 0,1 163.4,28.3 Z" fill="url(#steel)"/>
      <path d="M110,110 L110,14 A96,96 0 0,1 163.4,28.3 Z" fill="#f7a8d8" fill-opacity="0.35"/>
      <title>7. Document & Content Management</title>
    </g>
  </a>

  <!-- 8. Reference & Master Data -->
  <a xlink:href="./08-reference-master-data/" target="_blank">
    <g transform="rotate(229.089 110 110)">
      <path d="M110,110 L110,14 A96,96 0 0,1 163.4,28.3 Z" fill="url(#steel)"/>
      <path d="M110,110 L110,14 A96,96 0 0,1 163.4,28.3 Z" fill="#6fe9fb" fill-opacity="0.35"/>
      <title>8. Reference & Master Data</title>
    </g>
  </a>

  <!-- 9. Data Warehousing & BI -->
  <a xlink:href="./09-data-warehousing-bi/" target="_blank">
    <g transform="rotate(261.816 110 110)">
      <path d="M110,110 L110,14 A96,96 0 0,1 163.4,28.3 Z" fill="url(#steel)"/>
      <path d="M110,110 L110,14 A96,96 0 0,1 163.4,28.3 Z" fill="#fbbf24" fill-opacity="0.45"/>
      <title>9. Data Warehousing & BI</title>
    </g>
  </a>

  <!-- 10. Metadata Management -->
  <a xlink:href="./10-metadata-management/" target="_blank">
    <g transform="rotate(294.543 110 110)">
      <path d="M110,110 L110,14 A96,96 0 0,1 163.4,28.3 Z" fill="url(#steel)"/>
      <path d="M110,110 L110,14 A96,96 0 0,1 163.4,28.3 Z" fill="#b6f04a" fill-opacity="0.35"/>
      <title>10. Metadata Management</title>
    </g>
  </a>

  <!-- 11. Data Quality -->
  <a xlink:href="./11-data-quality/" target="_blank">
    <g transform="rotate(327.27 110 110)">
      <path d="M110,110 L110,14 A96,96 0 0,1 163.4,28.3 Z" fill="url(#steel)"/>
      <path d="M110,110 L110,14 A96,96 0 0,1 163.4,28.3 Z" fill="#7fb3ff" fill-opacity="0.40"/>
      <title>11. Data Quality</title>
    </g>
  </a>

  <!-- ===== Inner hub ===== -->
  <circle cx="110" cy="110" r="40" fill="url(#hub)" stroke="#2a3240" stroke-width="1.2"/>
  <text x="110" y="108" class="lbl">DATA GOVERNANCE</text>
  <text x="110" y="114" class="tick">framework hub</text>
</svg>
</p>









<p align="center">
  <a href="#01">1. Data Governance</a> ·
  <a href="#02">2. Data Architecture</a> ·
  <a href="#03">3. Data Modeling & Design</a> ·
  <a href="#04">4. Data Storage & Operations</a> ·
  <a href="#05">5. Data Security</a> ·
  <a href="#06">6. Data Integration & Interoperability</a> ·
  <a href="#07">7. Document & Content Management</a> ·
  <a href="#08">8. Reference & Master Data</a> ·
  <a href="#09">9. Data Warehousing & BI</a> ·
  <a href="#10">10. Metadata Management</a> ·
  <a href="#11">11. Data Quality</a>
</p>

---
---

## Index par “pétale” (liens vers vos dossiers)

### <a id="01"></a>1. Data Governance
- Dossier : `./01-data-governance/`
- Idées UC : RACI, politique de nommage, glossaire métier

### <a id="02"></a>2. Data Architecture
- Dossier : `./02-data-architecture/`
- Idées UC : principes d’architecture, zones de données, schémas logiques

### <a id="03"></a>3. Data Modeling & Design
- Dossier : `./03-data-modeling-design/`
- Idées UC : modèles conceptuels/ERD, normalisation, conventions

### <a id="04"></a>4. Data Storage & Operations
- Dossier : `./04-data-storage-operations/`
- Idées UC : sauvegardes, archivage, policies de rétention

### <a id="05"></a>5. Data Security
- Dossier : `./05-data-security/`
- Idées UC : RBAC de base, classification des données, principes RGPD

### <a id="06"></a>6. Data Integration & Interoperability
- Dossier : `./06-data-integration-interoperability/`
- Idées UC : déduplication multi-sources, mapping, petits pipelines

### <a id="07"></a>7. Document & Content Management
- Dossier : `./07-document-content-management/`
- Idées UC : arborescence documentaire, versionning, gabarits

### <a id="08"></a>8. Reference & Master Data
- Dossier : `./08-reference-master-data/`
- Idées UC : golden record simple, dictionnaire de valeurs

### <a id="09"></a>9. Data Warehousing & BI
- Dossier : `./09-data-warehousing-bi/`
- Idées UC : mini-star schema, KPI de gouvernance, petit dashboard

### <a id="10"></a>10. Metadata Management
- Dossier : `./10-metadata-management/`
- Idées UC : mini data catalog, lineage visuel

### <a id="11"></a>11. Data Quality
- Dossier : `./11-data-quality/`
- Idées UC : complétude, unicité, règles de validation

---

> 💡 Astuce : ajoute un dossier `00-templates/` avec un **USECASE-template.md** pour cloner le même format partout.
