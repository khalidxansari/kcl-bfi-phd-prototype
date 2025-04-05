# KCL-BFI PhD Prototype

This repository presents a proof-of-concept prototype developed to support my application for the fully funded AHRC Collaborative Doctoral Partnership between **King’s College London** and the **British Film Institute (BFI)**.

The project explores how **cloud-based computer vision tools** can be used to extract, analyze, and visualize metadata from **UK television adverts**, aligning with the PhD project titled:

**“From narratives of value to valuable algorithms: a decade of promotional screen culture in the UK seen by machine.”**

---

## 🧠 Objectives

- Test the feasibility of using Google Vision API for large-scale advert frame analysis
- Extract meaningful visual metadata from real-world UK TV ads
- Visualize dominant themes and co-occurrence of concepts in screen culture

---
```
## 📁 Project Structure


kcl-bfi-phd-prototype/
├── Output/                      # Contains generated visualizations (bar chart, word cloud, heatmap)
│   ├── Frequent words label.png
│   ├── Wordcloud.png
│   └── label co-occurance matrix.png
├── tagging_frames_adverts.ipynb       # Main notebook: frame extraction & Google Vision integration
├── label_visuals.ipynb                # Notebook for top labels + word cloud
├── co_occurrence_matrix.ipynb         # Notebook for co-occurrence analysis
├── vision_labels.csv                  # Output CSV from Google Vision label detection
├── README.md
└── requirements.txt
```

