# 📚 영어 본문 암기장 (English Text Memorizer)

중·고등학교 영어 본문 및 지문 암기를 효율적으로 돕는 Web 기반 암기 프로그램입니다.  
별도의 서버 설치 없이 `index.html` 단일 파일로 동작하며, PC와 모바일 환경 모두에 최적화되어 있습니다.

---

## ✨ 주요 기능

- **📖 전체 보기 (Read Mode)**: 문장별 원어민 TTS 발음 듣기 지원
- **🙈 단어 가리기 (Blank Mode)**: 
  - **Easy**: 문장당 핵심 단어 최대 3개 무작위 가림
  - **Normal**: 주요 어휘/긴 단어 위주 가림
  - **Hard**: 전체 단어 가림
  - **기타 기능**: [🔄 새로고침] 버튼으로 재암기 조합 생성, [👁️ 전체 공개] 버튼 제공
- **✍️ 암기 퀴즈 (Quiz Mode)**: 문장 단위 빈칸 채우기 및 실시간 타이핑 검증
- **🎙️ 음성 암기 (Speech Mode)**:
  - Web Speech API 기반 AI 음성 인식 지원
  - 3초간 입력이 없으면 인식된 텍스트 자동 초기화 로직 탑재
- **⚙️ 학습 편의 기능**: 튜토리얼(따라쓰기/따라말하기) 온오프 지원

---

## 🛠️ 기술 스택

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **APIs**: Web Speech API (`SpeechRecognition`), Web Speech Synthesis (`speechSynthesis`)
- **Storage**: Browser LocalStorage (설정값 저장)

---

## 🚀 시작하기

별도의 패키지 설치나 빌드 과정이 필요하지 않습니다.

1. 이 저장소를 클론(Clone)하거나 ZIP 파일로 다운로드합니다.
   ```bash
   git clone [https://github.com/사용자이름/저장소이름.git](https://github.com/사용자이름/저장소이름.git)
