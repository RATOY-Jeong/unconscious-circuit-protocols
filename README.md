# Unconscious Judgment Circuit Protocols  
> LLM 기반 무의식 판단 회로 분석 프로토콜 - **학술/비영리용 공개 프로젝트**  
> A license-based open protocol project for unconscious judgment circuit analysis

---

## 📌 소개 (Overview)

이 프로젝트는 대형언어모델(LLM)을 기반으로 사용자의 대화 데이터를 분석하여  
무의식적으로 작동하는 판단 회로를 추출하는 일련의 프로토콜을 제공합니다.  

This project provides a set of structured protocols for extracting  
unconscious judgment circuits based on user conversation data via large language models (LLMs).

**분석 목적 (Purpose of Analysis):**
- 자동화된 사고 구조 분석 (Automated cognitive structure analysis)  
- 감정/판단 회로의 반복 패턴 인식 (Detection of repetitive emotion/judgment patterns)  
- 자기이해 및 심리 패턴 구조화 (Self-awareness and structured psychological pattern inference)

**주요 프로토콜 버전 (Main Protocol Versions):**
- **v1.0k**: 초기 판단 회로 정의 기준 확립 (Initial rule-based definitions)  
- **v1.7k**: ZIP 기반 자동 회로 추출 프로토콜 (Auto-extraction via ZIP-based input)  
- **v1.4k**: 반복 분석 통합 및 회로 안정화 구조 제공 (Stabilization via integrated loop analysis)

---

## 📂 폴더 구조 (Folder Structure)

| 폴더명 (Folder) | 설명 (Description) |
|-----------------|--------------------|
| `protocols/` | 각 프로토콜 버전별 전문 (Markdown) / Protocol source (Markdown) |
| `docs/` | 개요 설명 및 논문/출판용 초안 / Docs & publication drafts |
| `examples/` | 실제 입력 JSON과 출력 예시 / Sample inputs and outputs |
| `rawdata/` | ZIP 분석 조건 및 가이드라인 / Data conditions and guides |
| `run/` | 실행용 프롬포트 및 사용자 가이드 / Runnable prompts and user guide |
| `LICENSE` | 공개 라이선스 파일 / Open license file (CC BY-NC-SA) |
| `LICENSE_Commercial` | 상업용 별도 라이선스 / Separate commercial license |
| `README.md` | 이 파일 / This file |

---

## ⚙️ 사용 방법 (How to Use)

무의식 판단 회로 분석은 아래의 7단계 절차를 따릅니다.

### 1. ZIP 파일 추출 (Export ZIP File)
- ChatGPT 설정(Settings) → 데이터 제어(Data Controls) → **데이터 내보내기(Export)** 클릭
- 받은 ZIP 파일을 보관

### 2. 새 프로젝트 시작 (Start New Project)
- ChatGPT에서 새로운 프로젝트 생성

### 3. 1.0k 지침 추가 (Add v1.0k Guidelines)
- '지침 추가' 를 열어
  `run_protocol_v1.0k_kor.md` 본문 내용을 그대로 복사하여 붙여넣기

### 4. 1.7k 회로 추출 실행 (Run v1.7k Protocol)
- ZIP 파일 업로드
- 프롬프트에 `run_protocol_v1.7k_kor.md` 본문 내용을 그대로 복사하여 붙여넣기

### 5. 3~5회 반복 분석 (Repeat Analysis 3~5 times)
- 동일 ZIP 기반으로 각각 독립된 세션에서 분석을 최소 3회, 최대 5회 반복

### 6. 통합 분석 실행 (Run Integrated v1.4k Analysis)
- 동일 프로젝트 내에서 새 세션(New Chat) 시작
- 시작 문구 입력: `"여기에 3~5개의 분석결과를 올릴거야"`
- 앞서 출력된 결과물 3~5개 전체 붙여넣기
- 마지막으로 `run_protocol_v1.4k_kor.md` 본문 내용을 그대로 복사하여 붙여넣기

### 7. 결과 확인 (Check Final Output)
- 통합 분석된 회로 결과를 확인
- 결과는 Markdown 텍스트 형식으로 자동 출력됨

### 8. 주의사항(Cautions)
- ZIP파일은 사진이 적게 들어가 있을수록 분석 확률이 상승합니다. 분석 전 최대한 사진파일을 제거해주세요.
- 간혹 마크다운 형식으로 출력중 중간에 끊기는 경우가 있습니다. 그런경우 결과를 통합하여 마크다운 형식으로 출력하도록 요청하세요.
- 여러 이유로 분석에 실패하는 경우가 있습니다. 새로운 세션에서 다시 시도해주세요.
- 반드시 상기 절차를 따라주세요.

---

## 📄 논문 및 출판 (Publications)

- arXiv 업로드 예정 (2025.07~08 예정)  
- 본문은 **영문**, Appendix A에 **한글 원문** 포함  

Planned publication on arXiv (July–August 2025).  
Main text in English, Korean version included in Appendix A.

---

## 🧪 라이선스 (Dual Licensing)

이 프로젝트는 **듀얼 라이선스 정책(Dual License)**을 따릅니다.  
This project is dual-licensed as follows:

### 1. 비상업적 목적 (Non-commercial Use)

**Creative Commons BY-NC-SA 4.0** (저작자표시-비영리-동일조건변경허락)  
- 연구, 비영리 프로젝트, 교육 목적 사용 가능  
- 원작자 ‘정도현 (DoHyeon Jeong)’ 명시 필수  
- **상업적 사용 금지**  

For academic, non-commercial use only.  
You must attribute “DoHyeon Jeong” as the author.  
Commercial usage is strictly prohibited.

License Text: [LICENSE]

---

### 2. 상업적 목적 (Commercial Use)

**별도 계약 필요.** 본 프로토콜을 상업적 제품, 유료 서비스, 강의 등에서 활용할 경우,  
**별도의 유료 라이선스 계약이 반드시 필요합니다.**

Separate commercial license required for any for-profit usage, including integration into  
products, services, tools, paid lectures, or internal corporate analysis.

License Text: [LICENSE_Commercial]

- 💰 가격: 연 ₩3,000,000 / 조직 단위 (또는 별도 협의)  
- 📅 사용기간: 1년, 이후 갱신 필요 (영구 라이선스 없음)  
- 📩 문의: parabellum0208@gmail.com  
- 🧾 GitHub: https://github.com/RATOY-Jeong/unconscious-circuit-protocols  

---

## 🔐 면책 조항 (Disclaimer)

- 본 프로토콜은 **구조적 심리 추론 도구**로, 진단/치료 목적이 아닙니다.  
  This protocol is a tool for structural psychological inference — not for diagnosis or therapy.

- 사용 결과에 대한 모든 책임은 사용자에게 있습니다.  
  The user assumes all responsibility for the outcomes of its application.

- 제공 자료는 “있는 그대로(as is)” 제공되며, 특정 목적에 대한 적합성은 보장하지 않습니다.  
  All materials are provided “as-is” with no warranty of suitability for specific purposes.

- 상업적 사용자는 자사 기준에 따라 적용하며, 발생한 문제에 대해  
  **정도현(DoHyeon Jeong)**은 법적 책임을 지지 않습니다.  
  Commercial users apply the protocol at their own discretion and risk.

---

## 🙋‍♂️ 개발자 정보 (Author Info)

- Original Creator: **정도현 (DoHyeon Jeong)**  
- Contact: parabellum0208@gmail.com  
- GitHub: https://github.com/RATOY-Jeong/unconscious-circuit-protocols  
- Powered by: **Chat-GPT**
