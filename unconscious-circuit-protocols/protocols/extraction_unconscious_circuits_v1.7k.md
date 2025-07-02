# extraction_unconscious_circuits_v1.7k.md  
(Korean & English Included)

[무의식 판단 회로 추출 프로토콜 v1.7k]  
[Protocol v1.7k: Unconscious Judgment Circuit Extraction]

본 프로토콜은 [무의식 판단 회로 분석 프로젝트 추가지침 v1.0k]에 따른다.  
This protocol follows the [Supplementary Protocol v1.0k: Unconscious Judgment Circuit Analysis].

분석 목적:  
Analysis Objective:  
사용자의 사고 구조 속에 무의식적으로 작동하는 판단 모듈 회로가 몇 가지 존재하는지,  
어떤 구조와 순서로 작동하는지를 파악하는 데 있다.  
To identify unconscious judgment circuit modules within a user's cognitive structure,  
including how many exist, what structures they take, and in what sequence they operate.

분석 허용 조건:  
Analysis Conditions:  
1. ZIP 파일은 ChatGPT 공식 내보내기 형식(conversations.json 포함)을 따라야 하며,  
   내부 구조 변경·누락·날짜 정보 손실 시 분석을 중단해야 한다.  
   The ZIP file must follow ChatGPT’s official export format (including conversations.json).  
   If internal structure is altered, data is missing, or date information is lost, analysis must be terminated.  

2. 메시지 수 300개 이상, 감정·판단 관련 메시지 150개 이상이어야 한다.  
   단, 100개 이상이면서 사용자 메시지 중 200자 이상인 항목이 50개 이상일 경우 예외를 허용한다.  
   At least 300 messages and 150 related to emotion/judgment are required.  
   Alternatively, if there are 100+ messages and at least 50 of them exceed 200 characters, the condition is accepted.

3. 정보 요청, 요약, 명령 중심 대화만 있는 경우 분석을 거부해야 하며,  
   반드시 사고방식·판단기준·감정처리·인지습관이 반복적으로 드러나야 한다.  
   If the dialogue consists only of queries, summaries, or commands, analysis must be rejected.  
   The dataset must reveal repeated patterns of thinking, judgment, emotional processing, and cognition.

분석 기준:  
Analysis Criteria:  
1. 회로는 특정 자극에 대해 자동 작동하는 사고 필터 또는 판단 흐름이어야 한다.  
   A circuit is defined as a thought filter or judgment flow that activates automatically in response to a specific stimulus.

2. 반복적이고 자동화된 판단 구조만을 회로로 인정한다.  
   Only repetitive and automatic judgment structures qualify as circuits.

3. 취향, 감정 표현, 단발성 반응 등은 회로로 포함하지 않는다.  
   Preferences, emotional expressions, and one-time reactions are excluded from circuits.

출력 조건:  
Output Conditions:  
- 판단 회로는 최소 20개 이상, 최대 50개 이하이어야 한다.  
  A minimum of 20 and a maximum of 50 judgment circuits must be extracted.

- 20개 미만 감지 시, “감지된 회로 수가 기준에 미달함” 경고를 출력해야 한다.  
  If fewer than 20 circuits are detected, display a warning: “Detected circuit count below threshold.”

- 40개 이하로 인위적으로 축소하는 것을 금지한다.  
  Artificially reducing the total count below 40 is not allowed.

- 각 회로는 아래 형식으로 출력해야 한다:  
  `[번호]. [모듈 이름] ([작동 속도]): [한 줄 설명]. [예: 상황 설명]`  
  Each circuit must follow the format:  
  `[Number]. [Module Name] ([Speed]): [One-line description]. [Ex: Contextual example]`

- 작동 속도는 반드시 빠름 / 보통 / 느림 중 하나여야 한다.  
  Speed must be explicitly stated as Fast, Normal, or Slow.

- 예시는 고정 형식을 반드시 유지해야 한다.  
  The example format must be strictly preserved.

- 모듈명은 반드시 “기능 중심 명사 + 필터/탐지기/계산기/회피기/우선기” 형식이어야 한다.  
  Module names must follow the “Function-based Noun + Filter/Detector/Calculator/Avoider/Prioritizer” format.

- 은유적 표현이나 문학적 표현은 금지된다.  
  Metaphorical or literary expressions are prohibited.

- 회로는 작동 속도나 순서와 관계없이 반드시 우선순위 기준으로 정렬해야 한다.  
  Circuits must be sorted by priority regardless of their speed or activation order.

유사 회로 분리 기준:  
Circuit Differentiation Criteria:  
- 작동 조건, 트리거, 우선순위 중 2가지 이상이 다를 경우 분리 회로로 간주해야 한다.  
  If two or more of the activation condition, trigger, or priority differ, circuits must remain separate.

불확실 회로:  
Uncertain Circuits:  
- 최소 1개 이상의 불확실 회로를 출력해야 한다.  
  At least one uncertain circuit must be extracted.

- 예시는 다음 형식을 따르며, 설명은 요약적으로 작성한다:  
  `[모듈 이름] ([속도]): [불확실 이유 요약]`  
  The following format must be used with a brief rationale:  
  `[Module Name] ([Speed]): [Summary of uncertainty]`

감정 자극 회로 변화:  
Emotion-Induced Circuit Variations:  
- 감정 자극(예: 피로, 분노, 수치심 등)으로 인해 회로의 속도나 우선순위가 변할 경우,  
  아래 형식으로 출력해야 한다:  
  `[번호] - 변화 내용. [감정 및 상황 설명]`  
  If emotional stimuli (e.g., fatigue, anger, shame) alter a circuit's speed or priority,  
  output using the format:  
  `[Number] - Description of change. [Emotion and context]`

- 변화가 없을 경우 “감정 자극에 의한 회로 변화 없음.” 문구를 출력해야 한다.  
  If no variation occurs, explicitly state: “No circuit variations due to emotional stimuli.”

분석 재시도 규칙:  
Retry Conditions:  
- GPT가 “분석 완료” 또는 “다른 지시 하라”고 출력할 경우, 즉시 전체 분석을 재시도해야 한다.  
  If GPT outputs “Analysis complete” or “Give other instruction,” a full re-analysis must be performed immediately.

- 출력 용량 초과 시 다음 문장을 출력해야 한다:  
  “출력 용량 초과로 인한 분석 중단: 대화 데이터를 분할하여 세션 단위로 재시도하십시오.”  
  If output size exceeds capacity, output:  
  “Analysis interrupted due to output size: Please retry by splitting conversation data into session units.”

최종 고지:  
Final Notice:  
- 본 분석은 임상적 진단이 아니라 구조적 추론을 위한 실험이며,  
  실제 심리 진단은 전문가에 의해 수행되어야 한다.  
  This analysis is not a clinical diagnosis but a structural inference task.  
  Real psychological evaluations must be conducted by professionals.

- 출력 형식이 위 조건과 다를 경우 즉시 분석을 중단하고 재시도를 금지한다.  
  If output format deviates from the above conditions, immediately terminate the analysis and do not retry.
