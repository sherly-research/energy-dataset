# energy-dataset
Dataset for aspect terms analysis related energy issue in Indonesia

# 📊 Energy Discourse Dataset from Indonesian Online Forums

This repository contains a collection of text data extracted from Indonesian online forums discussing energy-related topics. The dataset is designed for research purposes, particularly in **opinion mining** and **aspect-based sentiment analysis (ABSA)** related to public energy discourse.

---

## 📁 Files Description

### 🔹 `energi_kaskus.xlsx`
- **Description**: Contains public discussion texts about energy topics collected from the [Kaskus](https://www.kaskus.co.id) forum.
- **Content**: Raw user-generated comments and discussion threads about various energy issues.

### 🔹 `energi_reddit.xlsx`
- **Description**: Contains public discussion texts about energy topics collected from the [Reddit Indonesia](https://www.reddit.com/r/indonesia/) community.
- **Content**: User comments discussing energy-related issues such as renewable energy, fuel prices, and energy policy.

### 🔹 `energi_kaskus_reddit.xlsx`
- **Description**: Sentence-level segmentation results of the combined discussion texts from Kaskus and Reddit forums.
- **Content**: Each row represents a single sentence extracted and segmented from the original discussion content.

### 🔹 `data_aspectterms.xlsx`
- **Description**: Contains the results of aspect term extraction from energy discussion sentences.
- **Columns**:
  - `kalimat`: Original sentence text
  - `kalimat_processed`: Preprocessed version (lowercased, normalized, and stopwords removed)
  - `candidate_aspect_terms_rulebased`: Aspect term candidates extracted using a **rule-based approach**
  - `candidate_aspect_term_unsupervised`: Aspect term candidates extracted using an **unsupervised approach**
  - `selected_aspect_terms_hybrid`: Final aspect terms selected through a **hybrid refinement method**

---

## 📌 Dataset Purpose

This dataset can be used for:
- Research in aspect-based sentiment analysis (ABSA)
- Evaluation of aspect term extraction techniques (rule-based vs unsupervised vs hybrid)
- Analyzing public opinion on energy-related issues in Indonesia

---
## 📌 How to Cite

If you use this dataset in your research or publication, please cite it as follows:

### 🔹 APA Style

> Christina, S. (2025). *Energy Discourse Dataset from Indonesian Forums* (Version 1.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.15511140

### 🔹 BibTeX

```bibtex
@dataset{christina_2025_energy,
  author       = {Christina, Sherly},
  title        = {Energy Discourse Dataset from Indonesian Forums},
  year         = 2025,
  publisher    = {Zenodo},
  version      = {1.0},
  doi          = {10.5281/zenodo.15511140},
  url          = {https://doi.org/10.5281/zenodo.15511140}
}


---

## 📬 Contact

For questions, discussion, or collaboration, feel free to contact:  
📧 sherlychristina@it.upr.ac.id  
📍 GitHub Issues or via your GitHub profile
