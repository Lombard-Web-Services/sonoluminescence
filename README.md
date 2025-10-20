# Signature Thermodynamique de la Lumière en Sonoluminescence

Ce projet explore un **cadre théorique original** reliant la **sonoluminescence** — l’émission de lumière lors de l’effondrement d’une bulle de gaz sous ultrasons — à des outils mathématiques avancés :  
- **Transport Optimal (OT)**,  
- **Information de Fisher**,  
- **Optimisation numérique (L-BFGS, Newton)**,  
- **Thermodynamique hors équilibre**.

Le document propose une **signature thermodynamique** de la lumière : la température du plasma émetteur est liée à la pénalité Fisher imposée pour régulariser le collapse, évitant ainsi les singularités non physiques.

---

## ⚙️ Génération automatique

Ce script :
- Écrit un fichier `.tex` complet à partir d’une chaîne intégrée,
- Compile avec `latexmk` (ou `pdflatex` en fallback),
- Produit `output/sonoluminescence.pdf`.

### Prérequis

- **Python 3.7+**
- `latexmk` **ou** `pdflatex` (via TeX Live, MiKTeX, etc.)
- **Packages LaTeX** : `amsmath`, `siunitx`, `hyperref`, `tabularx`, `booktabs`, etc.

> 💡 Le script gère l’encodage UTF-8, les chemins, et les recompilations nécessaires (TOC, références).

---

## 📥 Télécharger le PDF

➡️ [**sonoluminescence.pdf**](https://raw.githubusercontent.com/Lombard-Web-Services/sonoluminescence/main/output/sonoluminescence.pdf)

---

## 🧪 Reproductibilité expérimentale

Le document inclut une **section détaillée (Section 4)** pour reproduire la sonoluminescence à la maison ou en laboratoire :

- **Fréquence** : 25–28 kHz  
- **Rayon initial** : ~10 µm  
- **Température du plasma** : 5000–20 000 K  
- **Durée du flash** : ~50 ps  
- **Matériel** : transducteurs piézo, eau dégazée, ampli 50–100 W

---

## 📚 Références clés

Voir liens annexes et remerciements dans le paper.

---

## 📜 License

Ce document est distribué sous **[MIT License](LICENSE)**.  
© 2025 Thibaut Lombard — Project Manager & Machine Learning Engineer @ Lombard-Web-Services

>  À usage **informationnel, ou pédagogique.**. 

---

## 📬 Contact

- **Auteur** : Thibaut Lombard  (contact@lombard-web-services.com)
- **Entreprise** : Lombard-Web-Services  
- **Objectif** : Ouvrir des pistes de recherche interdisciplinaires (physique + information + optimisation).
