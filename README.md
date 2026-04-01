# 맥락 중심 학습 에이전트

> 정의를 외우는 건 시험용. 맥락으로 배우는 건 실전용.

새로운 개념, 분야, 용어를 입력하면
**맥락 속에서 자연스럽게 이해할 수 있는 레퍼런스 예시**를 대량으로 만들어주는 에이전트입니다.

## 왜 만들었는가

초중고 12년 동안 영어를 배웠는데 외국인 앞에서 한마디도 못 하는 이유.
**맥락 중심 학습**을 못 해서입니다.

미국에서 태어난 아이는 "apple = 사과"를 외우지 않습니다.
엄마가 사과를 보며 "Where's the apple?" 하는 걸 보고,
**맥락 속에서** apple이 뭔지 알게 됩니다.

이 에이전트는 어떤 개념이든 그렇게 배울 수 있게 도와줍니다.

## 사용법

### Claude Code (추천)

이 레포를 클론하면 바로 씁니다.

```bash
git clone https://github.com/YOUR_USERNAME/context-learning-agent.git
cd context-learning-agent
claude
```

Claude Code 안에서:

```
/aijeong_context Resilience
/aijeong_context 유닛 이코노믹스
/aijeong_context 퍼포먼스 마케팅
/aijeong_context OKR
```

이미 다른 프로젝트에서 쓰고 싶으면 파일 하나만 복사:

```bash
cp .claude/commands/aijeong_context.md 내프로젝트/.claude/commands/
```

### ChatGPT / Claude 웹
`system-prompt.md` 내용을 Custom GPT Instructions 또는 Claude 프로젝트 지침에 붙여넣기.

### 그냥 복붙
`system-prompt.md` 내용을 대화 맨 처음에 붙여넣고 바로 사용.

## 사용 예시

```
/aijeong_context 유닛 이코노믹스
```

**출력:**
- 한 줄 정의
- 맥락 레퍼런스 20개+ (일상/비즈니스/실패/성공 상황별)
- 헷갈리는 개념 비교
- 셀프 테스트

## 이런 분한테 유용합니다

- 새 분야에 진입하는 사람
- 용어는 알겠는데 실전에서 못 쓰는 사람
- "그래서 그게 뭔데?"를 자주 듣는 사람
- 교과서 정의 말고 진짜 감을 잡고 싶은 사람

---

**by 에이정 (AI Jeong)**
기업 AI 정착 교육
"가장 중요한 건 정착입니다. 쓰지 못하면 아무 소용 없습니다."
