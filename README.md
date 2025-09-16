## Introduction 
“Given the limited amount of class time that can be used exclusively for vocabulary in EFL classroom settings such as South Korea, it is necessary to use effective methods that can increase opportunities for English exposure and vocabulary learning at the same time.”

“Glosses are useful because they work as both aids for English comprehension and tools for vocabulary learning simultaneously when learners read a text (Hulstijn, Hollander, & Greidanus, 1996; Ko, 2005).”

“However, glosses used in previous studies were static in terms of presenting meanings and explanations for glossed words. In other words, learners passively received the given definition without any further assistance regarding identifying the meaning independently.”

“In order to compensate for this passive nature, glossing can be designed by drawing on Dynamic Assessment (DA), a framework that integrates assessment with instruction.”

“Meanwhile, different challenges have been reported when implementing DA in the classroom setting. As Davin (2013) stated, ‘This form of DA administration in dyads is time-consuming, limiting the number of participants with whom a mediator can work’ (p. 307).”

“In response to these issues, the present study introduced the concept of Chatbot-Assisted Dynamic Assessment (CA-DA) as a form of glossing in which a chatbot acted as a mediator regarding unfamiliar words when learners read a text.”

“During CA-DA, learners engaged in more open-ended dialogues with chatbots and gained opportunities to recognize and produce unfamiliar words by receiving automated mediation while not constrained to a multiple-choice format.”

----------
Research Questions:
1. “Is CA-DA effective for receptive and productive vocabulary learning in L2 learners?”
2. “How can CA-DA be used for diagnosing L2 learners’ vocabulary knowledge?”

--------
## Literature Review 

#### 1. Glossing for vocabulary learning
“A gloss is a brief definition or synonym, either in L1 or L2, which is provided with the text (Nation, 2013). Glosses can work as both aids for text comprehension and tools for vocabulary learning simultaneously (Hulstijn et al., 1996; Ko, 2005).”

“However, learners do not pay attention to text-only glossing and see the glosses simply as aids to comprehension rather than as sources for vocabulary learning (Bowles, 2004; Yanguas, 2009).”

#### 2. Dynamic assessment for vocabulary learning
“DA … is a move away from static assessments … it provides diagnostic information about learner abilities, and at the same time, promotes learner development as a mediated process of transition from other-regulation toward self-regulation (Lantolf & Thorne, 2006).”

“DA utilizes graduated mediation … beginning as implicit prompts and becoming increasingly explicit if required (Aljaafreh & Lantolf, 1994).”

 “DA has been used as an effective means for vocabulary learning … dynamic glossing utilizes graduated mediation to help learners identify meanings of unfamiliar words.”

“However … computerized DA often relied on multiple-choice formats, which is not desirable because it limits learners to only a few options.”

#### 3. Artificial intelligence for dynamic assessment
“With the assistance of an AI agent … scholars have attempted to take advantage of AI technology when implementing assessment (Ai, 2017; Heift, 2017).”

“AI agents hold potential … they provide individual, graduated, and automated mediation to which a learner is able to respond through open-ended interaction.”

“However, it may seem infeasible for teachers to use AI technology in the classroom because they would need programming knowledge …”

“To address this concern, AI chatbots … such as Google’s Dialogflow … can be used with ease by teachers … considered a ubiquitous technology free from time and space.”

“Despite these advantages, research employing AI chatbots for DA … does not exist. To fill this gap … the present study explores the effect of chatbots used for DA on vocabulary learning and demonstrates effective ways of using chatbots for vocabulary diagnosis.”

________________________________________

## Method
1. Participants
After screening 81 students, 53 learners were randomly assigned into three groups:
 - 1) CA-DA (n=18): chatbot-assisted dynamic assessment with graduated prompts → prompts were given step by step, from implicit hints (“Read again and guess”) to explicit support (definition in a new sentence).
 - 2) CA-NDA (n=18): chatbot-assisted non-dynamic assessment with only word definitions (simple glosses) → learners received static definitions immediately, without step-by-step scaffolding.
 - 3) Control (n=17): no chatbot use → learners read texts without any automated support.

2. Target Vocabulary & Materials
   - 10 words: blizzard, demon, jar, jewelry, kernel, moisture, pot, refrigerator, sand, torch
   - Source: The Popcorn Book (de Paola, 1978), simplified passages (~200–220 words)
   - Target words underlined for focus

