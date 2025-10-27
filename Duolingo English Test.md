# Kang et al. (2024)  
**Fairness of Using Different English Accents: The Effect of Shared L1s in Listening Tasks of the Duolingo English Test**  
*Language Testing, Vol. 41(2), 263–289*

---

## 🧭 Introduction

- International English proficiency tests have long faced **validity and fairness issues** regarding the use of *nonstandard English accents*.  
- Tests such as TOEFL and IELTS often **privilege standard English**, disadvantaging *non-native speakers*.  
- With the rise of **Global Englishes (GEs)**, researchers now emphasize reflecting *diverse English accents* in listening assessment.  
- This study explored **Duolingo English Test (DET)** listening tasks — *yes/no vocabulary* and *dictation* — to examine:  
  1. The effect of accent variability on listening performance  
  2. The influence of **shared first language (L1)** between speaker and listener  
  3. The impact of **task type** on performance  

### 🎯 Research Questions
1. To what extent does listening to *shared vs. different English accents* affect test-takers’ DET listening performance?  
2. How do *different English accents* influence performance across the two DET task types (*yes/no vocabulary* and *dictation*)?  
:contentReference[oaicite:0]{index=0}

---

## 📚 Literature Review

### 1️⃣ Use of Different English Accents in Listening Assessment
- **Kachru’s (1985)** *World Englishes (WE)* model divides English varieties into:
  - **Inner circle (내부권):** Standard native English (U.S., U.K.)
  - **Outer circle (외부권):** Official but not everyday English (India, Philippines)
  - **Expanding circle (확장권):** Foreign language contexts (Korea, China)
- Calls for including *L1-accented English varieties* in testing (Harding, 2012) are tempered by concerns about **accent familiarity bias** and **fairness** (Taylor & Geranpayeh, 2011).  
- The **Shared-L1 Intelligibility Benefit** (Bent & Bradlow, 2003) posits that shared phonological systems lead to higher comprehension between speakers and listeners with the same L1.  
- Yet, effects may disappear for **highly intelligible or advanced speakers** (Kang et al., 2019; Munro et al., 2006).  
:contentReference[oaicite:1]{index=1}

### 2️⃣ Task Types and Listening Assessment
- The two DET tasks — *yes/no vocabulary* and *dictation* — are **phoneme-level perception tasks** relying on **speaker intelligibility**.  
- Input characteristics strongly influence performance (Buck, 1994; Field, 2013).  
- Shared-L1 advantages appear stronger in **word-recognition tasks** than in comprehension tasks (Dai & Roever, 2019).  
:contentReference[oaicite:2]{index=2}

---

## ⚙️ Method

| Section | Key Details |
|----------|--------------|
| **Participants** | **Speakers:** 24 total across six accents (American, British, Chinese, Indian, Korean, Mexican). Selected via expert ratings (≥ 4/5 accentedness & comprehensibility, ≥ 90% intelligibility). <br> **Listeners:** 160 total (40 each from Chinese, Korean, Hindi, and Mexican-Spanish L1 groups). Average age = 23.8, average English study = 6.5 years. |
| **Tasks** | - **Yes/No Vocabulary:** 18 items per set × 3 sets (word + nonword).  <br> - **Dictation:** 8 sentences per set × 3 sets.  <br> - **Elicited Imitation Test (EIT):** measured general proficiency (control variable). |
| **Procedure** | Three listening phases: <br> (1) *Inner-circle accent* (AmE/BrE) → (2) *Shared-L1 accent* → (3) *Non-shared L2 accent*. <br> Each phase used unique recordings; total time ≈ 45 min. |
| **Analysis** | Linear Mixed-Effects Models (LMM) in R. <br> Fixed effects: EIT score, listener L1, speaker accent, task type. <br> Dependent variable: DET accuracy score. |
:contentReference[oaicite:3]{index=3}

---

## 📊 Results

### 🌳 Shared vs. Different Accent Effects

| Predictor | β | p | Interpretation |
|------------|---|---|----------------|
| **Shared-L1 accent** | +0.016 | .044 | Significant improvement in shared-accent condition |
| **Inner-circle accent** | +0.019 | .416 | No significant difference vs. other accents |
| **Outer-circle (Indian)** | −0.041 | .035 | Performance decreased with Indian accent |
| **Task effect** | n.s. | .708 | No difference between task types |

- **Korean listeners** outperformed all other groups (β = .079, *p* < .001).  
- **Shared-L1 accents > other L2 accents**, but **Shared-L1 ≈ Inner-circle** when both were highly intelligible.  
:contentReference[oaicite:4]{index=4}

### 🌱 Task Type Effects
- No significant difference between **dictation** and **yes/no vocabulary** (*p* = .708).  
- Both tasks depend primarily on **speaker intelligibility**, not task format.  
:contentReference[oaicite:5]{index=5}

---

## 💬 Discussion

1. **Shared-L1 Benefit:**  
   Listeners performed better when hearing speakers who shared their L1, confirming Bent & Bradlow (2003)’s *Matched Interlanguage Intelligibility Benefit*.  

2. **Inner-circle vs. Shared-L1:**  
   Performances were equally high — possibly due to **familiarity** with standard accents through learning exposure.  

3. **Indian (Outer-circle) Accent:**  
   Despite high intelligibility, produced lower scores — suggesting accent familiarity still matters.  

4. **Task Type:**  
   No task-specific effects; both rely on similar **phonemic-level processing** and working memory.  

5. **Pedagogical & Testing Implications:**  
   - Including **highly intelligible non-native accents** can improve fairness and ecological validity.  
   - Potential for test-takers to **choose accent options** (e.g., Inner-circle or Shared-L1).  

6. **Limitations:**  
   - Only one *outer-circle* variety (Indian English).  
   - Speaker selection limited (24 out of 77 met intelligibility threshold).  
   - Korean group may have benefited from **task-type familiarity**.  
:contentReference[oaicite:6]{index=6}

---

## 🧩 Key Takeaways

> - **Shared-L1 accents** enhance listening performance.  
> - **Shared-L1 and Inner-circle accents** yield comparable scores when both are highly intelligible.  
> - **No task-type difference** across DET listening formats.  
> - Supports inclusion of **diverse, highly intelligible L2 accents** in high-stakes English tests to improve **fairness** and **validity**.

---
