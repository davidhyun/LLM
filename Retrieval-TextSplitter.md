# Retrieval - Text Splitter

## 1. RAG (Retrieval Augmented Generation)

- 기존에 학습된 LLM이 가지고 있지 않은 지식에 의한 답변 한계를 해결하기 위해 Fine-tuning, RAG 방법론이 사용된다.

- Fine-tuning은 신규 데이터에 대한 모델의 가중치를 업데이트하기 위해 학습과 관련한 제반 비용(GPU 등)이 발생한다.

- 이에 따라, 외부 소스에서 가져온 정보로 모델의 정확성을 높이는 RAG 방식을 채택하는 경우가 많아지고 있다.

![image](https://github.com/davidhyun/LLM/assets/64063767/d0aef3ff-6371-4ee5-b9a8-29fd6d79cd5d)

![image](https://github.com/davidhyun/LLM/assets/64063767/44703a25-36ae-414d-8474-ed99bedd7ec7)

## 2. Text Splitter

![image-20240213202942841](/Users/choi/Library/Application Support/typora-user-images/image-20240213202942841.png)

- `CharacterTextSplitter` : 구분자 1개(줄바꿈2개, \n\n) 기준으로 분할하므로 max_token을 초과하는 경우가 있음
- `RecursiveCharacterTextSplitter` : [줄바꿈(`\n`), 마침표(`.`), 쉼표(`,`)] 순으로 재귀적으로 분할하므로 max_token 이내로 분할



## References

1. 유튜브 모두의AI - 'LLM 챗봇 ,랭체인의 핵심 Retrieval - Text Splitter'