3. Procedure
   - Pretest → two treatment sessions → Immediate Posttest → Delayed Posttest (2 weeks)
   - Treatment sessions:
        - Length: 25 min × 2 days
        - Task: read passages & infer meaning of underlined words
   - Group tasks:
        - CA-DA: dynamic chatbot scaffolding (graduated hints)
        - CA-NDA: chatbot provides only definitions
        - Control: reading only

4. Chatbot Design
   - Platform: Google Dialogflow (tablet-based)
   - Mode: text-based interaction (Korean & English)
   - Prompt hierarchy (CA-DA only):
      1.	“Read the sentence again and guess.”
      2.	Highlight context clues
      3.	Provide guiding question
      4.	Give new example sentence

5. Measures
   - Receptive test: write definition (L1 or L2) for target words
   - Productive test: write English word for pictures (with first letter + blanks)
   - Scoring:
      - Receptive & Productive: 1 point per item (max 10 each)
   - Reliability: interrater = 98%; Cronbach’s α ≥ 0.70
----	
## Results 
#### 🌳 Receptive Vocabulary Knowledge

1. Descriptive Statistics
   
   | Group   | Posttest M (SD) | Delayed M (SD) |
   |---------|-----------------|----------------|
   | CA-DA   | 7.94 (1.95)     | 7.17 (2.23)    |
   | CA-NDA  | 5.89 (1.78)     | 5.06 (1.43)    |
   | Control | 1.88 (1.11)     | 1.41 (1.00)    |

➡️ 평균 점수 차이: CA-DA > CA-NDA > Control

2. Inferential Statistics
   - “In the posttest and delayed posttest, the statistical results were F(2, 50) = 59.696, p < .05, η² = 0.70 and F(2, 50) = 54.425, p < .05, η² = 0.69, respectively.”

#### 🌳 Productive Vocabulary Knowledg

1. Descriptive Statistics
   
   | Group   | Posttest M (SD) | Delayed M (SD) |
   |---------|-----------------|----------------|
   | CA-DA   | 6.33 (2.30)     | 4.56 (1.79)    |
   | CA-NDA  | 4.28 (1.96)     | 3.17 (1.86)    |
   | Control | 2.06 (1.34)     | 1.41 (1.12)    |

➡️ 평균 점수 차이: CA-DA > CA-NDA > Control

2. Inferential Statistics
   - “Regarding productive vocabulary knowledge … F(2, 50) = 21.640, p < .05, η² = 0.46 … F(2, 50) = 16.277, p < .05, η² = 0.39.”
➡️ 두 검사 모두 CA-DA 집단이 가장 우수, 효과 크기도 큼.

3. Diagnostic Insights (CA-DA group only)
 3.1. Descriptive Statistics (Session별 점수)
  - Session 1 → Actual M=1.11 (SD=2.14), Mediated M=15.78 (SD=5.46)
  - Session 2 → Actual M=8.61 (SD=5.89), Mediated M=28.89 (SD=8.73)
➡️ 시간이 지날수록 Actual & Mediated 점수 모두 상승

3.2. 추론통계 
   - “Increases in the mean actual and mediated scores from session 1 to session 2 revealed that learners in the CA-DA group improved in terms of both independent and mediated performance.”
➡️ 학습자들이 점차 더 적은 힌트로 정답 도출 → 자기조절(self-regulation) 발달의 증거.

------------
최종 요약
•	기술통계: M, SD로 집단별 성취 수준 확인 → CA-DA > CA-NDA > Control
•	추론통계: ANOVA 결과, 모든 차이가 p < .05에서 유의미, 효과 크기 큼 (η² 0.39~0.70)
•	추가 진단: CA-DA 집단 학습자들의 Actual vs Mediated 점수 상승 → 학습 + 평가 동시 가능


## Discussion
1. CA-DA most effective → higher scores than CA-NDA & Control (both receptive & productive)
2. Retention confirmed → effects sustained in delayed posttests
3. Diagnostic value → prompt levels revealed learners’ ZPD & individual differences
4. Pedagogical implication → chatbot-assisted DA supports both learning & assessment
5. Limitations → small sample, limited to elementary learners & 10 words → need broader studies

