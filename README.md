# Healthcare-Patient-Clustering-Risk-Stratification

This project applies unsupervised machine learning techniques to the MIMIC-III Clinical Database, containing 58K+ patient records across demographics, lab tests, and vital signs. The goal is to cluster patients into meaningful subgroups to support risk stratification, early diagnosis, and evidence-based clinical decision-making.
📊 Dataset
Source: MIMIC-III Clinical Database
Size: 58,833 patient records → 30,600 clean records after preprocessing
Features: Demographics (age, gender, ethnicity), lab tests (glucose, creatinine, WBC, BUN, hematocrit, potassium), and vital signs (blood pressure, temperature, respiratory rate).
⚙️ Methodology
Data Preprocessing: Missing value imputation, normalization (StandardScaler & Min-Max Scaling), feature selection.
Exploratory Data Analysis (EDA): Histograms, KDE plots, scatterplots for demographic and lab value distributions.
Clustering:
K-Means with Elbow Method & Silhouette Score for optimal k.
Hierarchical Clustering with Ward’s linkage & dendrograms for subgroup insights.
Validation: PCA visualization of clusters.
📈 Results & Insights
Optimal grouping suggested 2–4 clusters, with 4 clusters selected for clinical interpretability.
Clusters revealed patient risk groups including:
High glucose & abnormal WBC counts → Diabetes & immune risks
Older patients with high BP & creatinine → Kidney & cardiovascular risks
Moderate lab values → General population
Stable lab values → Healthy/well-managed patients
Provided actionable insights for healthcare providers in screening, monitoring, and resource allocation.
🛠️ Skills & Tools
Languages/Libraries: Python (pandas, NumPy, scikit-learn, matplotlib, seaborn)
Techniques: K-Means, Hierarchical Clustering, PCA, Elbow Method, Silhouette Score, EDA
Domain: Healthcare Analytics, Risk Stratification, Clinical Decision Support
