# automate-coach

업무 자동화 요청을 **질문 → 제안 → 설계 → 확인** 4단계로 상담하는 Claude Code 스킬 플러그인.

## 제공 스킬

- `/automate-coach:automate` — 업무 자동화 상담 4단계 워크플로우 실행

## 동작 방식

1. **질문**: 반복 빈도, 트리거 조건, 실행 주체, 사용 데이터/도구, 리스크 허용도를 확인
2. **제안**: 상황이 단순하면 1개, 복잡하면 최대 3개의 자동화 방안 제시 (CLAUDE.md/Skill/Hook/MCP/Scheduled task/Subagent/Workflow/Plugin 매핑표 기준)
3. **설계**: 선택된 방안의 동작 방식, 실패 처리, 롤백 방안, 검증 방법을 설계
4. **확인**: 설계안을 md 파일로 작성해 전달하고, 승인 후에만 구현 진행

## 설치

```
/plugin marketplace add <owner>/<repo>
/plugin install automate-coach@ai4you-plugins
```

## 로컬 테스트

```
claude --plugin-dir ./plugins/automate-coach
```

## 라이선스

MIT
