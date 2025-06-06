# Hackaton_AGH

Welcome to the **Hackaton_AGH** project repository!  
This repository is designed for a group of 4 people collaborating on a project developed during a hackathon. It includes tools, templates, and datasets shared across the team.

---

## 📁 Project Structure

```
Hackaton_AGH/
│   .gitignore             # Specifies files and directories to be ignored by Git
│   README.md              # Project overview and documentation
│   requirements.txt       # Python dependencies for the project
│
├── .vscode/               # VS Code-specific settings (optional/editor configs)
│
├── projects/              # Contains individual project directories
│   ├── 00_test_project/   # Example or test project for development
│   │   ├── data/          # Project-specific data storage
│   │   │   ├── processed/ # Cleaned and processed datasets
│   │   │   └── raw/       # Original, unprocessed data
│   │   ├── notebooks/     # Jupyter notebooks for analysis or exploration
│   │   ├── reports/       # Generated reports, figures, or visualizations
│   │   └── src/           # Source code specific to this project
│   │
│   └── 01_Spring25/       # Another example test project (Spring 2025)
│       ...                # Follows the same folder layout as above
│
└── shared/                # Shared resources across all projects
    ├── data/              # Shared datasets
    ├── models/            # Trained models for reuse
    ├── notes/             # Documentation, meeting notes, or planning docs
    ├── templates/         # Report, code, or notebook templates
    └── utils/             # Shared utility scripts and helper functions
```

---

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/united1flipper/Hackaton_AGH.git
cd Hackaton_AGH
```

### 2. Create a Virtual Environment

```bash
py -3.11 -m venv aghHack
# On Windows
aghHack\Scripts\activate
# On macOS/Linux
source aghHack/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 📌 Guidelines

- Each sub-project should be placed in the `projects/` directory using the format `XX_ProjectName/`.
- Shared tools, scripts, and data belong in the `shared/` directory.
- Use consistent naming conventions and organize files clearly.
- Document your code, notebooks, and project-specific logic.

---

## 📄 License

*(Optional – Add license info here if applicable)*

---

## 👥 Contributors

- [H. A.]
- [K. P.]
- [M. D.]
- [T. T.]