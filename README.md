# 맥락 중심 학습 에이전트

> 정의를 외우는 건 시험용. 맥락으로 배우는 건 실전용.

새로운 개념, 분야, 역할, 프로세스를 입력하면
**그 세계의 장면을 보여줘서 감을 잡게 해주는** 에이전트입니다.

## 왜 만들었는가

초중고 12년 동안 영어를 배웠는데 외국인 앞에서 한마디도 못 하는 이유.
**맥락 중심 학습**을 못 해서입니다.

미국에서 태어난 아이는 "apple = 사과"를 외우지 않습니다.
엄마가 사과를 보며 "Where's the apple?" 하는 걸 보고,
**맥락 속에서** apple이 뭔지 알게 됩니다.

사업도, 업무도, 새로운 분야도 똑같습니다.
이 에이전트는 어떤 주제든 **장면으로** 배울 수 있게 도와줍니다.

## 설치 — 글로벌 스킬 (추천)

어디서든 `/aijeong_context`를 쓰려면 글로벌 커맨드로 설치하세요.

```bash
# 1. 글로벌 commands 폴더 생성 (없으면)
mkdir -p ~/.claude/commands

# 2. 파일 하나만 복사
curl -o ~/.claude/commands/aijeong_context.md \
  https://raw.githubusercontent.com/happyhappy82/context-learning-agent/main/.claude/commands/aijeong_context.md
```

끝. 이제 아무 프로젝트에서나:

```
/aijeong_context SaaS 사업
/aijeong_context 스타트업 대표
/aijeong_context 투자 유치 과정
/aijeong_context 유닛 이코노믹스
```

## 입력 유형

| 입력 | 예시 | 보여주는 것 |
|------|------|-----------|
| **단어/개념** | "유닛 이코노믹스" | 이 단어가 실제로 쓰이는 장면 20개 |
| **분야/도메인** | "SaaS 사업" | 이 바닥이 어떻게 돌아가는지 |
| **역할/직무** | "HR 담당자" | 이 사람의 하루, 의사결정, 압박 |
| **프로세스** | "투자 유치 과정" | 처음~끝 단계별 장면 + 망하는 지점 |

전부 설명이 아니라 **장면**으로 나옵니다.

## 다른 방법으로 쓰기

### 프로젝트 레벨 설치
```bash
git clone https://github.com/happyhappy82/context-learning-agent.git
cd context-learning-agent
claude
```

### ChatGPT / Claude 웹
`system-prompt.md` 내용을 Custom GPT Instructions 또는 Claude 프로젝트 지침에 붙여넣기.

### 그냥 복붙
`system-prompt.md` 내용을 대화 맨 처음에 붙여넣고 바로 사용.

---

**by 에이정 (AI Jeong)**
기업 AI 정착 교육
"가장 중요한 건 정착입니다. 쓰지 못하면 아무 소용 없습니다."
