<p align='center'>
    <image src='https://github.com/user-attachments/assets/fafbac18-c808-412e-a29d-9c1e85d9c2cb'>
</p>

## 📖 소개
LangChain은 LLM (Large Language Models) 기반 애플리케이션을 쉽고 효율적으로 구축할 수 있도록 돕는 프레임워크입니다. 이 리포지토리는 LangChain의 핵심 개념을 단계적으로 학습하고, 실습을 통해 개념을 이해하는 것을 목표로 합니다.

이 저장소에서는 **LangChain의 주요 기능**과 **실제 활용 예제**를 다루며, 각 주제별 폴더에 코드와 설명을 정리합니다.

## 📂 폴더 구조

```
LangChain-Tutorial/
│── 00-Introduction/      # LangChain 기본 개념 및 설치
│── 01-PromptEngineering/ # 프롬프트 엔지니어링 기법
│── 02-Chains/            # LangChain Chains 개념 및 활용
│── 03-Memory/            # 대화 상태 및 메모리 활용
│── 04-Agents/            # LangChain Agents 이해 및 실습
│── 05-Tools/             # LangChain에서 제공하는 다양한 도구 활용
│── 06-VectorStores/      # 벡터 저장소 및 검색 기능 활용
│── 07-LLMEvaluation/     # LLM 평가 및 디버깅 방법
│── 08-Applications/      # LangChain을 활용한 실제 프로젝트 예제
│── requirements.txt      # 프로젝트 실행에 필요한 패키지 목록
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
pip install langchain openai
```

또한, 특정 실습에서는 추가적인 패키지가 필요할 수 있습니다. 필요 시 `requirements.txt`를 업데이트하여 설치하세요.

## 🏗 학습 내용

### 📌 1. LangChain 기본 개념 익히기
- LangChain이란 무엇인가?
- 핵심 개념 (Prompt Templates, Chains, Memory, Agents 등)
- 간단한 예제 실습

### 📌 2. 주요 기능 학습 및 실습
- **Prompt Engineering:** 효과적인 프롬프트 작성 방법
- **Chains:** LLM과의 인터랙션을 관리하는 체인 구성
- **Memory:** 대화형 애플리케이션을 위한 메모리 활용
- **Agents:** 동적 태스크 수행을 위한 LangChain Agents
- **VectorStores:** 문서 검색 및 RAG (Retrieval-Augmented Generation) 구현
- **LLM 평가:** 모델 성능을 평가하고 디버깅하는 방법

### 📌 3. 실제 프로젝트 구현
- LLM 기반 챗봇 만들기
- PDF 및 문서 요약 시스템 구축
- LangChain을 활용한 데이터 분석 및 자동화

## 🔗 참고 자료
- [LangChain 공식 문서](https://python.langchain.com/docs/introduction/)
- [TeddyNote LangChain-KR GitHub Repository](https://github.com/teddylee777/langchain-kr)
- [OpenAI API 문서](https://platform.openai.com/docs/)