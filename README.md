  
<h1 align="center"> Data Wheel • Mini Use Cases</h1>

<p align="center">
This repository showcases DMBOK use cases applied to public datasets(Chinook, Northwind, OpenFoodFacts, etc.). To demonstrate, in a concrete and traceable way, how I apply data governance & curation: policies, glossary, quality, security, architecture, and more.
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

<!-- ===================== SVG Data Wheel (11 segments cliquables) ===================== -->
<p align="center">
<svg viewBox="0 0 200 200" width="520" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
  <!-- Fond -->
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#0b1324"/>
      <stop offset="100%" stop-color="#0f1b2e"/>
    </linearGradient>
  </defs>
  <circle cx="100" cy="100" r="98" fill="url(#bg)"/>

  <!-- Modèle d’un secteur (≈32.727°) : du haut vers la droite, puis rotation autour (100,100) -->
  <!-- Chemin : centre -> bord haut -> arc -> retour centre -->
  <!-- Couleurs (palette douce) -->
  <a xlink:href="./01-data-governance/" target="_blank">
    <path d="M100,100 L100,10 A90,90 0 0,1 150.9,23.2 Z" fill="#5eead4"><title>1. Data Governance</title></path>
  </a>

  <a xlink:href="./02-data-architecture/" target="_blank">
    <g transform="rotate(32.727 100 100)"><path d="M100,100 L100,10 A90,90 0 0,1 150.9,23.2 Z" fill="#93c5fd"><title>2. Data Architecture</title></path></g>
  </a>

  <a xlink:href="./03-data-modeling-design/" target="_blank">
    <g transform="rotate(65.454 100 100)"><path d="M100,100 L100,10 A90,90 0 0,1 150.9,23.2 Z" fill="#fca5a5"><title>3. Data Modeling & Design</title></path></g>
  </a>

  <a xlink:href="./04-data-storage-operations/" target="_blank">
    <g transform="rotate(98.181 100 100)"><path d="M100,100 L100,10 A90,90 0 0,1 150.9,23.2 Z" fill="#fde68a"><title>4. Data Storage & Operations</title></path></g>
  </a>

  <a xlink:href="./05-data-security/" target="_blank">
    <g transform="rotate(130.908 100 100)"><path d="M100,100 L100,10 A90,90 0 0,1 150.9,23.2 Z" fill="#c4b5fd"><title>5. Data Security</title></path></g>
  </a>

  <a xlink:href="./06-data-integration-interoperability/" target="_blank">
    <g transform="rotate(163.635 100 100)"><path d="M100,100 L100,10 A90,90 0 0,1 150.9,23.2 Z" fill="#86efac"><title>6. Data Integration & Interoperability</title></path></g>
  </a>

  <a xlink:href="./07-document-content-management/" target="_blank">
    <g transform="rotate(196.362 100 100)"><path d="M100,100 L100,10 A90,90 0 0,1 150.9,23.2 Z" fill="#f9a8d4"><title>7. Document & Content Management</title></path></g>
  </a>

  <a xlink:href="./08-reference-master-data/" target="_blank">
    <g transform="rotate(229.089 100 100)"><path d="M100,100 L100,10 A90,90 0 0,1 150.9,23.2 Z" fill="#67e8f9"><title>8. Reference & Master Data</title></path></g>
  </a>

  <a xlink:href="./09-data-warehousing-bi/" target="_blank">
    <g transform="rotate(261.816 100 100)"><path d="M100,100 L100,10 A90,90 0 0,1 150.9,23.2 Z" fill="#fbbf24"><title>9. Data Warehousing & BI</title></path></g>
  </a>

  <a xlink:href="./10-metadata-management/" target="_blank">
    <g transform="rotate(294.543 100 100)"><path d="M100,100 L100,10 A90,90 0 0,1 150.9,23.2 Z" fill="#a3e635"><title>10. Metadata Management</title></path></g>
  </a>

  <a xlink:href="./11-data-quality/" target="_blank">
    <g transform="rotate(327.27 100 100)"><path d="M100,100 L100,10 A90,90 0 0,1 150.9,23.2 Z" fill="#60a5fa"><title>11. Data Quality</title></path></g>
  </a>

  <!-- Noyau -->
  <circle cx="100" cy="100" r="36" fill="#0f172a" stroke="#1f2937" stroke-width="1.2"/>
  <text x="100" y="104" text-anchor="middle" fill="#e5e7eb" font-size="9" font-weight="600">DATA WHEEL</text>
</svg>
</p>

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
