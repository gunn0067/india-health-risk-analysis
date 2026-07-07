# India's Ticking Time Bomb — Disease Risk & The Fitness Paradox

> Analyzing 5,17,000+ real patient records across diabetes, heart disease, cancer, PCOS and lifestyle factors using SQL and Python.

---

## The Question That Started This

*"I go to the gym. I'll be fine."*

India is facing a silent health crisis — diabetes, heart disease, and cancer are rising at alarming rates. Yet most people believe fitness alone protects them.

This project uses real clinical data to challenge that belief — and uncover what actually determines your health risk.

---

## Key Questions Answered

1. Does exercise cancel out smoking and alcohol?
2. At what age does disease risk actually begin?
3. How much does family history multiply your risk?
4. Which factors cause cancer — genetics or lifestyle?
5. What are the most underdiagnosed conditions in Indian women?
6. What free interventions actually work — backed by research?

---

## Datasets Used

| Dataset | Records | Source |
|---------|---------|--------|
| Diabetes Prediction Dataset | 1,00,000 | Kaggle |
| UCI Heart Disease Dataset | 920 | Kaggle |
| Wisconsin Breast Cancer Dataset | 569 | Kaggle |
| CDC Behavioral Risk Factor Dataset | 4,41,456 | Kaggle |
| Breast Cancer Risk Factors & Survival | 32 | Kaggle |
| Cervical Cancer Risk Factors | 858 | Kaggle |
| PCOS Dataset | 541 | Kaggle |

**Total: 5,17,000+ real patient records across 7 datasets**

---

## Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| SQLite + SQL | Data querying and analysis |
| Pandas | Data cleaning and manipulation |
| Matplotlib | Data visualization |
| Seaborn | Plot styling |
| Google Colab | Development environment |

---

## Key Findings & Visualizations

### 1. The Fitness Paradox — Does Exercise Cancel Out Smoking?
![Fitness Paradox](Screenshot%202026-07-06%20112341.png)

> An active smoker (13% diabetes rate) is healthier than an inactive non-smoker (18%).
> Exercise is powerful — but it cannot fully cancel out smoking.
> Data from 3,75,000 real CDC survey respondents.

---

### 2. Diabetes Risk by Age — The Turning Point Is Your 30s
![Diabetes by Age](Screenshot%202026-07-06%20112527.png)

> Risk increases 15x from your 20s to 60s.
> The turning point is your 30s — not your 60s.
> Start prevention in your 20s, not when symptoms appear.

---

### 3. Heart Disease by Age & Gender
![Heart Disease](Screenshot%202026-07-06%20112553.png)

> 80% of men above 60 show signs of heart disease.
> Women's risk catches up sharply after 50 — post menopause effect.
> Gender is not protection — it is just a delay.

---

### 4. Malignant vs Benign Tumors — What Makes Cancer Dangerous?
![Cancer Tumors](Screenshot%202026-07-06%20112616.png)

> Malignant tumors are 2x larger and 80% more compact than benign ones.
> Early detection is the only affordable cure.

---

### 5. The Triple Threat — Hypertension + Heart Disease + Diabetes
![Triple Threat](Screenshot%202026-07-06%20112639.png)

> Having hypertension alone multiplies diabetes risk by 4.3x.
> Having both hypertension and heart disease increases risk by 6.4x.
> These three conditions feed each other — catch one early, prevent the other two.

---

### 6. BMI vs Smoking — Which Matters More?
![BMI vs Smoking](Screenshot%202026-07-06%20112702.png)

> Normal BMI reduces diabetes risk to 3.8% — regardless of smoking history.
> Weight management is more impactful than quitting smoking for diabetes prevention.

---

### 7. Breast Cancer Risk Factors — What You Can and Cannot Control
![Breast Cancer Risk](Screenshot%202026-07-06%20112742.png)

> Modifiable lifestyle factors (obesity, alcohol, physical inactivity) cause 26% of breast cancer cases.
> You cannot change your genes — but you can change your habits.

---

### 8. PCOS — AMH Levels in Diagnosed vs Non-Diagnosed Women
![PCOS AMH](Screenshot%202026-07-06%20112824.png)

> PCOS positive women have nearly 2x higher AMH levels (7.84 vs 4.53 ng/mL).
> 32.7% of suspected hormonal cases tested PCOS positive.
> PCOS women have 3x higher diabetes risk if untreated.

---

### 9. Women's Health — India's Silent Epidemic
![Women's Health](Screenshot%202026-07-06%20112915.png)

> Breast cancer is India's most common cancer — 1,78,361 new cases.
> Cervical cancer risk peaks at 50+ with 25% positive rate — almost entirely preventable.
> Early detection at Stage 1 = 99% survival. Stage 4 = only 28%.

---

### 10. Cervical Cancer — Risk Factors & Age Analysis
![Cervical Cancer](Screenshot%202026-07-06%20112935.png)

> Hormonal contraceptive use peaks at 30–39 age group (65%).
> Cervical cancer positive rate jumps to 25% after 50.
> Regular Pap smear + HPV vaccine = almost complete prevention.

---

### 11. Men vs Women — Diabetes Risk Comparison
![Gender Comparison](Screenshot%202026-07-06%20113024.png)

> Men have 28% higher diabetes rate than women despite similar BMI.
> Estrogen provides metabolic protection — but disappears after menopause.

---

## Final Conclusions

| Finding | Key Insight |
|---------|-------------|
| Exercise vs Smoking | Active smoker (13%) healthier than inactive non-smoker (18%) |
| Diabetes turning point | Risk doubles every decade — starts at 30, not 60 |
| Heart disease | 80% of men above 60 affected |
| Hypertension impact | Multiplies diabetes risk by 6.4x combined |
| BMI power | Normal BMI = 3.8% diabetes risk regardless of smoking |
| Breast cancer | Stage 1 = 99% survival, Stage 4 = 28% survival |
| PCOS | 2x higher AMH, 3x higher diabetes risk if untreated |

> **Your genes load the gun. Your lifestyle pulls the trigger.**
> **Healthcare is expensive. Awareness is free.**

---

## How to Run

1. Open `India_Health_Risk_Analysis.ipynb` in Google Colab
2. Download datasets from Kaggle links below
3. Upload to Google Drive in a folder named `health risk analysis`
4. Run all cells in order

---

## Dataset Sources

- [Diabetes Prediction Dataset](https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset)
- [UCI Heart Disease Dataset](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data)
- [Wisconsin Breast Cancer Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- [CDC Behavioral Risk Factor Dataset](https://www.kaggle.com/datasets/cdc/behavioral-risk-factor-surveillance-system)
- [Breast Cancer Risk & Survival](https://www.kaggle.com/datasets/ankushpanday2/breast-cancer-risk-and-survival-dataset)
- [Cervical Cancer Risk Factors](https://www.kaggle.com/datasets/loveall/cervical-cancer-risk-classification)
- [PCOS Dataset](https://www.kaggle.com/datasets/prasoonkottarathil/polycystic-ovary-syndrome-pcos)

---

*Made with real clinical data | CSE Student Project | Python + SQL + Matplotlib*
