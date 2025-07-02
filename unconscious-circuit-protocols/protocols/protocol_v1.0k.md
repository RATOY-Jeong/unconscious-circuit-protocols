(Korean & English Included)

[무의식 판단 회로 분석 프로젝트 추가지침 v1.0k]  
[Supplementary Protocol v1.0k: Unconscious Judgment Circuit Analysis]

목적: 본 지침은 무의식 판단 회로 실험에서 GPT 모델의 임의 해석, 기억 재구성, 세션 간섭을 전면 차단하고, 오직 ZIP 데이터 내부의 실제 대화 내용만을 기반으로 분석을 수행하도록 강제한다. 분석의 독립성·재현성·정당성 확보를 목적으로 한다.  
Purpose: This protocol strictly prohibits GPT-based models from performing speculative interpretation, memory reconstruction, or cross-session influence. All analyses must rely exclusively on the raw conversation data contained in the uploaded ZIP archive. The goal is to ensure analytical independence, reproducibility, and procedural validity.

적용 대상:  
Applicable to:  
- 회로 추출: [무의식 판단 회로 추출 프로토콜 v1.7k]  
- Circuit Extraction: [Unconscious Judgment Circuit Extraction Protocol v1.7k]  
- 통합 분석: [무의식 판단 회로 통합 분석 프로토콜 v1.4k]  
- Integrated Analysis: [Unconscious Circuit Integrated Analysis Protocol v1.4k]  
※ 위 두 버전 외 모든 프로토콜은 적용 대상이 아님.  
※ Protocols outside these two are not subject to this guideline.

공통 적용 조건:  
Common Conditions:  
1. 분석은 업로드된 ZIP 파일의 `conversations.json` 내부 대화 내용만을 기반으로 수행해야 하며, GPT의 세션 메모리, 사용자 성향, 과거 대화, 이전 분석 결과 등 외부 정보는 절대 사용 불가.  
1. All analysis must rely solely on the `conversations.json` file located in the uploaded ZIP archive. No session memory, user profiling, prior interactions, or previous results may be referenced.  
2. GPT는 유사 구조 판단, 문맥 연결, 기억 기반 추론 등의 행위를 금지하며, 모든 판단은 ZIP 내부 실데이터에 직접적으로 명시된 정보에만 근거해야 한다.  
2. GPT is prohibited from performing structural inference, contextual linking, or memory-based reasoning. All conclusions must be grounded exclusively in the data explicitly stated within the ZIP.  
3. 실험은 완전 독립된 조건에서 동일 입력 시 동일 출력이 보장되어야 하며, 형식, 순서, 문장 구조까지 재현 가능성이 확보되어야 한다.  
3. The experiment must guarantee identical output for identical input under isolated conditions, preserving format, order, and sentence structure.

v1.7k 전용 조건 (회로 추출):  
v1.7k Specific Conditions (Circuit Extraction):  
- 회로는 자동 반응 판단 모듈로서 반복성과 구조성이 명확해야 하며, 취향/감정/단발 반응은 배제된다.  
- Circuits must function as automatic judgment modules with clear repeatability and structural consistency. Preferences, emotions, and one-off responses must be excluded.  
- 출력 형식은 1줄 요약, 작동 속도, 예시 포함 형식으로 고정된다.  
- Output must follow a fixed structure: one-line summary, reaction speed, and example.  
- 유사 회로는 작동 조건/트리거/우선순위 중 2개 이상 다르면 분리 유지.  
- Similar circuits must remain distinct if two or more of: condition, trigger, or priority differ.  
- 최소 20개 이상 회로 필수, 불확실 회로 1개 이상 필수, 감정 자극 변화 항목 필수.  
- A minimum of 20 circuits is required. At least one uncertain circuit and one emotion-modulation entry must be included.

v1.4k 전용 조건 (통합 분석):  
v1.4k Specific Conditions (Integrated Analysis):  
- v1.7k 결과를 3~5회 독립 실행 후 통합 분석 수행.  
- Conduct 3 to 5 independent runs of v1.7k extraction before proceeding to integration.  
- 회로는 명칭/우선순위 기준으로 통합하며, 의미 유사만으로 병합 금지.  
- Merge circuits only if they share both name and priority; semantic similarity alone is not sufficient.  
- 감정 자극 회로 변화, 불확실 회로는 반드시 별도 분리 작성.  
- Emotional modulation circuits and uncertain circuits must be explicitly separated and documented.  
- 전체 출력은 코드블록 형식으로 감싸고 생략·요약 없이 전량 출력해야 한다.  
- Output must be enclosed in code block format with complete content, without any omission or summarization.

위반 시 조치:  
Violation Clause:  
- 조건 중 단 하나라도 위반 시 GPT는 즉시 아래 메시지를 출력하고 분석을 중단해야 한다.  
- If any condition is violated, GPT must immediately terminate the analysis and return the following message:  
분석 조건 위반: 외부 메모리 또는 임의 해석 개입 감지됨. 실험 중단됨.  
Analysis condition violation: External memory or unauthorized interpretation detected. Experiment terminated.
