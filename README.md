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
├── public/                  # Static assets (favicon, logo, etc.)
├── src/                     # React + Tailwind frontend
│   ├── components/          # Reusable UI elements (cards, navbar, footer)
│   ├── pages/               # Page-level views (Home, Dataset, Tools, About)
├── data/                    # All medical imaging dataset metadata
│   ├── kidney/              # Kidney-related datasets (e.g., KiTS19, KiTS23)
│   │   ├── kits19.json
│   │   └── kits23.json
│   ├── lung/                # Lung-related datasets (e.g., LUNA16)
│   │   └── luna16.json
│   ├── brain/               # Brain datasets (e.g., BraTS)
│   ├── prostate/            # Prostate datasets
│   ├── liver/               # Liver datasets
│   ├── breast/              # Breast datasets
│   └── index.json           # (Optional) master index of all datasets
├── scripts/                 # Python scripts for crawling and processing datasets
│   ├── fetch_kits.py
│   └── fetch_luna.py
├── .gitignore
├── README.md
└── package.json

