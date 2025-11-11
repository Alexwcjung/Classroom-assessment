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
→ Compare mean scores and rater severity between human and LLM scoring using Many-Facet Rasch Measurement (MFRM).

**RQ2.** Does scoring meaning-recall vocabulary tests with LLMs affect reliability compared to human scoring?  
→ Examine internal consistency (Cronbach’s α) and score variance to determine whether AI scoring yields comparable reliability.

**RQ3.** Are correlations between human and LLM ratings acceptable under inter-rater reliability standards?  
→ Evaluate Pearson and intraclass correlations to see if Human–AI agreement matches human–human benchmarks.

**RQ4.** When and why do LLM and human raters differ in their judgments?  
→ Identify items with significant Human–AI disagreement and analyze whether differences stem from categorical errors or natural rater leniency.


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
| 핵심 결과 | 요약 및 통계 |
|------------|--------------|
| **평균 점수 패턴** | Gemini (75.3) > Human1 (73.8) ≈ GPT (71.5) ≈ Human2 (70.2) > Llama (64.7). → GPT/Gemini ≈ 인간 수준. |
| **Reliability** | Cronbach’s α ≈ .96 (GPT & Gemini = Human-level). Llama 약간 낮음. |
| **Human–AI correlation** | r > .95, ICC > .90 → “Excellent agreement.” |
| **Strictness trend** | Llama 가 가장 보수적 (낮은 평균 점수 및 분산). |
| **Error patterns** | 다의어·L1-transfer 의미 (예: *develop, clinic, random*) 에서 AI 오판 사례 관찰. |

---

## 🌈 Interpretation (해석)
* **GPT-4o & Gemini 1.5** → human-like accuracy and consistency.  
* **Llama 3-8B** → parameters 적어 보수적 채점 경향.  
* **AI scoring patterns ≈ human judgment**, low-stakes 평가 에 활용 가능.  
* 차이는 주로 **polysemous words** 및 **L1 의미 전이** 상황에서 발생.  

---

## 💬 Discussion & Implications
* **Fairness 공정성:** 명확한 기준 prompt 설계 시 AI 도 공정성 유지 가능.  
* **Efficiency 효율성:** 600명 채점 → Human 약 5시간 vs GPT 10분 미만.  
* **Use cases:** 형성평가, 연습 or 대규모 저위험 시험에 적합.  
* **Future work:** (1) Human-AI hybrid 모델 보정  (2) 다언어 확장  (3) 반복채점 일관성 검증.  

---

## 🧩 Conclusion (결론)
✅ **GPT-4o and Gemini achieve human-level reliability and accuracy.**  
⚙️ **AI-based meaning-recall scoring** is feasible for large-scale or low-stakes testing.  
🚧 High-stakes contexts require hybrid systems and continued validation.  

---

## 💬 Discussion Questions
1. Should LLMs replace human raters in classroom vocabulary assessment?  
2. How can teachers ensure fairness for learners with different L1 backgrounds?  
3. How might AI feedback promote *construct-relevant learning* rather than *test-wiseness*?  
