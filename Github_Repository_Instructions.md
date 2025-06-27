PFAS Public Consultation Analysis: Group
Deliverable Overview
Main Rep ository:
 github.com/DoMoreForWater
Dashb oard:
 Tableau Public
GitHub Rep ository Overview
Data Prepro cessing
‹
convert
docx
to
csv.ipynb
{ Extracts public comments from Word do cuments and converts them
into a structured CSV format.
‹
Dummy
Variables.ipynb
{ Generates dummy variables to reduce redundancy.
Cross-Sectoral Sentim ent Analysis:
Zina
deliverables
‹
Sentiment
Analysis
BART.ipynb
{ Use zero-shot classication (BART) for sentiment analysis.
‹
Sentiment
Analysis
Prompt.ipynb
{ Use prompt engineering for sentiment analysis.
‹
Sector
Classification
Prompt.ipynb
{ Classies the comments into NACE sectors and sub
sectors for cross-sectoral sentim ent analysis.
Stance and Exemption Prompting A nalysis:
Valeria
deliverables
‹
Full
stance
exemption
classification.ipynb
{ Apply few-shot prompting to the entire ECHA
dataset to p erform stance and exem ption classication.
‹
pfas
stance
exemption.xlsx
{ Final output le combining stance and exemption predictions.
‹
Translation
with
API.ipynb
{ Uses GPT-3.5 to de tect language and translate into English.
‹
Stance
detection
1.ipynb
{ Compares zero-, one-, and few-shot prompting techniques using
GPT-4o-mini on the development set.
‹
Dev
Stance
Evaluation.ipynb
{ Evaluates prompt p erformance on the development set.
‹
Test
stance
detection.ipynb
{ Applies and e valuates the ve b e st-p erforming prompt strategies
on a test set.
‹
Test
exemption
classification
evaluation.ipynb
{ Applies and evaluates keyword-based l-
tering and fe w-shot prompting for exemption classication on a test set.
Data Prepro cessing for Dashb oard
‹
Data
Cleaning
and
Exploration
for
Dashboard.ipynb
{ Preparing the comment data for inte-
gration with Tableau dashb oard. Also contains general data exploration.
‹
arguments
LONG.csv
{ Argument classication re sults turned into a long-le format for dashb oard
integration.
‹
comments
definitive.csv
{ Final version of the PFAS comment dataset us ed for the dashb oard
and for p erforming argument classication.
Lobbying Argument Classication:
Marko
deliverables
‹
GPT
4o
and
GPT
4o
mini
Lobbying
Argument
Classification.ipynb
{ Co de for classifying the
lobbying argument typ es (all mo dels that use either GPT-4o or GPT-4o-m ini).
‹
KMeans
clustering
for
few
shot
exemplars.ipynb
{ K-Means c lus tering to select representative
comment exemplars for few-shot mo de ling.
‹
RoBERTa
argument
classification.ipynb
{ Co de for classifying the lobbying argument typ es
with RoBERTa.
1
