---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education
* **B.S. in Computer Science**, UC Santa Cruz, Santa Cruz, CA 
  * Expected Graduation: June 2026 
  * GPA: 3.61/4.0 

---

## Work Experience
* **Undergraduate Researcher**, Neuromorphic Computing Group, UC Santa Cruz 
    * Developed **Future-Guided Learning (FGL)**, a novel time-series framework that achieved up to a 23% MSE reduction over baselines, leading to a publication in *Nature Communications*.
    * Led an international collaboration with computational neuroscientists at Aix Marseille University to formalize the mathematical link between FGL and predictive coding theory.
    * Created a new seizure prediction method that resulted in a 20% average per-patient increase in prediction AUCROC on the CHB-MIT EEG dataset, published as a TinyPaper at ICLR 2024.
    * Co-authored a perspective piece in *Nature Computational Science* on bridging the gap between artificial and natural intelligence.
* **Group Tutor**, CMPM 118-03: Collaborative Research Explorations In Engineering, UC Santa Cruz 
    * Spearheaded the design and creation of CMPM 118, a new course that created a structured pathway for over 150 students to gain hands-on experience in machine learning, neuromorphic computing research.
    * Designed a curriculum composed of lectures, slides, assignments, and a group-based final project to prepare new students for a rigorous research environment.
    * Mentored and supervised student research groups, with one group successfully co-authoring an accepted manuscript at the Baylearn conference and presenting their work at UCSC science fairs.

---

## Awards & Scholarships
* **Research Pathways Fellowship**, 2025 
* **Mantey Leadership Award**, 2025 
* **Koret Scholarship**, 2023-2025 

---

## Skills
* **Programming Languages**: Python, C, C++
* **ML/Data Science Libraries**: PyTorch, Scikit-learn, Pandas, NumPy 
* **Developer Tools**: Git 

---

## Publications
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

---

## Teaching
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>