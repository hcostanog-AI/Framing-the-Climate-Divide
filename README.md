
# 🌍 Framing the Climate Divide
**Discursive Power Dynamics in COP15 Climate Negotiations (2009)**  
*An NLP-based investigation of presidential and stakeholder speeches using BERTopic.*

*Abstract*

Investigation of the discursive power dynamics in the negotiations around global climate by analyzing presidential speeches and stakeholders speeches from the COP15 Copenhagen summit in 2009. Utilizing the advanced Natural Language Processing (NLP) technique of BERTopic, the study aims to identify and compare the thematic focuses and speeches framing of Global North and Global South leaders. The central hypothesis is that Global North actors primarily frame the climate concerns around technocratic solutions and market mechanisms, while their Global South counterparts emphasize historical responsibility and equity. This research aims to uncover the latent topics that reveal a fundamental divide in agenda-setting, thereby providing empirical evidence for the ideological schism that often plagues international climate diplomacy. The findings will contribute to our understanding of how language and AI-powered text analysis can illuminate power imbalances in global governance.


---

## 📖 Project Overview
This project investigates how **discursive power asymmetries** shaped the 2009 Copenhagen Climate Summit (COP15). By applying **Natural Language Processing (NLP)** to speeches from the Global North and Global South, the study reveals how agenda-setting power operates through language.

- **Global North** → framed solutions in **technocratic terms** (technology, finance, carbon markets).  
- **Global South** → emphasized **justice, equity, and historical responsibility**.  

Understanding this discursive divide is key to unpacking the **political economy of climate governance** and how language reinforces structural inequalities.

---

## 🛠️ Methodology

### Why BERTopic?
- Captures **contextual embeddings**, enabling nuanced detection of terms like *“historical responsibility”* vs *“climate debt”*.  
- Retains **small but significant topics** (e.g., *loss and damage*, *technology transfer*) often missed by LDA or traditional models.  
- Well-suited for **short, rhetorically dense speeches**.

### Pipeline
1. **Data Collection** → COP15 presidential and stakeholder speeches.  
2. **Preprocessing** → Cleaning, tokenization, stopword removal.  
3. **Topic Modeling with BERTopic** → Extract themes and clusters.  
4. **Comparative Analysis**:
   - Topic frequency distributions.  
   - Regional disaggregation (North vs. South).  
   - Cross-frame mapping (technocratic vs. justice frames).  

---

## 📊 Key Findings

- **Technocratic Emphasis (North):** ~45% of topics focused on mitigation technologies, agreements, and institutional mechanisms.  
- **Justice Orientation (South):** Equity, responsibility, and vulnerability consistently foregrounded but less represented overall.  
- **Discursive Divide:** Confirms a persistent imbalance where **technocratic discourse dominates negotiation agendas**, marginalizing justice-oriented claims.  

---

## 🔍 Comparative Insights

- **North →** Agenda-setting power reinforced through discourse of innovation, carbon markets, and managerial solutions.  
- **South →** Counter-discourse of climate justice, historical responsibility, and equity.  
- **Outcome →** Justice frames persist but remain structurally sidelined.  

---

## 📈 Outputs

- Topic frequency distributions across speeches.  
- Comparative visualizations of North vs. South framing.  
- Cross-frame mapping of **technocracy vs. justice** discourses.  

---

## 📚 Limitations & Future Work
- **Scope:** Analysis limited to COP15 (2009). Future research could extend across multiple COPs (2009–2025).  
- **Text Type:** Focus on high-level speeches; further work could compare with draft agreements or technical reports.  
- **Geopolitical Complexity:** North–South binary simplifies shifting alliances (e.g., BASIC, AOSIS).  

---

## 💡 Broader Impact
This project shows how **AI-driven methods** can expose the language of power in climate diplomacy.  
By systematically mapping discursive asymmetries, NLP offers a path toward more **inclusive and just climate governance**.

---

## 🧰 Tech Stack
- **Python**  
- **BERTopic**  
- **Transformers / Sentence Embeddings**  
- **scikit-learn, pandas, numpy**  
- **matplotlib, plotly**  

---

## The thesis paper is attached to this repository
