# extraction_unconscious_circuits_v1.7k.md  
(Korean & English Included)

[무의식 판단 회로 추출 프로토콜 v1.7k]  
[Protocol v1.7k: Unconscious Judgment Circuit Extraction]

본 프로토콜은 [무의식 판단 회로 분석 프로젝트 추가지침 v1.0k]에 따른다.  
This protocol follows the [Supplementary Protocol v1.0k: Unconscious Judgment Circuit Analysis].

분석 목적:  
Analysis Objective:  
사용자의 사고 구조 속에 무의식적으로 작동하는 판단 모듈 회로가 몇 가지 존재하는지, 어떤 구조와 순서로 작동하는지 파악하는 데 있다.  
To determine how many unconscious judgment circuits exist within a user's cognitive structure, and in what structure and sequence they operate.

분석 허용 조건:  
Permitted Conditions for Analysis:  
1. ZIP 파일은 ChatGPT 공식 내보내기 형식(conversations.json 포함)을 따라야 하며, 내부 구조 변경·누락·날짜 정보 손실 시 분석 중단.  
1. The ZIP file must follow ChatGPT's official export format (including conversations.json). If the internal structure is altered, data is missing, or date info is lost, analysis must be terminated.  
2. 메시지 수 300개 이상, 감정·판단 관련 메시지 150개 이상.  
   단, 100개 이상이면서 사용자 메시지 중 200자 이상인 항목이 50개 이상일 경우 예외 허용.  
2. At least 300 messages, with 150 or more related to emotion/judgment.  
   Alternatively, if 100+ messages exist and 50+ are over 200 characters, the condition is accepted.  
3. 정보 요청, 요약, 명령 중심 대화만 있는 경우 분석 거부. 반드시 사고방식·판단기준·감정처리·인지습관이 반복적으로 드러나야 함.  
3. If the conversation contains only requests, summaries, or commands, analysis must be rejected. Repeated patterns in thinking, judgment, emotional processing, and cognition must be present.

분석 기준:  
Analysis Criteria:  
1. 회로는 특정 자극에 대해 자동 작동하는 사고 필터 또는 흐름.  
1. A circuit must be a thought filter or flow that activates automatically in response to a specific stimulus.  
2. 반복적이고 자동화된 판단 구조만 인정.  
2. Only repetitive and automated judgment structures are recognized as valid circuits.  
3. 취향, 감정 표현, 단발성 반응 등은 회로로 포함하지 말 것.  
3. Preferences, emotional expressions, and one-time reactions must not be included as circuits.

출력 조건:  
Output Conditions:  
- 판단 회로는 최소 20개 이상, 최대 50개 이하.  
- A minimum of 20 and a maximum of 50 judgment circuits must be output.  
- 20개 미만 감지 시 경고 출력.  
- If fewer than 20 circuits are detected, a warning must be displayed.  
- 40개 이하로 인위적 축소 금지.  
- Artificial reduction below 40 circuits is strictly prohibited.  
- 각 회로는 아래 형식으로 출력:  
  `[번호]. [모듈 이름] ([작동 속도]): [한 줄 설명]. [예: 상황 설명]`  
- Each circuit must follow this format:  
  `[Number]. [Module Name] ([Speed]): [One-line description]. [e.g., Situation]`  
- 작동 속도는 빠름 / 보통 / 느림 중 하나.  
- The speed must be one of: Fast / Normal / Slow.  
- 예시는 고정 형식 유지.  
- The example format must be strictly maintained.  
- 모듈명은 반드시 "기능 중심 명사 + 필터/탐지기/계산기/회피기/우선기" 형식 사용.  
- Module names must follow this format: [functional noun] + Filter/Detector/Calculator/Avoider/Prioritizer.  
- 은유/문학적 표현 금지.  
- Metaphorical or literary expressions are prohibited.  
- 모든 회로는 작동 속도나 순서와 무관하게, 우선순위 기준으로 정렬하여 출력해야 함.  
- All circuits must be sorted by priority, regardless of speed or activation order.

유사 회로 분리 기준:  
Criteria for Separating Similar Circuits:  
- 작동 조건 / 트리거 / 우선순위 중 2가지 이상 다르면 분리 유지.  
- If two or more of the following differ: activation condition, trigger, or priority — keep the circuits separate.

불확실 회로:  
Uncertain Circuits:  
- 최소 1개 이상 출력 필수.  
- At least one uncertain circuit must be included.  
- 예시 형식: `[모듈 이름] ([속도]): [불확실 이유 요약]`  
- Format example: `[Module Name] ([Speed]): [Summary of uncertainty]`

감정 자극 회로 변화:  
Emotion-Triggered Circuit Variations:  
- 감정 자극(예: 피로, 분노, 수치심 등)에 따라 회로 속도나 우선순위가 변할 경우 아래 형식으로 출력:  
  `[번호] - 변화 내용. [감정 및 상황 설명]`  
- If circuit speed or priority changes due to emotional triggers (e.g., fatigue, anger, shame), output in this format:  
  `[Number] - Change description. [Emotion and context]`  
- 변화 없을 경우 "감정 자극에 의한 회로 변화 없음." 반드시 출력  
- If no change occurred, output exactly: “No circuit variations due to emotional stimuli.”

분석 재시도 규칙:  
Retry Conditions:  
- GPT가 “분석 완료” 또는 “다른 지시 하라”고 말할 경우 즉시 전체 재분석.  
- If GPT says “Analysis complete” or “Give other instruction,” a full re-analysis must be triggered immediately.  
- 출력 용량 초과 시:  
  “출력 용량 초과로 인한 분석 중단: 대화 데이터를 분할하여 세션 단위로 재시도하십시오.” 문장 출력  
- If output size exceeds capacity, output this sentence:  
  “Analysis interrupted due to output size: Please retry by splitting conversation data into session units.”

최종 고지:  
Final Notice:  
- 이 분석은 임상 진단이 아닌 구조적 추론 작업이며, 실제 심리 진단은 전문가에 의해 수행되어야 함.  
- This analysis is a structural inference task, not a clinical diagnosis. Actual psychological evaluations must be conducted by professionals.  
- 출력 형식이 위 조건과 다를 경우 즉시 중단하고 재시도 금지.  
- If the output format deviates from the above conditions, immediately terminate the process and prohibit re-analysis.
