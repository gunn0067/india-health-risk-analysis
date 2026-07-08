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
![Fitness Paradox](Screenshot_2026-07-06_112341.png)

> An active smoker (13% diabetes rate) is healthier than an inactive non-smoker (18%).
> Exercise is powerful — but it cannot fully cancel out smoking.
> Data from 3,75,000 real CDC survey respondents.

---

### 2. Diabetes Risk by Age — The Turning Point Is Your 30s
![Diabetes by Age](Screenshot_2026-07-06_112527.png)

> Risk increases 15x from your 20s to your 60s.
> The turning point is your 30s — not your 60s.
> Start prevention in your 20s, not when symptoms appear.

---

### 3. Heart Disease by Age & Gender
![Heart Disease](Screenshot_2026-07-06_112553.png)

> 80% of men above 60 show signs of heart disease.
> Women's risk catches up sharply after 50 — post menopause effect.
> Gender is not protection — it is just a delay.

---

### 4. Malignant vs Benign Tumors — What Makes Cancer Dangerous?
![Cancer Tumors](Screenshot_2026-07-06_112616.png)

> Malignant tumors are 2x larger and 80% more compact than benign ones.
> Early detection is the only affordable cure.
> Size and compactness are the key clinical indicators.

---

### 5. BMI vs Diabetes — Weight Is Not Just About Looks
![BMI Diabetes](Screenshot_2026-07-06_112639.png)

> Obese individuals have 22x higher diabetes rate than underweight people.
> Even normal weight people have 3.8% diabetes rate — being thin is not the same as being healthy.
> HbA1c and blood glucose rise consistently with BMI.

---

### 6. The Triple Threat — Hypertension + Heart Disease + Diabetes
![Triple Threat](Screenshot_2026-07-06_112702.png)

> Having hypertension alone multiplies diabetes risk by 4.3x.
> Having both hypertension and heart disease increases risk by 6.4x.
> These three conditions feed each other — catch one early, prevent the other two.

---

### 7. BMI vs Smoking — Which Matters More for Diabetes?
![BMI vs Smoking](Screenshot_2026-07-06_112742.png)

> Normal BMI reduces diabetes risk to 3.8% — regardless of smoking history.
> Weight management is more impactful than quitting smoking for diabetes prevention.
> Fix your weight first.

---

### 8. Breast Cancer Survival — Why Early Detection Changes Everything
![Breast Cancer Survival](Screenshot_2026-07-06_112824.png)

> Stage 1 detection = 99% five-year survival rate.
> Stage 4 detection = only 28% five-year survival rate.
> Early detection is not just important — it is the difference between life and death.

---

### 9. Breast Cancer Risk Factors — What You Can and Cannot Control
![Breast Cancer Risk](Screenshot_2026-07-06_112915.png)

> BRCA1/BRCA2 mutations carry 5.5x higher risk — but affect only 5% of cases.
> Age (50+) is the biggest population-level risk factor — responsible for 30% of cases.
> Modifiable factors (obesity, alcohol, physical inactivity) cause 26% of all breast cancer cases.

---

### 10. PCOS — AMH Levels as a Key Diagnostic Marker
![PCOS AMH](Screenshot_2026-07-06_112935.png)

> PCOS positive women have nearly 2x higher AMH levels (7.84 vs 4.53 ng/mL).
> Normal AMH upper limit is 3.5 ng/mL — both groups exceed it in suspected hormonal cases.
> 32.7% of suspected cases tested PCOS positive. PCOS women face 3x higher diabetes risk if untreated.

---

### 11. Women's Health — India's Silent Epidemic
![Women's Health Complete](Screenshot_2026-07-06_113024.png)

> Breast cancer is India's most common cancer — 1,78,361 new cases annually.
> Cervical cancer ranks 3rd with 1,23,907 new cases — almost entirely preventable.
> Combined view of cancer burden, breast survival, and PCOS markers.

---

### 12. Cervical Cancer — Risk Factors & Age Analysis
![Cervical Cancer](Screenshot_2026-07-06_113046.png)

> Cervical cancer positive rate jumps to 25% after age 50.
> Hormonal contraceptive use peaks at 30–39 age group (65%).
> Regular Pap smear + HPV vaccine = almost complete prevention.

---

### 13. Men vs Women — Diabetes Risk Comparison
![Gender Comparison](Screenshot_2026-07-06_113104.png)

> Men have 28% higher diabetes rate than women despite almost identical BMI.
> Estrogen provides metabolic protection in women — but disappears after menopause.
> Blood glucose levels are consistently higher in men across all age groups.

---

## Final Conclusions

| Finding | Key Insight |
|---------|-------------|
| Fitness Paradox | Active smoker (13%) healthier than inactive non-smoker (18%) |
| Diabetes turning point | Risk doubles every decade — starts climbing at 30, not 60 |
| Heart disease | 80% of men above 60 affected — women catch up post-menopause |
| Triple threat | Hypertension + heart disease = 6.4x higher diabetes risk |
| BMI power | Normal BMI = 3.8% diabetes risk regardless of smoking |
| Breast cancer | Stage 1 = 99% survival vs Stage 4 = 28% survival |
| PCOS | 2x higher AMH, 3x higher diabetes risk if untreated |
| Gender gap | Men have 28% higher diabetes rate despite similar BMI |

> **Your genes load the gun. Your lifestyle pulls the trigger.**
>
> **Healthcare is expensive. Awareness is free.**
> **The best time to start was yesterday. The next best time is today.**

---

## How to Run

1. Open `India_Health_Risk_Analysis.ipynb` in Google Colab
2. Download all datasets from Kaggle links below
3. Upload to Google Drive in a folder: `Colab Notebooks/sql project/health risk analysis/`
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
