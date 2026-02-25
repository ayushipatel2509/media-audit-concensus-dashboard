
# Llama 3 Media Bias Audit & Trust-Verifier

This repository contains a graduate-level research project auditing the performance of **Llama 3 (8B)** and **Llama 3.2 (3B)** in detecting media bias within the MBIC (Media Bias Instruction Corpus) dataset.

##  Key Research Findings
* **Prompt Optimization:** By shifting from a neutral to a **Strict Persona**, model accuracy improved from **58% to 71%**.
* **The Subjectivity Gap:** Observed a **36.5% conflict rate** between model sizes, proving that AI consensus on bias is highly unstable.
* **Linguistic Triggers:** Identified specific emotive keywords (e.g., *slammed*, *radical*, *fuming*) that disproportionately trigger bias labels.

##  Project Structure
* \`/notebooks\`: Contains the full audit logic and linguistic analysis.
* \`/data/processed\`: Cleaned results from baseline and dual-model experiments.
* \`/static/images\`: Generated confusion matrices and reliability heatmaps.

##  Usage
1. Clone the repo: \`git clone https://github.com/ayushipatel2509/media-audit-concensus-dashboard.git\`
2. Install requirements: \`pip install -r requirements.txt\`
3. Run the dashboard (upcoming): \`streamlit run app.py\`
EOF
