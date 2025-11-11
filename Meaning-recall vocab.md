# 🤖 Stewart et al. (2025)
**Can we reliably score meaning-recall vocabulary tests using AI?**  
*(Language Testing, in press)*

---

## 🧭 Introduction

Traditional vocabulary tests often rely on **meaning-recognition formats** (e.g., multiple-choice), which are efficient but can inflate scores through guessing.  

**Meaning-recall tests**, by contrast, tap into real productive vocabulary knowledge but are time-consuming and require trained human raters—especially for multilingual responses.  

With advances in **Large Language Models (LLMs)** such as *GPT-4* and *Gemini*, AI-based scoring may now achieve human-like semantic judgment and reliability.

---

## ❓ Research Questions

**RQ1.** Are LLM ratings stricter, more lenient, or statistically indistinguishable from human ratings?  
**RQ2.** Does scoring meaning-recall vocabulary tests with LLMs affect reliability compared to human scoring?  
**RQ3.** Are correlations between human and LLM ratings acceptable under inter-rater reliability standards?  
**RQ4.** When and why do LLM and human raters differ in their judgments?


## 📚 Background
* **Recognition tests:** efficient but they may fail to fully reflect a learner’s true ability.
* **Recall tests:** more valid but labor-intensive to score.  
* **LLMs:** show strong *contextual and semantic matching* (Aryadoust 2023; Roever 2024).  
- Empirical evidence comparing **human vs. AI reliability** is still limited.  
- This study examines whether AI scoring can achieve **fairness, validity, and consistency** comparable to human assessment.

---

## ⚙ Method (방법)
| 구분 | 내용 |
|------|------|
| **Participants** | 일본 EFL 학습자 611명 (18–22세, 영어 학습 6년 이상) |
| **Test Design** | Meaning recall vocabulary test (150 단어, BNC/COCA 1K–5K 수준). 참가자는 각 영어 단어의 일본어 의미 작성. |
| **Raters** | 👩‍🏫 Human 2 명 (영일 이중언어 채점자)  🤖 AI 3 종 (GPT-4o, Gemini 1.5, Llama 3-8B) |
| **Scoring Scheme** | Binary (1 = correct, 0 = incorrect). Prompt: “Does this Japanese response convey the correct meaning of the English word?” |
| **Analysis** | 기술통계 + Many-Facet Rasch Measurement (MFRM), Cronbach’s α, Pearson r, ICC (채점자간 신뢰도). |

---

## 📊 Results (결과)

### 🧩 RQ1. Rating strictness and comparability
| 주요 결과 | 요약 |
|------------|-------|
| **Mean score pattern** | Gemini (75.3) > Human1 (73.8) ≈ GPT (71.5) ≈ Human2 (70.2) > Llama (64.7) |
| **Interpretation** | GPT-4o와 Gemini는 인간 채점자와 통계적으로 유의한 차이가 없음. <br> → 두 모델 모두 **인간 수준의 평균 점수 및 채점 경향**을 보임. <br> Llama는 **가장 보수적인(엄격한)** 채점 경향을 나타냄. |


### 🧩 RQ2. Reliability (내적 일관성)
| 주요 결과 | 요약 |
|------------|-------|
| **Cronbach’s α** | GPT (.961), Gemini (.960), Human (.962), Llama (.941) |
| **Interpretation** | GPT와 Gemini의 신뢰도는 **인간 채점자와 동일 수준(.96)** 으로 안정적임. <br> Llama는 상대적으로 낮은 점수를 보여 **모델 크기(7B)의 한계**를 반영함. <br> → **AI 채점이 신뢰도 저하 없이 적용 가능**함을 시사. |


### 🧩 RQ3. Human–AI Correlation and Inter-rater Agreement
| 주요 결과 | 요약 |
|------------|-------|
| **Pearson r** | Human–AI 간 상관 r > .95 |
| **ICC (Interclass Correlation)** | > .90 → “Excellent agreement” 수준 |
| **Interpretation** | GPT와 Gemini의 점수는 **인간 간 상관(.925)** 을 능가하거나 유사한 수준으로, **채점 일치도가 매우 높음.** <br> → LLM 기반 채점이 **인간 채점자 간 변동 범위 내**에서 안정적으로 작동함. |


### 🧩 RQ4. Disagreement and Error Analysis
| 주요 결과 | 요약 |
|------------|-------|
| **Error patterns** | 주로 다의어·L1 전이 의미 (*develop, clinic, random, fabulous*) 등에서 불일치 발생 |
| **Interpretation** | GPT·Gemini의 오류는 **의미 확장/관용적 용법 해석 차이**로 인한 경미한 판단 차이로, 인간 간 채점 차이와 유사한 양상. <br> Llama는 **명백한 오판(예: 정답을 오답으로)** 사례 존재. <br> → 전반적으로 **AI의 오류는 해석상의 차이에 불과하며, 심각한 오판은 드묾.** |

---

## 🌈 Overall Interpretation

* **GPT-4o** and **Gemini 1.5** show **human-equivalent reliability, correlation, and scoring consistency** in meaning-recall vocabulary tests.  
* **Llama 3-8B** → parameters 적어 보수적 채점 경향.  
* **AI scoring patterns ≈ human judgment**, low-stakes 평가 에 활용 가능.  
* 차이는 주로 **polysemous words** 및 **L1 의미 전이** 상황에서 발생. 

✅ **Summary**
> LLMs (especially GPT-4o and Gemini 1.5) can **score meaning-recall vocabulary responses with human-level accuracy, reliability, and agreement**, marking a breakthrough in automated language assessment.

---

## 💬 Discussion Questions
1. Should LLMs replace human raters in classroom vocabulary assessment?  
2. How can teachers ensure fairness for learners with different L1 backgrounds?  

