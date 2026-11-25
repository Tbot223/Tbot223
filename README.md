<!-- markdownlint-disable MD033 MD041 -->
# Hi, I'm Tbot223 👋

<p align="right">
  <b>English</b> · <a href="./README.ko.md">한국어</a>
</p>

<p align="center">
  <a href="mailto:tbotxyz@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-tbotxyz%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white"></a>
  <a href="https://instagram.com/_hxun.s"><img alt="Instagram" src="https://img.shields.io/badge/Instagram-%40__hxun.s-E4405F?style=flat-square&logo=instagram&logoColor=white"></a>
  <a href="https://linkedin.com/in/hyunseung-song-a196213b0"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="https://pypi.org/project/tbot223-core/"><img alt="PyPI" src="https://img.shields.io/pypi/v/tbot223-core?style=flat-square&logo=pypi&logoColor=white&label=tbot223-core"></a>
</p>

I'm a self-taught high school developer in Korea, mainly working with **Python and Go**. I enjoy building systems that remain predictable as they grow, from reusable Python libraries to real-time financial market simulations.

I tend to start with a small idea, get curious about how the underlying system works, and end up designing something much bigger than I originally planned.

[Portfolio](https://tbot223.github.io/) · [GitHub repositories](https://github.com/Tbot223?tab=repositories)

> If you want a quick reply, Instagram is the best place to find me.

---

## 🔭 What I'm into

`System Design` · `Backend Engineering` · `Simulation` · `Concurrency` · `API Contracts` · `Performance`

I care about explicit failure paths, clear system boundaries, and measured optimization. I enjoy solving difficult problems, but I also try to keep complexity where it actually belongs.

## 🚀 Selected projects

### Open-source libraries

| Project | Description | Status |
|---|---|---|
| [`tbot223-core`](https://github.com/Tbot223/tbot223-core) | Zero-dependency Python toolkit for predictable operation results, file I/O, logging, parallel execution, and localization. | [Published on PyPI](https://pypi.org/project/tbot223-core/) |
| [`tbot223-base`](https://github.com/Tbot223/tbot223-base) | A small Python package for explicit operation outcomes and public-safe error payloads across system boundaries. | Alpha rebuild; not recommended for production |

<details>
<summary>More about the libraries</summary>

**tbot223-core** supports Python 3.10–3.14. Its features include atomic file writes, file locking, structured logging, exception diagnostics, thread/process pool wrappers, and shared-memory IPC. The explicit `Result` contract is central to its design.

**tbot223-base** focuses on a smaller scope: typed success, failure, and cancellation results, with a clear separation between internal exception diagnostics and public-safe error data. Its current rebuild emphasizes contract accuracy and safety.

```bash
pip install tbot223-core
```

</details>

### Financial market simulation

#### Stock Game · First generation

A previously deployed browser-based market simulation built with Python and Flask. It simulates stocks, commodities, and cryptocurrencies using rule-based market dynamics, macroeconomic events, sentiment, and sector behavior.

The project also includes real-time data streaming and a bilingual player wiki with an interactive diagram viewer.

**Stack:** Python · Flask · JavaScript · SSE

*Source repository is private.*

#### Next-generation market simulator · In development

A Go-based successor that extends the economic simulation with market microstructure and more direct player participation in price formation.

The project focuses on order matching, liquidity, macroeconomic modeling, risk controls, and reproducible simulation behavior. Some features are still being developed or validated.

**Stack:** Go · TypeScript · Next.js · PostgreSQL · Docker

*Source repository is private; not publicly released.*

### Other projects

- [`playground`](https://github.com/Tbot223/playground) : Small experiments, learning history, and prototypes.
- [`tbot223.github.io`](https://github.com/Tbot223/tbot223.github.io) : A bilingual personal portfolio built with plain HTML, CSS, and JavaScript.

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

## 🎯 How I build

| | |
|---|---|
| **Stability first** | Design for failure paths and make operation outcomes explicit. |
| **Clear contracts** | Keep interfaces predictable and verify the behavior they promise. |
| **Measured performance** | Find bottlenecks through profiling and benchmarks rather than assumptions. |
| **Maintainable systems** | Prefer clear boundaries and useful documentation over unnecessary abstraction. |
| **Curiosity-driven learning** | Learn by building, testing assumptions, reading code, and iterating. |

Outside of my own projects, I enjoy discussing technical problems and providing design feedback to other developers.

> Issues and PRs are welcome on my public projects.

---

## 📊 GitHub Stats

<p align="center">
  <img alt="Tbot223's GitHub stats" src="https://github-readme-stats.vercel.app/api?username=Tbot223&show_icons=true&include_all_commits=true&count_private=true&hide=issues&hide_border=true&theme=tokyonight&border_radius=12" width="48%">
  <img alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Tbot223&layout=compact&hide=cs&hide_border=true&theme=tokyonight&border_radius=12" width="48%">
</p>
