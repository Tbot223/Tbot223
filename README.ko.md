<!-- markdownlint-disable MD033 MD041 -->
# 안녕하세요, Tbot223입니다 👋

<p align="right">
  <a href="./README.md">English</a> · <b>한국어</b>
</p>

<p align="center">
  <a href="mailto:tbotxyz@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-tbotxyz%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white"></a>
  <a href="https://instagram.com/_hxun.s"><img alt="Instagram" src="https://img.shields.io/badge/Instagram-%40__hxun.s-E4405F?style=flat-square&logo=instagram&logoColor=white"></a>
  <a href="https://linkedin.com/in/hyunseung-song-a196213b0"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="https://pypi.org/project/tbot223-core/"><img alt="PyPI" src="https://img.shields.io/pypi/v/tbot223-core?style=flat-square&logo=pypi&logoColor=white&label=tbot223-core"></a>
</p>

뭔가 만드는 걸 좋아하는 한국 고등학교 2학년입니다.
주로 Python을 쓰고, 요즘은 Rust도 깨작거리고 있어요.
빠르게 만드는 편은 아니지만, 만들 거면 오래 쓸 수 있게 만들고 싶어서
같은 프로젝트를 서너 번씩 다시 짜는 일도 흔합니다. 🚀

> 답장이 빨리 필요하면 인스타그램이 제일 빠릅니다.

---

## 🔭 요즘 관심 있는 것

`시스템 설계` · `클린 아키텍처` · `에러 핸들링` · `i18n` · `AI`

거창한 건 아니고, 프로젝트가 커져도 코드가 읽히고 예측 가능한 상태로
남으려면 어떻게 짜야 하는지 고민하는 걸 좋아합니다.

---

## 🚀 만든 것들

### [`tbot223-core`](https://github.com/Tbot223/Core)

Python 3.10 ~ 3.14에서 돌아가는, **외부 의존성이 없는** 작은 유틸리티 라이브러리입니다.

매번 같은 보일러플레이트를 다시 짜는 게 지겨워서, 자주 쓰던 패턴들을 한곳에 모아 둔 거예요.
영향을 많이 받은 건 Rust의 `Result` 패턴이고, 그래서 곳곳에 `try/except`를 흩뿌리는 것보다
에러를 명시적으로 반환하는 쪽을 선호합니다.

**들어 있는 것**

- **AppCore** — Thread/Process Pool 래퍼, 콘솔·CLI 헬퍼, 다국어 지원
- **FileManager** — 원자적 쓰기, 파일 잠금, 안전한 JSON 입출력
- **LogSys** — 타임스탬프 기반 구조화된 로깅
- **Utils** — `GlobalVars`(스레드 안전 전역 변수 + 공유 메모리 IPC), `DecoratorUtils`, PBKDF2, 경로 유틸
- **Result / ExceptionTracker** — 표준화된 반환 타입과 풍부한 예외 컨텍스트

```bash
pip install tbot223-core
```

<details>
<summary>📝 간단한 예시</summary>

```python
from tbot223_core import AppCore, FileManager

app = AppCore.AppCore(is_logging_enabled=True)
fm = FileManager.FileManager()

fm.write_json("config.json", {"key": "value"})

tasks = [(my_func, {"arg": i}) for i in range(10)]
results = app.thread_pool_executor(tasks, workers=4)
```

</details>

### [`playground`](https://github.com/Tbot223/playground)

이름 그대로 놀이터입니다. 따로 레포를 팔 만큼은 아닌 아이디어들이 모여 있어요. 🧪🦀

- **`PYTHON/CountWord`** — 연습 삼아 만들었다가 의외로 쓸만해진 작은 단어 카운터
- **`PYTHON/legacy`** — `tbot223-core`의 옛 버전들과 잡다한 실험들. 지난 흔적을 남겨두는 용도
- **`RUST/start`** — Rust 입문 작업. 느리지만 꽤 재밌습니다

### [`tbot223.github.io`](https://github.com/Tbot223/tbot223.github.io)

다국어를 지원하는 개인 포트폴리오 사이트. 별다른 프레임워크 없이 HTML / CSS / JS로 만들었습니다.

---

## 🛠️ Tech & Tools

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="Rust" src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black">
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white">
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white">
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">
  <img alt="VSCode" src="https://img.shields.io/badge/VSCode-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white">
  <img alt="Zed" src="https://img.shields.io/badge/Zed-084CCF?style=flat-square&logo=zedindustries&logoColor=white">
</p>

---

## 🎯 잡담 같은 자기소개

|  |  |
|---|---|
| 🛠️ **에디터** | VSCode와 Zed를 기분 따라 골라 씁니다 |
| 💻 **OS** | 그날 책상 위에 있는 거 — Windows, Linux, macOS 다 씁니다 |
| ⏰ **코딩 시간** | 거의 새벽 🌙 |
| 📚 **학습 방법** | 거의 독학, 거의 다른 사람 코드 읽기 |
| 🎯 **신경 쓰는 것** | 안정성, 성능, 그리고 뭔가를 부수지 않는 것 |
| 🍿 **이게 없으면 안 됨** | 간식, 음악, 그리고 그날의 호기심 |

> 💬 Issue와 PR 언제든 환영합니다. 부담 갖지 마세요.

---

## 📊 GitHub Stats

<p align="center">
  <img alt="Tbot223의 GitHub 통계" src="https://github-readme-stats.vercel.app/api?username=Tbot223&show_icons=true&include_all_commits=true&count_private=true&hide=issues&hide_border=true&theme=tokyonight&border_radius=12&locale=ko" width="48%">
  <img alt="주요 언어" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Tbot223&layout=compact&hide=cs&hide_border=true&theme=tokyonight&border_radius=12&locale=ko" width="48%">
</p>
