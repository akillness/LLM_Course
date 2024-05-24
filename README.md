

## Simple LLM to prepare Project


| Title | emoji | colorFrom | colorTo | sdk | app_file | pinned |
| :--- | :--- | :---| :--- | :--- | :--- | :--- |
| [Simple LLM](https://github.com/streamlit/llm-examples) | 🎈 | - | - | streamlit | 6_Cahtbot_with_OpenAI.py | false |
| [Simple LLM Finetuner](https://github.com/lxe/simple-llm-finetuner?tab=readme-ov-file) | 🦙 | yellow | orange | gradio | app.py | false |


+ Simple LLM Finetuner is a beginner-friendly interface designed to facilitate fine-tuning various language models using [LoRA](https://arxiv.org/abs/2106.09685) method via the [PEFT](https://github.com/huggingface/peft) library on commodity NVIDIA GPUs.  
  + <https://akillness.github.io/posts/llm-agents>

## Install Dependency
~~~sh
$ pip install -r requirements.txt
~~~

## Run it locally
~~~sh
virtualenv .venv
source .venv/bin/activate
pip install -r requirements.txt
streamlit run 6_Chatbot_with_OpenAI.py
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
