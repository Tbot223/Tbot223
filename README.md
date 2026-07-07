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

I'm a high schooler in Korea (12th grade) who really likes building things.
Mostly Python, with a bit of Rust on the side. I'm not the fastest learner,
but I try to make the things I build last — so I usually end up rewriting
them three or four times until I'm actually happy with them. 🚀

> If you want a quick reply, Instagram is the best place to find me.

---

## 🔭 What I'm into

`System Design` · `Clean Architecture` · `Error Handling` · `i18n` · `AI`

Nothing too flashy — I just enjoy thinking about how code stays readable
and predictable as a project grows.

---

## 🚀 Things I've built

### [`tbot223-core`](https://github.com/Tbot223/Core)

A small utility library for Python (3.10 – 3.14), with **zero dependencies**.

I got tired of writing the same boilerplate in every project, so I
collected the patterns I kept reaching for and put them in one place.
A lot of it is inspired by Rust's `Result` — I prefer returning errors
explicitly over `try/except` everywhere.

**What's inside**

- **AppCore** — Thread / Process pool wrappers, console & CLI helpers, i18n
- **FileManager** — Atomic writes, file locking, safe JSON I/O
- **LogSys** — Structured, timestamped logging
- **Utils** — `GlobalVars` (thread-safe globals + shared-memory IPC), `DecoratorUtils`, PBKDF2, path helpers
- **Result / ExceptionTracker** — A standard return type and richer exception context

```bash
pip install tbot223-core
```

<details>
<summary>📝 Quick example</summary>

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

My sandbox. This is where ideas go before they're worth their own repo. 🧪🦀

- **`PYTHON/CountWord`** — A tiny word counter that started as practice and somehow turned useful.
- **`PYTHON/legacy`** — Older versions of `tbot223-core` and small experiments I keep around as learning history.
- **`RUST/start`** — My first attempts at Rust. Slow going, but fun.

### [`tbot223.github.io`](https://github.com/Tbot223/tbot223.github.io)

My personal portfolio site. Plain HTML / CSS / JS with multilingual support.

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

## 🎯 A few things about me

|  |  |
|---|---|
| 🛠️ **Editors** | VSCode and Zed, depending on my mood |
| 💻 **OS** | Whatever's on the desk — Windows, Linux, or macOS |
| ⏰ **Coding hours** | Almost always late at night 🌙 |
| 📚 **How I learn** | Mostly self-taught, mostly by reading other people's code |
| 🎯 **What I care about** | Stability, performance, and not breaking things |
| 🍿 **Can't code without** | Snacks, music, and being curious about something |

> 💬 Issues and PRs are always welcome. Don't be shy.

---

## 📊 GitHub Stats

<p align="center">
  <img alt="Tbot223's GitHub stats" src="https://github-readme-stats.vercel.app/api?username=Tbot223&show_icons=true&include_all_commits=true&count_private=true&hide=issues&hide_border=true&theme=tokyonight&border_radius=12" width="48%">
  <img alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Tbot223&layout=compact&hide=cs&hide_border=true&theme=tokyonight&border_radius=12" width="48%">
</p>
