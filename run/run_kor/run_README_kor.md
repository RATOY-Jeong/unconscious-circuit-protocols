# Run Protocols for Unconscious Circuit Analysis  
> 즉시 사용 가능한 무의식 판단 회로 분석 프로토콜 실행 파일 모음  
> Executable protocol files for immediate use

---

## 📌 소개 (Overview)

본 디렉토리는 연구자 또는 실험자가 직접 실행 가능한  
**고정 포맷의 프로토콜 파일(.md)**을 제공합니다.  

This folder contains fixed-format protocol files (.md)  
that are ready to be copied and used without modification.

⚠️ 주의 (Caution):  
해당 문서들은 **내용 변경 시 분석 무결성이 보장되지 않습니다.**  
변경 없이 전체 복사하여 사용하는 것을 권장합니다.

---

## 📄 포함된 파일 (Included Files)

| 파일명 (Filename) | 설명 (Description) |
|-------------------|---------------------|
| `run_protocol_v1.0k_kor.md` | 초기 조건 및 분석 기준 고정안 / Initial baseline protocol definition |
| `run_protocol_v1.4k_kor.md` | 통합 분석 실행용 프로토콜 / Protocol for integrated analysis |
| `run_protocol_v1.7k_kor.md` | ZIP 기반 자동 회로 추출 프로토콜 / ZIP-based auto extraction |

모든 파일은 UTF-8 인코딩된 **Markdown(.md)** 형식으로 작성되어 있습니다.

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

---

### 8. 주의사항(Cautions)
- ZIP파일은 사진이 적게 들어가 있을수록 분석 확률이 상승합니다. 분석 전 최대한 사진파일을 제거해주세요.
- 간혹 마크다운 형식으로 출력중 중간에 끊기는 경우가 있습니다. 그런경우 결과를 통합하여 마크다운 형식으로 출력하도록 요청하세요.
- 여러 이유로 분석에 실패하는 경우가 있습니다. 새로운 세션에서 다시 시도해주세요.
- 반드시 상기 절차를 따라주세요.

## 👤 저작자 정보 (Author Info)

- Original Creator: **정도현 (DoHyeon Jeong)**  
- Contact: parabellum0208@gmail.com  
- GitHub: https://github.com/RATOY-Jeong/unconscious-circuit-protocols  
- License: CC BY-NC-SA 4.0 / 별도 상업용 계약 필요

---

