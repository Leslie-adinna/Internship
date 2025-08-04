PEDIATRIC PULMONOLOGY CHATBOT
📚 Sources Used for Data Gathering
Mayo Clinic

PubMed Central (PMC)

National Institutes of Health (NIH)

Peer-reviewed Pediatrics and Pulmonology Journals

Clinical guidelines and educational materials from pediatric pulmonology societies

Additional reputable medical platforms including Medscape and Cleveland Clinic

🧪 2. Methodology
Used medical search engines and databases (PubMed, PMC, Mayo Clinic).

Keywords:

asthma, bronchiolitis, cystic fibrosis, pneumonia, sleep apnea in children, wheezing in infants.

Selected:

Review articles, meta-analyses, clinical practice guidelines, and patient education content.

Cross-verified data across sources.

Extracted:

Definitions, symptoms, causes, risk factors, diagnosis, treatment, prevention, FAQs.

📅 4. Date Accessed
July 08, 2025 – July 14, 2025

📂 5. Description of Contents
Pediatric pulmonology conditions:

Symptoms, causes, DDX, treatment options, surgical procedures, rehab.

Includes doctor-patient conversation examples.

Latest management guidelines and clinical updates.

💾 6. File Format and Size
Microsoft Word .docx → 4.7MB

Later converted to .txt for model integration.

🧬 Disease List of Pediatric Pulmonology
🔸 Common & Chronic Respiratory Diseases
Asthma

Reactive Airway Disease (RAD)

Bronchitis

Bronchiolitis

Pneumonia

Cystic Fibrosis

Bronchopulmonary Dysplasia (BPD)

Chronic Respiratory Failure

Wheezing Disorders

Chronic Cough

🔸 Congenital & Structural Abnormalities
Congenital lung anomalies

Tracheomalacia, bronchomalacia, laryngomalacia

Chest wall deformities

Airway malacia and stenosis

🔸 Rare & Diffuse Lung Diseases
Children’s Interstitial Lung Disease (chILD)

Bronchiolitis Obliterans

Pulmonary Fibrosis

NEHI

Alveolar Hemorrhage Syndromes

🔸 Infectious Diseases
RSV

Pertussis (Whooping Cough)

Tuberculosis

Other bacterial/viral LRTIs

🔸 Neuromuscular & Functional Disorders
Muscular dystrophy

Spinal muscular atrophy

Sleep apnea (central/obstructive)

Apnea of prematurity

🔸 Airway & Aerodigestive Disorders
Pulmonary aspiration

Aerodigestive anomalies

🔸 Vascular & Hematologic Disorders
Pulmonary Hypertension

HHT

Pulmonary complications from SCD

🔸 Other Important Conditions
Primary Ciliary Dyskinesia (PCD)

Non-CF Bronchiectasis

Tracheostomy/ventilator dependence

Subglottic stenosis

ARDS

Esophageal atresia

Tracheoesophageal fistula

Congenital Diaphragmatic Hernia

Pectus excavatum/carinatum

Pulmonary contusion

Sudden Infant Death Syndrome (SIDS)

Total Anomalous Pulmonary Venous Return

Sarcoidosis

Aspirin-exacerbated respiratory disease

CPT and ICD-10 codes included in structured dataset.

⚙️ BUILDING THE MODEL
🎯 Step 1: Define the Objective
Provide reliable non-critical respiratory health advice to caregivers using NLP without replacing clinical diagnosis.

Why?
🕐 24/7 accessibility

👩‍⚕️ Reduce workload on clinicians

📈 Promote patient engagement

⚖️ Maintain safety with disclaimers

☁️ Scalable deployment

📦 Step 2: Data Loading & Exploration
Used: "Pediatric Pulmonology.txt"

Contains real queries, medical notes, and responses

Chosen for domain-specific relevance

Manually curated for quality and accuracy

📊 Step 3: Exploratory Data Analysis (EDA)
Evaluated dataset structure, categories, and quality

Assessed:

Missing values

Distribution of inquiry types

Word length, common terms

Optional visualizations (bar charts, word clouds)

🧹 Step 4: Data Cleaning
Lowercased all text

Removed punctuation, symbols, stopwords

Preserved domain-specific terms (e.g., “cystic fibrosis”)

Optional: stemming, lemmatization

Removed headers/irrelevant lines

🧠 Step 5: Model Building
Trained multiple models including:

BOW + Logistic Classifier

BioGPT (fine-tuned)

🚀 Step 6: Deployment Strategy
Enables real-time non-critical medical support

Improves caregiver education

Can be connected to:

SMS (via Twilio)

Chatbot (Gradio, Dialogflow)

🗂️ Chatbot Use Cases
📱 Query	🤖 Bot Response
“My child has wheezing”	Bot checks severity and gives advice
“How can I prevent asthma?”	Bot provides triggers and prevention tips
“Explain sleep apnea”	Bot gives simple child-focused explanation
“Fever and runny nose”	Bot checks danger signs, offers care advice

👩‍⚕️ Team Members
Jennifer Imogie

Leslie El

Abubakar Barakat Oyiza
