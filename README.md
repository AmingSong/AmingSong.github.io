# MediLark

**MediLark** is a lightweight, research-oriented platform for discovering and curating public medical imaging datasets.

> _“Every day, a lark sings a new dataset.”_

---

## Mission

MediLark aims to help medical AI researchers quickly find, understand, and preprocess public imaging datasets (e.g., KiTS23, LUNA16, ACDC) through:

- Clean dataset summaries
- Direct access links
- Preprocessing tools
- Standardized metadata formats


## Key Features

- **Dataset Cards** — Curated, structured profiles for major public datasets
- **Preprocessing Toolkit** — Downloadable scripts for resampling, cropping, and label remapping
- **Searchable Navigator** — Easy-to-use interface for finding datasets by modality, task, or label
- **Community Ready** — Contributions encouraged via GitHub


## Project Structure

```plaintext
medilark/
├── public/             # Static assets (favicon, logo)
├── src/                # React + Tailwind frontend
│   ├── components/     # Reusable UI elements (cards, navbar, etc.)
│   ├── pages/          # Page views (Home, Dataset, Tools)
│   └── data/           # Dataset cards in JSON or YAML
├── scripts/            # Python scripts for preprocessing datasets
├── README.md
└── package.json
