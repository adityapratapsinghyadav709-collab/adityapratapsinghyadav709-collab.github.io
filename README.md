# Aditya Yadav | Personal Website & Research Portfolio

Official personal website and research portfolio repository for **Aditya Yadav** (Regeneron ISEF 2026 Finalist, 2025 World Science Scholar, Summer Science Program Astrophysicist, and 2026 Diana Award Recipient).

## Repository Structure

```text
aditya-yadav-portfolio/
├── index.html                                                  # Main responsive portfolio entry point
├── assets/
│   ├── css/
│   │   └── styles.css                                          # Custom glassmorphism & observatory theme styles
│   ├── js/
│   │   └── app.js                                              # Interactive research simulators, filters & modals
│   └── img/
│       ├── aditya-yadav.png                                    # Cropped portrait of Aditya Yadav
│       └── hero-observatory.jpg                                # Custom quantum waveguide & observatory hero artwork
├── papers/
│   ├── Adaptive_TRSB_Quantum_Photonics_Aditya_Yadav.pdf        # Regeneron ISEF 2026 & IRIS Gold manuscript
│   ├── Deterministic_Wave_Scarring_Energy_Harvesting_Aditya_Yadav.pdf # Elastodynamic wave scarring manuscript
│   └── World_Science_Scholars_EOY_Aditya_Yadav.pdf             # World Science Scholars highlight sheet
├── data/
│   └── portfolio-data.json                                     # Structured JSON metadata for easy maintenance
├── .nojekyll                                                   # Disables Jekyll processing on GitHub Pages
├── .gitignore
├── LICENSE                                                     # MIT License
└── README.md
```

## Quick Deployment to GitHub Pages

1. **Create a new repository on GitHub**:
   - Name it `<your-github-username>.github.io` (for a root personal domain) or any repository name such as `portfolio`.
2. **Upload the files**:
   - Unzip `aditya-yadav-github-portfolio.zip`.
   - Upload the contents of the folder (`index.html`, `assets/`, `papers/`, `data/`, `.nojekyll`, `LICENSE`, `README.md`) directly to the root of your GitHub repository via **Add file -> Upload files** or via Git CLI:
     ```bash
     git init
     git add .
     git commit -m "Initial commit: Aditya Yadav personal research portfolio"
     git branch -M main
     git remote add origin https://github.com/<your-username>/<your-repo>.git
     git push -u origin main
     ```
3. **Enable GitHub Pages**:
   - Go to **Settings -> Pages** in your GitHub repository.
   - Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/ (root)`, and click **Save**.
   - Your personal website will go live within 60 seconds.
