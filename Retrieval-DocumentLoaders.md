# Retrieval - Document Loaders

## 1. RAG (Retrieval Augmented Generation)

- 기존에 학습된 LLM이 가지고 있지 않은 지식에 의한 답변 한계를 해결하기 위해 Fine-tuning, RAG 방법론이 사용된다.

- Fine-tuning은 신규 데이터에 대한 모델의 가중치를 업데이트하기 위해 학습과 관련한 제반 비용(GPU 등)이 발생한다.

- 이에 따라, 외부 소스에서 가져온 정보로 모델의 정확성을 높이는 RAG 방식을 채택하는 경우가 많아지고 있다.

![image](https://github.com/davidhyun/LLM/assets/64063767/d0aef3ff-6371-4ee5-b9a8-29fd6d79cd5d)

![image](https://github.com/davidhyun/LLM/assets/64063767/44703a25-36ae-414d-8474-ed99bedd7ec7)

## 2. Document Loaders

Document Loaders는 다양한 형태의 문서를 RAG 전용 객체로 불러오는 모듈

- Page_content : 문서의 내용
- Metadata : 문서의 위치, 제목, 페이지 넘버 등



## References

1. 유튜브 모두의AI - 'LLM 챗봇 ,랭체인의 핵심 Retrieval - Document Loaders'