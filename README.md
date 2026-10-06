# 🌿 Digital Herbarium — Botanical Investigation Archive

An interactive **Digital Herbarium** created as an academic botanical documentation project by **The Botanical Detectives** at **Prestige Institute of Engineering, Research and Management, Indore**.

The project transforms field-based plant photographs and observations into a searchable digital archive containing plant identification, botanical family, morphology, habitat, uses, collection information and identification-confidence levels.

## ✨ Project Highlights

- 🌱 **18 botanical records**
- 🔎 Searchable and filterable plant archive
- 🧬 Botanical family explorer
- 🕵️ Evidence-board style visualization
- 📍 Collection locations and GPS data where available
- 📊 Identification-confidence classification
- 🖼️ Photographic plant observations
- 📋 Individual plant record/detail views
- 📱 Responsive design for desktop and mobile
- ♿ Basic accessibility features such as keyboard focus, labels and reduced-motion support
- 🌐 Runs as a static website — no backend or database server is required

## 🎯 Objective

The main objective is to convert a conventional physical/case-file style herbarium into a **structured, interactive and accessible digital archive**.

The workflow used by the project is:

**Observation → Identification → Documentation → Digital Herbarium**

## 🧪 What Each Plant Record Can Contain

Each plant record may include:

- Record ID
- Common name
- Scientific name
- Botanical family
- Plant type
- Description / morphology
- Habitat
- Uses
- Collection location
- Latitude and longitude
- Collection date
- Identification confidence
- Photograph

Some fields are intentionally marked as unavailable when the original observation did not contain that information.

## 🔬 Identification Confidence

The archive uses confidence labels to communicate how strongly the photographic evidence supports an identification.

Records marked as **probable/provisional** should be verified using additional photographs or authoritative botanical references before being treated as final academic identifications.

## 👥 Project Team

**The Botanical Detectives**

| Member | Role |
|---|---|
| Taniya | Team Lead |
| Rishik | Architect Behind the Solution |
| Sarthak | Field Investigation |
| Sanket | Data & Systems |
| Shrim | Research & Botany |
| Shubh | Visualization & Presentation |

**Institution:** Prestige Institute of Engineering, Research and Management, Indore

**Submitted to:** Kirti Mam

## 🗂️ Suggested Repository Structure

```text
digital-herbarium/
│
├── index.html
├── README.md
├── PROJECT_DESCRIPTION.md
├── METHODOLOGY.md
├── DATA_DICTIONARY.md
├── CONTRIBUTING.md
├── .gitignore
├── LICENSE
└── assets/
    ├── plants/
    ├── screenshots/
    └── documents/
```

> The current prototype is self-contained, so the plant data and photographic assets are embedded inside the HTML. The structure above is recommended if the project is later separated into maintainable files.

## 🚀 How to Run

### Option 1 — Open locally

Simply open `index.html` in a modern browser.

### Option 2 — VS Code

1. Open the project folder in VS Code.
2. Open `index.html`.
3. Use a local server such as Live Server, or open the HTML directly.

### Option 3 — GitHub Pages

This project can be hosted using GitHub Pages because it is a static website.

1. Upload the project to a GitHub repository.
2. Go to **Settings → Pages**.
3. Select the repository branch containing `index.html`.
4. Save the Pages configuration.
5. GitHub will provide the public website URL.

## 🛠️ Technology

- HTML5
- CSS3
- Vanilla JavaScript
- SVG
- Embedded image/data assets
- Responsive web design

No framework or backend is required for the current prototype.

## 📚 Academic Value

This project demonstrates how botanical field observations can be converted into a digital information system. It combines:

**Botany + Field Documentation + Data Organization + Web Development + Visualization**

The website is intended as an academic/project demonstration and not as a substitute for expert botanical identification.

## ⚠️ Data & Identification Note

Plant identifications in this archive are based on the submitted photographic observations. When a record is labelled probable or provisional, further verification is recommended before final academic use.

## 📄 Project Documentation

See the supporting files in this repository:

- `PROJECT_DESCRIPTION.md` — short project overview
- `METHODOLOGY.md` — project workflow
- `DATA_DICTIONARY.md` — explanation of plant-record fields
- `CONTRIBUTING.md` — how to add or improve records

## 🌿 Future Scope

Possible future improvements include:

- Separate JSON plant database
- Individual plant image files instead of embedded Base64 images
- Interactive real-world map integration
- QR code for every plant record
- Plant-family and species statistics
- Admin panel for adding new observations
- Expert verification workflow
- Search by location
- Export plant records to PDF/CSV
- PWA/offline support
- Optional plant-identification AI assistance

---

**Digital Herbarium Project — 2026**

**The Botanical Detectives**  
Prestige Institute of Engineering, Research and Management, Indore
