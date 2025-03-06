<p align='center'>
    <image src='https://github.com/user-attachments/assets/fafbac18-c808-412e-a29d-9c1e85d9c2cb'>
</p>

## 📖 소개
LangChain은 LLM (Large Language Models) 기반 애플리케이션을 쉽고 효율적으로 구축할 수 있도록 돕는 프레임워크입니다. 이 리포지토리는 LangChain의 핵심 개념을 단계적으로 학습하고, 실습을 통해 RAG의 개념을 이해하는 것을 목표로 합니다.

이 저장소에서는 **LangChain의 주요 기능**과 **RAG의 개념 및 실제 활용 예제**를 다루며, 각 주제별 폴더에 코드와 설명을 정리합니다.

## 📂 폴더 구조

```
RAG-Tutorial/
│── 00-LangChainBasic/    # LangChain 기본 문법 맛보기
│── 01-Chain/             # LangChain Chains 기본 요소
│── 02-Memory/            # 대화 상태 및 메모리 활용
│── 03-DocumentLoader/    # 다양한 형태의 Docuement 로드
│── 04-RAG/               # LangChaind을 활용한 RAG 개념 및 실습
│── 05-PreDefinedChain/   # 사전에 정의된 체인 (Stuff, Map Reduce 등)
│── 06-AdvancedLCEL/      # LCEL 고급 문법 (RunnableLambda 등)
│── 07-RAGEvaluation/     # RAG 평가 및 개선 방법
│── 08-Agent/             # LangChain을 활용한 Agent 개념과 활용
│── 09-LangGraph/         # LangGraph의 기본 개념과 활용
│── 10-LangServe/         # LangServe를 활용한 모델 서빙
│── 99-Projects/          # 실습 미니 프로젝트
│── requirements.txt      # 실행에 필요한 패키지 목록
│── README.md             # 리포지토리 소개 및 가이드
```

## 🚀 시작하기

### 1️⃣ 환경 설정
이 저장소를 활용하려면 Python 환경이 필요합니다. 다음 명령어를 실행하여 필요한 패키지를 설치하세요.

```bash
# 저장소 클론
git clone https://github.com/MartinusChoi/RAG-PlayGround.git
cd RAG-PlayGround/LangChain-Tutorial

# 필수 패키지 설치
pip install -r requirements.txt
```

### 2️⃣ LangChain 설치
LangChain을 설치하려면 다음 명령어를 실행하세요.

```bash
pip install langchain langchain-openai
```

또한, 특정 실습에서는 추가적인 패키지가 필요할 수 있습니다. 필요 시 `requirements.txt`를 업데이트하여 설치하세요.

## 🔗 참고 자료
- [LangChain 공식 문서](https://python.langchain.com/docs/introduction/)
- [TeddyNote LangChain-KR GitHub Repository](https://github.com/teddylee777/langchain-kr)
- [OpenAI API 문서](https://platform.openai.com/docs/)