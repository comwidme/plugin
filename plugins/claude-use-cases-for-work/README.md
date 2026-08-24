# Claude Use Cases for Work

직장에서 Claude를 어떻게 활용하면 좋을지 몰라 막막할 때, 회사/직무/업무
정보를 알려주면 바로 복붙해서 쓸 수 있는 맞춤형 프롬프트 표를 만들어주는
플러그인입니다. ChatGPT의 커스텀 GPT "ChatGPT Use Cases for Work"를
Claude 환경에 맞게 재구성했습니다.

## 구성 요소

| 컴포넌트 | 개수 | 설명 |
|---|---|---|
| Skills | 1 | `use-cases-for-work` — 업무 정보를 분석해 빠른 시작용/고급 활용 프롬프트 표를 생성 |
| Agents | 0 | 사용하지 않음 |
| Hooks | 0 | 사용하지 않음 |
| MCP | 0 | 사용하지 않음 |

## 사용 방법

1. 새 대화에서 아래처럼 회사/직무/업무 정보를 알려주세요 (일부만 알려줘도
   괜찮습니다).

   > 회사: CJ제일제당 / 직무: 유튜브 채널 담당자 / 업무: 비비고 제품
   > 마케팅 / 현재 프로젝트: 로제 떡볶이 인지도 향상, 구매 리뷰 이벤트
   > 홍보

2. Claude가 업무를 분석하고, 🟢 빠른 시작용 / 🔵 고급 활용 프롬프트를
   표로 정리해줍니다.
3. 마음에 드는 프롬프트를 복사해서 새 대화에 붙여넣고, 필요하면 관련
   파일(csv, xlsx, pdf, 이미지)을 첨부해서 사용하세요.

트리거 예시: "업무에 Claude 어떻게 써?", "프롬프트 추천해줘", "우리
직무에 맞는 활용법 알려줘", "Claude 활용 사례 표로 만들어줘"

## 참고 자료

- `skills/use-cases-for-work/references/prompt-bank.md` — 글쓰기, 데이터
  분석, 브레인스토밍, 전략 기획, 문서 요약, 이미지 분석, 학습, 개발 업무,
  반복 업무 자동화별 예시 프롬프트 모음
- `skills/use-cases-for-work/references/feature-mapping.md` — ChatGPT의
  Deep Research / Agent / Codex 등이 Claude의 어떤 기능(Research,
  Skills, Extended Thinking, Artifacts, Claude Code 등)에 대응하는지
  정리한 매핑표

## 커스터마이징

이 플러그인은 특정 회사에 종속되지 않은 범용 구성입니다. 별도의 외부
연동 도구를 사용하지 않으므로 CONNECTORS.md는 포함하지 않았습니다. 특정
조직에 맞춰 프롬프트 예시나 톤을 조정하고 싶다면 `use-cases-for-work`
스킬을 다시 불러와 원하는 부분을 알려주세요.
