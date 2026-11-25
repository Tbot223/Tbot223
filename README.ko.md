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

한국에서 독학으로 개발하는 고등학생입니다. 주로 **Python과 Go**를 사용하며, 재사용 가능한 Python 라이브러리부터 실시간 금융시장 시뮬레이션까지 규모가 커져도 예측 가능한 시스템을 만드는 일을 좋아합니다.

작은 아이디어로 시작했다가 내부 구조가 궁금해져서 처음 계획보다 훨씬 큰 시스템을 설계하게 되는 일이 흔합니다.

[포트폴리오](https://tbot223.github.io/) · [GitHub 저장소](https://github.com/Tbot223?tab=repositories)

> 답장이 빨리 필요하면 인스타그램이 제일 빠릅니다.

---

## 🔭 요즘 관심 있는 것

`시스템 설계` · `백엔드 엔지니어링` · `시뮬레이션` · `동시성` · `API 계약` · `성능`

실패 경로가 명확하고, 시스템 경계가 분명하며, 측정에 기반해 최적화할 수 있는 구조를 선호합니다. 어려운 문제를 해결하는 것을 좋아하지만, 복잡성이 필요한 곳에만 복잡성을 두려고 합니다.

## 🚀 주요 프로젝트

### 오픈소스 라이브러리

| 프로젝트 | 설명 | 상태 |
|---|---|---|
| [`tbot223-core`](https://github.com/Tbot223/tbot223-core) | 명시적인 작업 결과, 파일 입출력, 로깅, 병렬 실행, 다국어 지원을 제공하는 외부 의존성 없는 Python 툴킷. | [PyPI 배포](https://pypi.org/project/tbot223-core/) |
| [`tbot223-base`](https://github.com/Tbot223/tbot223-base) | 시스템 경계에서 명시적인 작업 결과와 외부 공개에 안전한 오류 데이터를 전달하는 작은 Python 패키지. | 알파 재구축 중, 프로덕션 사용 비권장 |

<details>
<summary>라이브러리 상세 소개</summary>

**tbot223-core**는 Python 3.10–3.14를 지원합니다. 원자적 파일 쓰기, 파일 잠금, 구조화된 로깅, 예외 진단, 스레드·프로세스 풀 래퍼, 공유 메모리 IPC 등을 제공하며 명시적인 `Result` 계약을 중심으로 설계했습니다.

**tbot223-base**는 더 작은 범위에 집중합니다. 성공·실패·취소를 표현하는 타입 기반 결과 구조와 내부 예외 진단 정보 및 외부 공개용 오류 데이터의 분리를 제공합니다. 현재 재구축에서는 계약의 정확성과 안전성을 중점적으로 다루고 있습니다.

```bash
pip install tbot223-core
```

</details>

### 금융시장 시뮬레이션

#### Stock Game · 1세대

Python과 Flask로 개발하고 실제 웹 게임으로 배포했던 실시간 시장 시뮬레이션입니다. 규칙 기반 시장 동학, 거시경제 이벤트, 시장 심리, 섹터별 동작을 활용해 주식·원자재·암호화폐 시장을 모사합니다.

실시간 데이터 스트리밍과 인터랙티브 다이어그램 뷰어를 포함한 한국어·영어 플레이어 위키도 구현했습니다.

**기술 스택:** Python · Flask · JavaScript · SSE

*소스 저장소는 비공개입니다.*

#### 차세대 시장 시뮬레이터 · 개발 중

Go 기반의 후속 프로젝트로, 경제 시뮬레이션에 시장 미시구조를 결합하고 플레이어가 가격 형성에 더 직접적으로 참여할 수 있는 구조를 개발하고 있습니다.

주문 매칭, 유동성, 거시경제 모델링, 위험 관리, 재현 가능한 시뮬레이션 동작에 집중하고 있습니다. 일부 기능은 아직 개발 또는 검증 단계입니다.

**기술 스택:** Go · TypeScript · Next.js · PostgreSQL · Docker

*소스 저장소는 비공개이며 아직 공개 출시하지 않았습니다.*

### 기타 프로젝트

- [`playground`](https://github.com/Tbot223/playground) : 작은 실험, 학습 기록, 프로토타입.
- [`tbot223.github.io`](https://github.com/Tbot223/tbot223.github.io) : HTML, CSS, JavaScript로 구현한 다국어 개인 포트폴리오.

---

## 🛠️ Tech & Tools

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="Go" src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white">
  <img alt="Rust" src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black">
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white">
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">
  <img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black">
  <img alt="VSCode" src="https://img.shields.io/badge/VSCode-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white">
  <img alt="Zed" src="https://img.shields.io/badge/Zed-084CCF?style=flat-square&logo=zedindustries&logoColor=white">
</p>

---

## 🎯 개발할 때 중요하게 생각하는 것

| | |
|---|---|
| **안정성 우선** | 실패 경로부터 설계하고 작업 결과를 명시적으로 표현합니다. |
| **명확한 계약** | 인터페이스를 예측 가능하게 유지하고 약속한 동작을 검증합니다. |
| **측정 기반 성능 개선** | 추측보다 프로파일링과 벤치마크를 통해 병목을 찾습니다. |
| **유지보수성** | 불필요한 추상화보다 명확한 경계와 유용한 문서를 선호합니다. |
| **호기심 중심 학습** | 직접 만들고, 가정을 검증하고, 다른 코드를 읽으며 반복적으로 개선합니다. |

제 프로젝트 외에도 다른 개발자와 기술적인 문제를 논의하고 설계 피드백을 제공하는 것을 좋아합니다.

> 공개 프로젝트의 Issue와 PR은 언제든 환영합니다.

---

## 📊 GitHub Stats

<p align="center">
  <img alt="Tbot223의 GitHub 통계" src="https://github-readme-stats.vercel.app/api?username=Tbot223&show_icons=true&include_all_commits=true&count_private=true&hide=issues&hide_border=true&theme=tokyonight&border_radius=12&locale=ko" width="48%">
  <img alt="주요 언어" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Tbot223&layout=compact&hide=cs&hide_border=true&theme=tokyonight&border_radius=12&locale=ko" width="48%">
</p>
