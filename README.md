# 🇲🇬 OpenMada — Répertoire des projets de Madagascar

> Répertoire collaboratif des projets contribuant à la digitalisation de Madagascar.

Ce dépôt contient un fichier JSON structuré listant les projets malgaches. Il est conçu pour être **édité collaborativement** par la communauté via des Pull Requests.

🌐 **Voir la carte interactive** : [openmada.bluetech.mg](https://openmada.bluetech.mg)

---

## 📂 Structure

```
├── projects.json    # Liste des projets et catégories
└── README.md
```

## 🗂️ Catégories

| Emoji | Catégorie | Description |
|:---:|---|---|
| 🗺️ | **Cartographie** | Cartographie, géolocalisation et données géographiques |
| 🚌 | **Transport** | Mobilité urbaine et itinéraires |
| 👥 | **Démographie** | Données démographiques et communautés de développeurs |
| 👥 | **Finance & Comptabilité** | Projets liés à la finance et comptabilité malgache  |
| 🏛️ | **Gouvernance Digitale** | Modernisation des services publics numériques |
| 🆔 | **Identité Digitale** | Identité numérique et identification des citoyens |
| 🔤 | **Langue & Culture** | Langue malgache, NLP, dictionnaires et culture |
| 🎭 | **Fun & Communauté** | Outils ludiques et créations de développeurs malgaches |

## 🚀 Contribuer

Tu connais un projet open source malgache qui manque à la liste ? Ajoute-le !

### 1. Fork ce repo

### 2. Ajoute ton projet dans `projects.json`

Ajoute un nouvel objet dans le tableau `projects` :

```json
{
  "id": "mon-projet",
  "name": "Mon Projet",
  "category": "cartography",
  "description": "Une courte description du projet (max 100 caractères).",
  "github": "https://github.com/user/mon-projet",
  "website": null,
  "author": "ton-username"
}
```

### 3. Crée une Pull Request

C'est tout ! 🎉

### Règles

- **`id`** : Identifiant unique en kebab-case (ex: `mon-super-projet`)
- **`name`** : Nom du projet tel qu'affiché
- **`category`** : Un des IDs de catégorie existants (`cartography`, `transport`, `demography`, `governance`, `identity`, `language`, `community`)
- **`description`** : Description concise en français (1-2 phrases max)
- **`github`** : URL du dépôt GitHub, ou `null` si le projet n'a pas de repo public
- **`website`** : URL du site web, ou `null` si le projet n'a pas de site
- **`author`** : Nom d'utilisateur GitHub ou nom de l'organisation

> **Note** : Au moins un des champs `github` ou `website` doit être renseigné.

### Proposer une nouvelle catégorie

Si ton projet ne rentre dans aucune catégorie existante, tu peux proposer une nouvelle catégorie en ajoutant un objet dans le tableau `categories` :

```json
{
  "id": "ma-categorie",
  "name": "Ma Catégorie",
  "emoji": "🔧",
  "description": "Description de la catégorie."
}
```

## 📊 Projets actuels

<!-- Ce tableau est généré à partir de projects.json -->

| Projet | Catégorie | Auteur | Lien |
|---|---|---|---|
| Madagascar Map | 🗺️ Cartographie | julkwel | [GitHub](https://github.com/julkwel/madagascar-map) |
| Mada CLI | 🗺️ Cartographie | tsirysndr | [GitHub](https://github.com/tsirysndr/mada) |
| Interactive Map | 🗺️ Cartographie | nralibera | [GitHub](https://github.com/nralibera/madagascar_is_not_only_a_movie) |
| Deforestation Maps | 🗺️ Cartographie | ghislainv | [GitHub](https://github.com/ghislainv/deforestation-maps-Mada) |
| BetaX Community | 🚌 Transport | puchka | [GitHub](https://github.com/puchka/BetaX-Community) |
| Top MG GitHub Users | 👥 Démographie | tsirysndr | [GitHub](https://github.com/tsirysndr/top-mg-github-users) |
| Gasy Corpus Crawler | 🔤 Langue | SetraC4Ci | [GitHub](https://github.com/SetraC4Ci/Gasy-Corpus-Crawler) |
| MM CLI | 🔤 Langue | HarimbolaSantatra | [GitHub](https://github.com/HarimbolaSantatra/mm-cli) |
| Quotes Gasy | 🎭 Communauté | rasolofonirina | [GitHub](https://github.com/rasolofonirina/quotes-gasy) |
| Gasy Quotes Explorer | 🎭 Communauté | tokyRT | [GitHub](https://github.com/tokyRT/Gasy-quotes-explorer) |
| MES Emulator | 🎭 Communauté | luckasRanarison | [GitHub](https://github.com/luckasRanarison/mes) |
| Icelang | 🎭 Communauté | luckasRanarison | [GitHub](https://github.com/luckasRanarison/icelang) |

## 📜 Licence

Ce projet est sous licence [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) — domaine public. Vous pouvez copier, modifier et distribuer librement.

## 💙 Maintenu par

[BlueTech](https://bluetech.mg) — Breaking limits. Building Possibilities.
