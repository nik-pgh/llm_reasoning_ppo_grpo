# The RL Reasoning Revolution

> **PPO에서 GRPO, DeepSeek R1까지: 수학적 원리와 추론 모델의 발전 과정을 이해하기 위한 발표 자료**

이 저장소는 대형 언어 모델(LLM)의 비약적인 추론(Reasoning) 능력을 강화학습(RL)으로 이끌어내는 과정 및 핵심 원리를 설명하는 프레젠테이션 슬라이드입니다. [Reveal.js](https://revealjs.com/) 기반의 단일 HTML 파일 형태로 구성되어 있어, 추가 설치 없이 웹 브라우저에서 바로 발표가 가능합니다.

## 🔗 프레젠테이션 보기 (GitHub Pages)
👉 **[프레젠테이션 바로가기](https://nik-pgh.github.io/llm_reasoning_ppo_grpo/)**

## 🎯 주요 내용 (Contents)
1. **추론을 강화학습(RL)으로 푸는 이유**: 데이터셋 구축 비용, Human Bias 등 지도학습(SFT)의 한계와 RL의 우회적 접근법
2. **GRPO vs PPO 비교**: 리워드 최적화 여정, Advantage의 개념, Value Model의 한계(PPO), 그리고 이를 극복한 그룹 내 상대평가 방식(GRPO)의 수학적 차이점
3. **"Stalled Performance" 문제**: 토큰 길이 폭주와 보상 해킹(Reward Hacking) 현상, 그리고 이를 극복하기 위한 DAPO 및 Dr. GRPO 손실 함수 디자인 비교
4. **DeepSeek R1 파이프라인**: V3-Base에서 시작되는 콜드스타트 SFT → 추론 GRPO → 종합 SFT → 종합 GRPO 파이프라인과 작은 모델로 능력을 이식하는 Distillation(지식 증류)

## 🚀 로컬 실행 방법 (How to Run Locally)
1. 이 저장소를 클론합니다:
   ```bash
   git clone https://github.com/nik-pgh/llm_reasoning_ppo_grpo.git
   ```
2. 폴더 내의 `index.html` 파일을 원하시는 웹 브라우저(Chrome, Safari 등)로 엽니다.
3. 스페이스바 또는 방향키(`→`, `←`)를 통해 슬라이드를 넘기며 발표를 진행할 수 있습니다.

## 🛠 기술 스택
- HTML5 / CSS3
- [Reveal.js](https://revealjs.com/): 프레젠테이션 프레임워크
- [MathJax 3](https://www.mathjax.org/): LaTeX 수식 렌더링 지원
