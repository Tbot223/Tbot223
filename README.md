### Hi there! 👋

I'm a high school student (11th grade in Korea) aspiring to be a developer. I mainly work with Python.

I love building things, experimenting with ideas, and learning from mistakes. Still on the journey! 🚀

📫 **Contact:**
- Email: tbotxyz@gmail.com
- Instagram: [@_hxun.s](https://instagram.com/_hxun.s) (faster response here!)

🔭 **Interests:** AI, System Design, Clean Architecture

---

### 🚀 Main Projects

#### [tbot223-core](https://github.com/Tbot223/Core)
A comprehensive utility package for Python applications.

Why I built it:
- Tired of writing the same boilerplate code in every module
- Wanted to build something properly, once and for all

What it supports (evolved along the way):
- ✅ Thread-safe global state management
- ✅ Parallel task execution made simple
- ✅ Production-ready file operations
- ✅ Detailed exception tracking

Key features:
- **AppCore** — Parallel execution (Thread/Process Pool), console management, multi-language support, CLI input validation
- **FileManager** — Atomic file writing, JSON read/write, safe file management
- **LogSys** — Structured logging system
- **Utils** — Path conversion, encryption, PBKDF2, and includes:
  - `GlobalVars` — Thread-safe global variables + Shared memory IPC
  - `DecoratorUtils` — Runtime measurement, function-to-decorator converter
- **Result** — Standardized return object for all operations
- **ExceptionTracker** — Detailed exception tracking with system info

```bash
pip install tbot223-core
```

<details>
<summary>📝 Quick Example</summary>

```python
from tbot223_core import AppCore, FileManager

# Initialize
app = AppCore.AppCore(is_logging_enabled=True)
fm = FileManager.FileManager()

# Safe JSON write
fm.write_json("config.json", {"key": "value"})

# Parallel execution
tasks = [(my_func, {"arg": i}) for i in range(10)]
results = app.thread_pool_executor(tasks, workers=4)
```

</details>

---

#### [playground](https://github.com/Tbot223/playground)
My personal sandbox for chaos and creativity. Testing ideas before they become real projects. 🧪

What lives here:
- **CountWord** — A tiny utility that counts words (started as a coding exercise, now genuinely useful)
- **legacy/Core** — Previous iterations of tbot223-core (learning history)
- **legacy/Cooooode** — Random experiments: number baseball game, typewriter effects, you name it

<details>
<summary>📝 CountWord Example</summary>

```python
from Scripts.CountWord import CountWord

cw = CountWord(is_logging_enabled=False)
result = cw.count_words_in_file("example.txt")
print(f"Word count: {result.data}")
```

</details>

---

### 🎯 About Me

| | |
|---|---|
| 🎵 **Currently listening** | 어제보다 슬픈 오늘 - 우디 (Woody) |
| 🛠️ **Dev environment** | VSCode + Windows (I prefer what most people use!) |
| ⏰ **Coding hours** | Mostly late night 🌙 |
| 📚 **How I learn** | Self-taught + reading others' code |
| 🎯 **What I value** | Stability, Performance, Compatibility |
| 🍿 **Coding essentials** | Snacks, Music, and Curiosity (can't code without these!) |
| 😴 **School life** | I sleep all the time, I like sleep more than studying~ (oops) |

> 💬 Issues and PRs are always welcome!

---

<details>
<summary>🇰🇷 한국어</summary>

### 안녕하세요! 👋

고등학교 2학년 개발자 지망생입니다. Python을 주력으로 사용합니다.

저는 뭔가를 만들고, 아이디어를 실험하고, 실수에서 배우는 걸 좋아합니다. 아직도 배우는 중! 🚀

📫 **연락처:**
- 이메일: tbotxyz@gmail.com
- 인스타그램: [@_hxun.s](https://instagram.com/_hxun.s) (이메일보다 인스타를 잘 봐요!)

🔭 **관심 기술:** AI, 시스템 설계, 클린 아키텍처

---

### 🚀 주요 프로젝트

#### [tbot223-core](https://github.com/Tbot223/Core)
Python 애플리케이션을 위한 종합 유틸리티 패키지입니다.

만든 이유:
- 반복되는 코드를 모듈마다 만들기 귀찮았음
- 만들 거면 제대로 만들고 싶었음

지원하는 기능 (만들다 보니 됨):
- ✅ 스레드 안전 전역 상태 관리
- ✅ 병렬 작업 실행 간단하게
- ✅ 프로덕션 레벨의 파일 작업
- ✅ 상세한 예외 추적

주요 기능:
- **AppCore** — 병렬 실행(Thread/Process Pool), 콘솔 관리, 다국어 지원, CLI 입력 검증
- **FileManager** — 원자적 파일 쓰기, JSON 읽기/쓰기, 안전한 파일 관리
- **LogSys** — 구조화된 로깅 시스템
- **Utils** — 경로 변환, 암호화, PBKDF2, 그리고:
  - `GlobalVars` — 스레드 안전 전역 변수 + 공유 메모리 IPC
  - `DecoratorUtils` — 런타임 측정, 함수-데코레이터 변환기
- **Result** — 모든 작업의 표준화된 반환 객체
- **ExceptionTracker** — 상세한 예외 추적 및 시스템 정보 수집

```bash
pip install tbot223-core
```

<details>
<summary>📝 간단 예시</summary>

```python
from tbot223_core import AppCore, FileManager

# 초기화
app = AppCore.AppCore(is_logging_enabled=True)
fm = FileManager.FileManager()

# 안전한 JSON 쓰기
fm.write_json("config.json", {"key": "value"})

# 병렬 실행
tasks = [(my_func, {"arg": i}) for i in range(10)]
results = app.thread_pool_executor(tasks, workers=4)
```

</details>

---

#### [playground](https://github.com/Tbot223/playground)
아이디어를 테스트하고 혼돈과 창의력이 공존하는 개인의 모래상자. 🧪

여기 있는 것들:
- **CountWord** — 단어를 세는 작은 유틸리티 (코딩 연습에서 시작, 이제 실제로 유용함)
- **legacy/Core** — tbot223-core의 이전 버전들 (학습 역사)
- **legacy/Cooooode** — 랜덤 실험: 숫자야구, 타이핑 효과, 기타 등등

<details>
<summary>📝 CountWord 예시</summary>

```python
from Scripts.CountWord import CountWord

cw = CountWord(is_logging_enabled=False)
result = cw.count_words_in_file("example.txt")
print(f"단어 수: {result.data}")
```

</details>

---

### 🎯 나에 대해

| | |
|---|---|
| 🎵 **요즘 듣는 노래** | 어제보다 슬픈 오늘 - 우디 |
| 🛠️ **개발 환경** | VSCode + Windows (많은 사람들이 쓰는 환경 선호!) |
| ⏰ **코딩 시간** | 주로 새벽 🌙 |
| 📚 **학습 방법** | 독학 + 다른 사람 코드 리뷰 |
| 🎯 **중요하게 생각하는 것** | 안정성, 성능, 호환성 |
| 🍿 **코딩할 때 필수** | 간식, 음악, 그리고 흥미 (이게 없으면 코딩 못함) |
| 😴 **학교 생활** | 맨날 잠만 잠, 공부보다 잠이 더 좋아~(ㅎㅎ) |

> 💬 Issue랑 PR 환영합니다!

</details>

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Tbot223&bg_color=30,FF7F50,FF69B4&title_color=fff&text_color=fff&include_all_commits=true&show_icons=true&hide=issues&hide_border=true&count_private=true&line_height=30&border_radius=15" alt="Tbot223's github stats" width="400"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Tbot223&layout=compact&bg_color=30,FF7F50,FF69B4&title_color=fff&hide=cs&text_color=fff&hide_border=true&card_width=400&border_radius=12" alt="Top Langs" width="400"/>
</p>
