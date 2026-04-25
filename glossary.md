# 용어 사전

길을 잃었을 때 돌아오는 곳이에요. 본문에서 처음 등장한 영문 용어를 한 줄로 풀어 모았습니다.

가나다 → 알파벳 순으로 정렬되어 있어요. 같은 개념의 영문 표기는 괄호 안에 적었습니다.

---

## ㄱ

- **경사하강법** (gradient descent) — 산 정상에서 안개 속을 더듬어 내려가듯, 모델이 한 발씩 "더 낮은(더 잘 맞는) 방향" 을 찾아가는 학습 방법. 핵심은 "틀린 만큼 그쪽으로 움직이지 마." → [03화](chapters/03-training.md)

## ㅂ

- **베이스 모델** (base model) — 사전학습만 마친 가공 안 된 모델. 친절하지 않고 거칠며, 인터넷 평균을 그대로 흉내 냄. → [07화](chapters/07-rlhf.md)

## ㅅ

- **사전학습** (pretraining) — 모델을 본격적으로 쓰기 전, 인터넷의 거대한 글 더미로 시키는 첫 학습. 빈칸 채우기 시험을 수십억 번 반복. → [03화](chapters/03-training.md)

## ㅇ

- **에이전트** (agent) — 도구를 쓸 수 있도록 LLM 에 몸(하네스) 을 붙인 것. 글만 만드는 LLM 과 달리 파일을 열고 명령을 실행하는 등 실제 행동을 함. → [09화](chapters/09-agents.md)
- **온도** (temperature) — 모델이 답을 얼마나 다양하게 뽑을지 조절하는 값. 0 이면 항상 1등 후보만 뽑고(단조로움), 높을수록 다양해짐(창의적이거나 헛소리). → [04화](chapters/04-inference.md)

## ㅈ

- **잠재 공간** (latent space) — 모델 안에 숨어 있는 단어·개념의 의미 좌표 공간. 비슷한 의미는 가까이, 다른 의미는 멀리 배치됨. 학습이 자연스럽게 만들어낸 의미의 기하학. → [99화](chapters/99-epilogue.md)

## ㅋ

- **컨텍스트 윈도우** (context window) — 모델이 한 번에 한꺼번에 볼 수 있는 글의 양. 토큰 수로 매겨짐. 그 너머의 글은 책상에서 떨어지듯 잘려나감. → [05화](chapters/05-context-window.md)

## ㅌ

- **토큰** (token) — AI 가 한 번에 처리하는 글자 덩어리. 글자보다 크고 단어보다 작거나 같은 단위. 영어에선 한 단어가 한 토큰이 되기도, 한국어에선 한 글자가 한 토큰이 되기도. → [02화](chapters/02-tokens.md)

## ㅍ

- **파라미터** (parameter) — 모델 안에 들어 있는 학습 가능한 숫자. 학습 중에 머리카락 한 올씩 조정되는 게 바로 이 숫자들. GPT-3 약 1,750억 개. → [03화](chapters/03-training.md)
- **프롬프트** (prompt) — 우리가 AI 에게 입력하는 모든 글. 어떻게 묻느냐(역할·맥락·예시·출력 형식 깔기) 에 따라 답의 품질이 극적으로 달라짐. → [08화](chapters/08-prompting.md)

## ㅎ

- **하네스** (harness) — 원래 말의 마구. 여기선 LLM 을 감싸서 외부 세계와 연결해주는 실행 환경. 도구 호출·반복 루프·안전 장치를 담당. → [09화](chapters/09-agents.md)
- **학습 컷오프** (knowledge cutoff) — 모델이 학습한 데이터의 마지막 시점. 그 이후 일은 모델이 모르고, 모델 자신도 자기가 어디까지 알고 있는지 잘 모름. → [10화](chapters/10-limits.md)
- **환각** (hallucination) — AI 가 사실이 아닌 걸 사실인 것처럼 자신만만하게 만들어내는 현상. 거짓말이 아니라 "다음 토큰 룰렛" 의 부산물. → [06화](chapters/06-hallucination.md)

## A–Z

- **API** (Application Programming Interface) — 챗봇 화면 대신 서버에 직접 요청해서 AI 를 쓰는 방식. 사용량(토큰 수) 기반으로 과금. → [02화](chapters/02-tokens.md)
- **Chain-of-Thought** (생각의 사슬) — 모델이 풀이 과정을 한 단계씩 글로 풀어 쓰면서 답으로 가는 방식. "단계별로 생각해줘" 한 마디만 추가해도 정답률이 올라감. → [08화](chapters/08-prompting.md)
- **GPU** (Graphics Processing Unit) — 원래 게임 그래픽용으로 만든 칩이지만 AI 학습에 가장 잘 맞아 핵심 인프라가 된 칩. → [03화](chapters/03-training.md)
- **LLM** (Large Language Model, 대규모 언어 모델) — 인터넷 규모의 글을 학습해 다음에 올 단어를 짐작하는, 숫자를 수천억 개 가진 거대한 언어 흉내쟁이. ChatGPT·Claude 같은 챗봇의 본체. → [01화](chapters/01-next-word-game.md)
- **RAG** (Retrieval-Augmented Generation, 검색으로 보강하는 답 생성) — 외부 검색 엔진 등으로 사실 자료를 찾아 모델 입력에 끼워 넣어서 환각을 줄이는 방식. → [06화](chapters/06-hallucination.md)
- **RLHF** (Reinforcement Learning from Human Feedback, 사람의 피드백을 통한 강화학습) — 모델이 만든 두 답 중 사람이 더 좋은 답을 골라주고, 그 정보로 모델을 미세 조정하는 작업. ChatGPT 의 친절함을 만든 두 번째 학습 단계. → [07화](chapters/07-rlhf.md)
