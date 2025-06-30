# 📚 TIL (Today I Learned)

> 매일 배운 내용을 기록하고 정리하는 저장소입니다.

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FLeeHonggii%2FTIL&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

## 🎯 목표
- 매일 학습한 내용을 체계적으로 정리
- 지속적인 성장과 발전
- 나중에 쉽게 찾아볼 수 있는 개인 지식 저장소 구축

## 📂 카테고리별 정리

### 🦜 LangChain
LangChain 프레임워크와 관련된 학습 내용을 정리합니다.

| 제목 | 설명 | 
|------|------|
| [LangChain Runnable Components](https://github.com/LeeHonggii/TIL/tree/main/By-Topic/LangChain/LangChain_Runnable_Components.ipynb) | Runnable 컴포넌트의 기본 개념과 활용법 |
| [LCEL Interface Methods](https://github.com/LeeHonggii/TIL/tree/main/By-Topic/LangChain/LCEL_Interface_Methods.ipynb) | LangChain Expression Language 인터페이스 메소드 |
| [RunnableLambda와 PromptTemplate 활용법](https://github.com/LeeHonggii/TIL/tree/main/By-Topic/LangChain/RunnableLambda_and_PromptTemplate.ipynb) | RunnableLambda로 함수 통합 및 PromptTemplate 활용 |
| [Prompt Templates and Hub](https://github.com/LeeHonggii/TIL/tree/main/By-Topic/LangChain/Prompt_Templates_and_Hub.ipynb) | YAML 기반 템플릿, ChatPromptTemplate, MessagePlaceholder, FewShot 프롬프트, Example Selector, LangChain Hub 활용법 |
| [RAG Basic](https://github.com/LeeHonggii/TIL/tree/main/By-Topic/LangChain/RAG_Basic.ipynb) | PDF 문서 로드, 텍스트 분할, 임베딩, 벡터 저장, 검색기를 활용한 RAG 구현 |
| [Output Parsers - PydanticOutputParser](https://github.com/LeeHonggii/TIL/tree/main/By-Topic/LangChain/Output_parsers.ipynb) | LLM 출력을 구조화된 형태로 변환하는 PydanticOutputParser 활용법 |
| [CommaSeparatedListOutputParser 활용법](https://github.com/LeeHonggii/TIL/tree/main/By-Topic/LangChain/CommaSeparatedListOutputParser.ipynb) | LLM 출력을 쉼표로 구분된 리스트 형태로 파싱하는 방법 |
| [JsonOutputParser 활용법](https://github.com/LeeHonggii/TIL/tree/main/By-Topic/LangChain/JsonOutputParser.ipynb) | 딕셔너리 형태의 구조화된 출력을 위한 StructuredOutputParser와 JSON 스키마 기반 JsonOutputParser 사용법 |
| [FrameOutputParser](https://github.com/LeeHonggii/TIL/tree/main/By-Topic/LangChain/DataFrameOutputParser.ipynb) | DataFrame 쿼리, 날짜시간 파싱, Enum 값 파싱을 위한 특수 OutputParser 활용법 |
| [LLM Models and Caching](https://github.com/LeeHonggii/TIL/tree/main/By-Topic/LangChain/LLM_Models.ipynb) | OpenAI, Anthropic, Cohere 등 다양한 LLM 모델 활용법과 캐싱 기능 구현 |
| [Model Serialization and Chain Storage](https://github.com/LeeHonggii/TIL/tree/main/By-Topic/LangChain/Model_Serialization.ipynb) | LangChain 모델과 체인의 직렬화(dumps, dumpd) 및 저장(pickle, json) 방법 |
| [ChatOllama 로컬 LLM 활용법](https://github.com/LeeHonggii/TIL/tree/main/By-Topic/LangChain/ChatOllama_Local_LLM_Tutorial.ipynb) | Ollama를 사용한 로컬 LLM 구동 및 멀티모달 모델 활용 |
| [Conversation Memory Types](https://github.com/LeeHonggii/TIL/tree/main/By-Topic/LangChain/Conversation_Memory.ipynb) | LangChain의 다양한 메모리 타입 (ConversationBufferMemory, WindowMemory, TokenBufferMemory, EntityMemory, KGMemory, SummaryMemory, VectorStoreRetrieverMemory) 활용법 |
| [LCEL Memory Integration](https://github.com/LeeHonggii/TIL/tree/main/By-Topic/LangChain/LCEL_Memory.ipynb) | LCEL 체인에 ConversationBufferMemory를 통합하여 대화 내용을 기억하는 방법 |
| [SQLChatMessageHistory Tutorial](https://github.com/LeeHonggii/TIL/tree/main/By-Topic/LangChain/SQLChatMessageHistory_Tutorial.ipynb) | SQLAlchemy를 활용한 데이터베이스 기반 대화 기록 저장 및 다중 사용자/세션 관리 |
| [PDF Document Loaders](https://github.com/LeeHonggii/TIL/tree/main/By-Topic/LangChain/PDF_Document_Loaders.ipynb) | PyPDF, PyMuPDF, Unstructured, PyPDFium2 등 다양한 PDF 로더의 특징과 활용법 |
| [CSV Document Loaders](https://github.com/LeeHonggii/TIL/tree/main/By-Topic/LangChain/CSV_Document_Loaders.ipynb) | CSVLoader, UnstructuredCSVLoader, DataFrameLoader를 활용한 CSV 파일 처리 방법 |
| [WebBaseLoader Tutorial](https://github.com/LeeHonggii/TIL/tree/main/By-Topic/LangChain/WebBaseLoader_Tutorial.ipynb) | 웹 페이지 스크래핑, BeautifulSoup 파싱, 비동기 로드, 프록시 설정 등 WebBaseLoader 활용법 |
| [DirectoryLoader로 디렉토리 문서 로드하기](https://github.com/LeeHonggii/TIL/tree/main/By-Topic/LangChain/DirectoryLoader_Tutorial.ipynb) | DirectoryLoader를 사용한 디렉토리 파일 일괄 로드, 와일드카드 패턴, 커스텀 로더 클래스 활용법 |
| [UpstageLayoutAnalysisLoader로 문서 레이아웃 분석](https://github.com/LeeHonggii/TIL/tree/main/By-Topic/LangChain/UpstageLayoutAnalysisLoader_Tutorial.ipynb) | Upstage AI의 문서 레이아웃 분석 도구를 활용한 구조적 문서 분석 및 OCR 처리 |
| [LlamaParser로 고급 문서 파싱](https://github.com/LeeHonggii/TIL/tree/main/By-Topic/LangChain/LlamaParser_Document_Parsing.ipynb) | LlamaIndex의 LlamaParse를 활용한 고급 문서 파싱, 멀티모달 모델 활용, 맞춤형 파싱 지시 |
| [RecursiveCharacterTextSplitter로 텍스트 청크 분할](https://github.com/LeeHonggii/TIL/tree/main/By-Topic/LangChain/RecursiveCharacterTextSplitter_Tutorial.ipynb) | RecursiveCharacterTextSplitter를 사용한 의미론적 텍스트 분할, 청크 크기 및 중복 설정 방법 |

### 🔜 Coming Soon
- **Java** - Java 프로그래밍 관련 내용
- **Spring** - Spring Framework 학습 내용
- **Python** - Python 프로그래밍 및 라이브러리
- **Algorithm** - 알고리즘 및 자료구조
- **Database** - 데이터베이스 관련 학습

## 🛠️ 기술 스택
현재 학습 중인 주요 기술들:

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-121212?style=for-the-badge&logo=chainlink&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

## 📝 작성 규칙
1. **매일 꾸준히** - 작은 내용이라도 매일 기록
2. **카테고리별 정리** - 주제별로 폴더를 나누어 체계적으로 관리
3. **실습 코드 포함** - 이론과 함께 실제 동작하는 코드 예제 포함
4. **Jupyter Notebook 활용** - 코드와 설명을 함께 볼 수 있도록 .ipynb 형식 사용

## 🌟 학습 철학
> "작은 걸음이 모여 큰 여정이 된다"

매일 조금씩이라도 새로운 것을 배우고, 배운 것을 정리하며 성장합니다.

## 📊 통계
- 총 학습 일수: 진행 중
- 작성된 문서: 3개
- 다룬 주제: 1개 (LangChain)

## 🔗 유용한 링크
- [LangChain 공식 문서](https://python.langchain.com/docs/get_started/introduction)

---

### 💬 Contact
질문이나 제안사항이 있으시면 언제든 연락주세요!

⭐ 이 저장소가 도움이 되었다면 Star를 눌러주세요!