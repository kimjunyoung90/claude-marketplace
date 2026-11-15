# claude-marketplace

Kim Junyoung의 개인 Claude Code 플러그인 마켓플레이스입니다. 플러그인은 각자 자기 저장소에 있고, 이 저장소에는 목록(`marketplace.json`)만 있습니다.

## 추가

```
/plugin marketplace add kimjunyoung90/claude-marketplace
```

## 플러그인

| 플러그인 | 설명 | 설치 |
|---|---|---|
| [genius](https://github.com/kimjunyoung90/genius) | 공부 노트로 손글씨 PDF 시험을 보고, 몰랐던 것을 학습 로그에 쌓아 간격 복습 | `/plugin install genius@kimjunyoung90` |
| [todo](https://github.com/kimjunyoung90/todo) | 지라 기반 할 일 관리 — 할 일 추가·시작·완료와 작업 내역 기록 | `/plugin install todo@kimjunyoung90` |
| [my-skills](https://github.com/kimjunyoung90/my-skills) | 특정 목적에 묶이지 않는 범용 스킬 모음 | `/plugin install my-skills@kimjunyoung90` |

## 플러그인 추가하는 법

플러그인을 별도 저장소로 만들고(저장소 루트에 `.claude-plugin/plugin.json` 포함), `marketplace.json`의 `plugins`에 `{"name": "<name>", "source": {"source": "github", "repo": "kimjunyoung90/<name>"}}` 항목을 추가합니다.
