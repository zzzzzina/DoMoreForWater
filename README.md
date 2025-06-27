# PFAS Public Consultation Analysis: Group Deliverable Overview

**Main Repository:** [github.com/DoMoreForWater](https://github.com/zzzzzina/DoMoreForWater)  
**Dashboard:** [Tableau Public](https://public.tableau.com/app/profile/marko.poldma/viz/Dashboard22may/Story1)

---

## GitHub Repository Overview

### Data Preprocessing

- `convert_docx_to_csv.ipynb` – Extracts public comments from Word documents and converts them into a structured CSV format.
- `Dummy_Variables.ipynb` – Generates dummy variables to reduce redundancy.

### Cross-Sectoral Sentiment Analysis: [`Zina_deliverables`](https://github.com/zzzzzina/DoMoreForWater/tree/main/zina_deliverable)

- `Sentiment_Analysis_BART.ipynb` – Use zero-shot classification (BART) for sentiment analysis.
- `Sentiment_Analysis_Prompt.ipynb` – Use prompt engineering for sentiment analysis.
- `Sector_Classification_Prompt.ipynb` – Classifies the comments into NACE sectors and sub sectors for cross-sectoral sentiment analysis.

### Stance and Exemption Prompting Analysis: [`Valeria_deliverables`](https://github.com/zzzzzina/DoMoreForWater/tree/main/Valeria_deliverables)

- `Full_stance_exemption_classification.ipynb` – Apply few-shot prompting to the entire ECHA dataset to perform stance and exemption classification.
- `pfas_stance_exemption.xlsx` – Final output file combining stance and exemption predictions.
- `Translation_with_API.ipynb` – Uses GPT-3.5 to detect language and translate into English.
- `Stance_detection_1.ipynb` – Compares zero-, one-, and few-shot prompting techniques using GPT-4o-mini on the development set.
- `Dev_Stance_Evaluation.ipynb` – Evaluates prompt performance on the development set.
- `Test_stance_detection.ipynb` – Applies and evaluates the five best-performing prompt strategies on a test set.
- `Test_exemption_classification_evaluation.ipynb` – Applies and evaluates keyword-based filtering and few-shot prompting for exemption classification on a test set.

### Data Preprocessing for Dashboard

- `Data_Cleaning_and_Exploration_for_Dashboard.ipynb` – Preparing the comment data for integration with Tableau dashboard. Also contains general data exploration.
- `arguments_LONG.csv` – Argument classification results turned into a long-file format for dashboard integration.
- `comments_definitive.csv` – Final version of the PFAS comment dataset used for the dashboard and for performing argument classification.

### Lobbying Argument Classification: [`Marko_deliverables`](https://github.com/zzzzzina/DoMoreForWater/tree/main/Marko_deliverables)

- `GPT_4o_and_GPT_4o_mini_Lobbying_Argument_Classification.ipynb` – Code for classifying the lobbying argument types (all models that use either GPT-4o or GPT-4o-mini).
- `KMeans_clustering_for_few_shot_exemplars.ipynb` – K-Means clustering to select representative comment exemplars for few-shot modeling.
- `RoBERTa_argument_classification.ipynb` – Code for classifying the lobbying argument types with RoBERTa.
