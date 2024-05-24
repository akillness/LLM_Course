

## Simple LLM to prepare Project


| Title | emoji | colorFrom | colorTo | sdk | app_file | pinned |
| :--- | :--- | :---| :--- | :--- | :--- | :--- |
| [Simple LLM](https://github.com/streamlit/llm-examples) | 🎈 | - | - | streamlit | 6_Chatbot_with_OpenAI.py | false |
| [Simple LLM Finetuner](https://github.com/lxe/simple-llm-finetuner?tab=readme-ov-file) | 🦙 | yellow | orange | gradio | app.py | false |


+ Simple LLM Finetuner is a beginner-friendly interface designed to facilitate fine-tuning various language models using [LoRA](https://arxiv.org/abs/2106.09685) method via the [PEFT](https://github.com/huggingface/peft) library on commodity NVIDIA GPUs.  
  + <https://akillness.github.io/posts/llm-agents>


<details markdown="1">
<summary> State-of-the-art Parameter-Efficient Fine-Tuning (PEFT) methods </summary>

대규모 사전 학습 모델의 미세 조정은 그 규모 때문에 종종 비용이 많이 듭니다. 파라미터 효율적 미세 조정(PEFT) 방법은 모델의 모든 파라미터 대신 소수의(추가) 모델 파라미터만 미세 조정함으로써 대규모 사전 학습 모델을 다양한 다운스트림 응용 프로그램에 효율적으로 적응시킬 수 있습니다. 이는 컴퓨팅 및 저장 비용을 크게 감소시킵니다. 최근 최첨단 PEFT 기술은 완전히 미세 조정된 모델과 비슷한 성능을 달성합니다.

PEFT는 모델 훈련과 추론을 쉽게 하기 위해 Transformers와 통합되었으며, Diffusers를 통해 다양한 어댑터를 편리하게 관리할 수 있습니다. 또한, Accelerate를 통해 매우 큰 모델의 분산 훈련과 추론이 가능합니다.

팁

PEFT 라이브러리에 구현된 PEFT 방법에 대해 읽고, 이러한 방법을 다양한 다운스트림 작업에 적용하는 방법을 보여주는 노트북을 확인하려면 PEFT 조직 페이지를 방문하세요. 조직 페이지에서 "Watch repos" 버튼을 클릭하여 새로 구현된 방법과 노트북에 대한 알림을 받을 수 있습니다!

지원되는 PEFT 방법 목록은 PEFT 어댑터 API 참조 섹션을 확인하고, 이러한 방법이 어떻게 작동하는지 배우기 위해 어댑터, 소프트 프롬프트 및 IA3 개념 가이드를 읽어보세요.

</details>

## Install Dependency
~~~sh
$ pip install -r requirements.txt
~~~

## Run it locally
~~~sh
$ virtualenv .venv
$ source .venv/bin/activate
$ pip install -r requirements.txt
$ streamlit run 6_Chatbot_with_OpenAI.py
~~~

* * *

## Keywords (용어설명)

1. [Anthropic](https://namu.wiki/w/Anthropic)
   - 개요 :  [미국](https://namu.wiki/w/%EB%AF%B8%EA%B5%AD)의 [인공지능](https://namu.wiki/w/%EC%9D%B8%EA%B3%B5%EC%A7%80%EB%8A%A5) [스타트업](https://namu.wiki/w/%EC%8A%A4%ED%83%80%ED%8A%B8%EC%97%85)이다. 창업자 전원이 [OpenAI](https://namu.wiki/w/OpenAI) 출신의 인물이며, [생성형 인공지능](https://namu.wiki/w/%EC%83%9D%EC%84%B1%ED%98%95%20%EC%9D%B8%EA%B3%B5%EC%A7%80%EB%8A%A5) 업체 중에서는 OpenAI에 이어서 규모가 가장 큰 기업
   - 제품 :
     -  Claude.ai : [Haiku](https://namu.wiki/w/%ED%95%98%EC%9D%B4%EC%BF%A0), [Sonnet](https://namu.wiki/w/%EC%86%8C%EB%84%A4%ED%8A%B8), [Opus](https://namu.wiki/w/%EC%98%A4%ED%91%B8%EC%8A%A4#s-1)
   - - 기타 : Python package 에 출시
2. Langchain
   - 개요 : [**대규모 언어 모델을 활용한 혁신적인 프레임워크**](https://wikidocs.net/231151)
     - 대규모 언어 모델(LLM)을 활용하여 애플리케이션과 파이프라인을 신속하게 구축할 수 있는 플랫폼의 필요성을 느껴, 이러한 비전을 가지고 개발자들이 챗봇, 질의응답 시스템, 자동 요약 등 다양한 LLM 애플리케이션을 쉽게 개발할 수 있도록 지원하는 프레임워크.
     - 2023년 4월, 랭체인은 법인으로 전환하고 세쿼이아캐피털 등 벤처캐피탈의 투자를 받으며 빠르게 성장 중
   - 기타 : Python package 사용가능
