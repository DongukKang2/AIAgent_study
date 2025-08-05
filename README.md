AI Agent Study 🤖
Google Colab에서 작업한 AI Agent 관련 연구 및 학습 자료를 정리한 저장소입니다.
📚 포함된 내용
1. Langchain Agent ([1]Langchain_Agent.ipynb)

Zero-shot ReAct: Wikipedia와 수학 문제 해결을 위한 도구 활용
Conversational ReAct: 대화형 에이전트와 메모리 기능
Self-ask with search: Tavily 검색을 활용한 자가 질문 에이전트
ReAct docstore: Wikipedia 문서 검색 및 조회 에이전트

2. AutoGPT Agent ([2]AutoGPT_Agent.ipynb)

AutoGPT 설치 및 설정
코드 멘토로 활용하는 방법

3. AutoGen Agent ([3]AutoGen_Agent.ipynb)

단일 에이전트: 소수 개수 계산 코드 생성
멀티 에이전트: 운동화 광고 전략 수립

디자인팀, 마케팅팀, PM 역할의 에이전트들이 협업
상태 전환을 통한 체계적인 대화 흐름



4. LlamaIndex Agent ([4]LlmaIndex_Agent.ipynb)

수학 계산을 위한 함수 도구 활용
PDF 문서 기반 Q&A 시스템 구축
임산부 운동 가이드 문서 질의응답

5. CrewAI Agent ([5]crewai_Agent.ipynb)

웹 검색 기반: Serper API를 활용한 데이터 검색 및 기사 작성
유튜브 분석: 특정 채널의 비디오 내용 분석 및 요약

🚀 사용 방법
1. 환경 설정
bash# 저장소 클론
git clone https://github.com/DongukKang2/AIAgent_study.git
cd AIAgent_study

# 환경변수 파일 설정
cp .env.example .env
2. API 키 설정
.env 파일을 열어 다음 API 키들을 입력하세요:
envOPENAI_API_KEY=sk-your-openai-api-key-here
SERPER_API_KEY=your-serper-api-key-here
TAVILY_API_KEY=tvly-your-tavily-api-key-here
3. 필요한 라이브러리 설치
각 노트북 파일의 첫 번째 셀에서 필요한 라이브러리를 설치할 수 있습니다:
python# 예시: Langchain 관련 라이브러리
!pip install langchain openai wikipedia langchain-community "httpx==0.27.2"
4. 노트북 실행
Jupyter Notebook 또는 Google Colab에서 원하는 .ipynb 파일을 열어 실행하세요.
🔑 필요한 API 키
서비스용도획득 방법OpenAIGPT 모델 사용OpenAI PlatformSerper구글 검색 APISerper.devTavily검색 도구Tavily AI
📋 주요 기능별 노트북 선택 가이드
원하는 기능추천 노트북특징기본 AI 에이전트[1]Langchain_Agent.ipynb가장 기본적이고 이해하기 쉬운 구조대화형 에이전트[3]AutoGen_Agent.ipynb여러 에이전트가 협업하는 시스템문서 기반 Q&A[4]LlmaIndex_Agent.ipynbPDF 문서를 활용한 질의응답웹 검색 에이전트[5]crewai_Agent.ipynb실시간 웹 정보를 활용한 콘텐츠 생성자율 에이전트[2]AutoGPT_Agent.ipynb독립적으로 작업을 수행하는 에이전트
🛠️ 기술 스택

Python: 주 개발 언어
Langchain: AI 에이전트 프레임워크
AutoGen: 멀티 에이전트 시스템
LlamaIndex: 문서 기반 AI 시스템
CrewAI: 협업 AI 에이전트
OpenAI GPT: 언어 모델
Jupyter Notebook: 개발 환경

📖 학습 순서 추천

[1]Langchain_Agent.ipynb - AI 에이전트 기본 개념 학습
[4]LlmaIndex_Agent.ipynb - 문서 기반 AI 시스템 이해
[3]AutoGen_Agent.ipynb - 멀티 에이전트 협업 시스템
[5]crewai_Agent.ipynb - 실제 업무에 활용 가능한 에이전트
[2]AutoGPT_Agent.ipynb - 고급 자율 에이전트

⚠️ 주의사항

API 키 보안: .env 파일은 절대 Git에 커밋하지 마세요
비용 관리: OpenAI API 사용량을 주기적으로 확인하세요
한국어 지원: 일부 모델은 한국어 성능이 제한적일 수 있습니다

🤝 기여 방법

Fork the repository
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request

📄 라이선스
이 프로젝트는 학습 목적으로 만들어졌습니다. 자유롭게 사용하고 수정하세요.
📞 문의
프로젝트에 대한 질문이나 제안사항이 있으시면 Issue를 생성해 주세요.

⭐ 이 저장소가 도움이 되었다면 Star를 눌러주세요!
