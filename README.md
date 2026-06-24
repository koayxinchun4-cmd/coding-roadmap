# From Zero to Dev — A GitHub-Powered Self-Learning Roadmap

> All resources are free, open-source, and hosted on GitHub. No paid courses needed.
> Every step includes: what to learn → which repo → how to start → what to build next.

---

## Your Starting Point

| You Already Know | Level |
|------------------|-------|
| SQL | Beginner (SELECT, WHERE, GROUP BY, JOIN basics) |
| Python | Beginner (wrote a bot, used APIs) |
| JavaScript | Beginner (tinkered with a fuel-bot) |
| Git | Beginner (clone, push, token usage) |
| Termux | Mobile dev environment |

---

## Phase 0: Set Up Your Tools (Do This First)

### 0.1 Master Git

Why first? Every new thing you learn gets committed to a repo. Git IS your learning journal.

| Step | Topic | Resource |
|------|-------|-----------|
| 1 | Clone, add, commit, push | You already do this |
| 2 | Branch, merge, pull, rebase | [git-tips](https://github.com/git-tips/tips) — cheat sheet, ⭐12K |
| 3 | `.gitignore` templates | [github/gitignore](https://github.com/github/gitignore) — official, ⭐165K |
| 4 | Git from the inside out | [pluralsight/git-internals-pdf](https://github.com/pluralsight/git-internals-pdf) — free book |
| 5 | Oh Shit, Git!?! | [ohshitgit](https://ohshitgit.com/) — fix common disasters |

### 0.2 Your Terminal (Termux)

```bash
pkg update && pkg upgrade -y
pkg install python nodejs git sqlite curl wget -y
pip install requests
npm install -g nodemon
```

### 0.3 Learn the Command Line

| Resource | Stars | Why |
|----------|-------|-----|
| [the-art-of-command-line](https://github.com/jlevy/the-art-of-command-line) | ⭐155K | One-page masterclass, English |
| [explainshell.com](https://explainshell.com/) | — | Paste any command, get line-by-line explanation |

---

## Phase 1: Algorithms — Learn 11 Languages at Once

### [hello-algo](https://github.com/krahets/hello-algo) ⭐107K

> Animated, interactive data structures & algorithms. Supports **Python, C++, Java, C#, Go, Swift, JS, TS, Dart, Rust, C, Zig** — all in one book.

**How to use it (30-day plan):**

| Week | Chapter | What You Get |
|------|---------|---------------|
| 1 | Arrays, Linked Lists, Stack, Queue | Foundation — compare syntax across 11 languages |
| 2 | Hash Table, Tree, Heap, Graph | Core data structures |
| 3 | Searching, Sorting, Divide & Conquer | Classic algorithms |
| 4 | Backtracking, DP, Greedy | Advanced thinking patterns |

**Pro tip:** Read the Python version first (it's the simplest), then click "Switch Language" to see how the same algorithm looks in JS, Go, or Rust. This builds cross-language fluency faster than any tutorial.

### Backup / Deeper Dive

| Repo | Stars | Best For |
|------|-------|----------|
| [TheAlgorithms/Python](https://github.com/TheAlgorithms/Python) | ⭐201K | Every algorithm implemented in Python |
| [TheAlgorithms/JavaScript](https://github.com/TheAlgorithms/JavaScript) | ⭐33K | Same, in JS |
| [TheAlgorithms/Go](https://github.com/TheAlgorithms/Go) | ⭐16K | Same, in Go |
| [CS-Notes](https://github.com/CyC2018/CS-Notes) | ⭐179K | CS fundamentals, Chinese + English |

---

## Phase 2: Pick One Language & Go Deep

> Based on your repos (Python bots + JS bots), you're already touching both. Pick Python as your **primary language** — it's the easiest to read, and you already have projects in it.

### Python — Your Primary Language

| Order | Resource | Stars | What You'll Learn |
|-------|----------|-------|-------------------|
| 1 | [30-Days-Of-Python](https://github.com/Asabeneh/30-Days-Of-Python) | ⭐44K | Day-by-day, from `print("hello")` to APIs |
| 2 | [wtfpython](https://github.com/satwikkansal/wtfpython) | ⭐36K | Python quirks explained (learn what NOT to do) |
| 3 | [python-patterns](https://github.com/faif/python-patterns) | ⭐41K | Design patterns in Python |
| 4 | [realpython/python-guide](https://github.com/realpython/python-guide) | ⭐28K | Best practices, packaging, deployment |
| 5 | [awesome-python](https://github.com/vinta/awesome-python) | ⭐237K | Curated list of libraries — your Python dictionary |

### JavaScript — Your Secondary Language

| Order | Resource | Stars | What You'll Learn |
|-------|----------|-------|-------------------|
| 1 | [javascript-algorithms](https://github.com/trekhleb/javascript-algorithms) | ⭐191K | Algorithms in JS, with explanations |
| 2 | [You-Dont-Know-JS](https://github.com/getify/You-Dont-Know-JS) | ⭐182K | Deep JS concepts, book series |
| 3 | [33-js-concepts](https://github.com/leonardomso/33-js-concepts) | ⭐65K | 33 core concepts every JS dev should know |
| 4 | [clean-code-javascript](https://github.com/ryanmcdermott/clean-code-javascript) | ⭐93K | Clean code principles for JS |

### SQL — Your Data Language

| Order | Resource | Stars | What You'll Learn |
|-------|----------|-------|-------------------|
| 1 | [SQL Tutorial (W3Schools)](https://www.w3schools.com/sql/) | — | Interactive, run SQL in browser |
| 2 | [sql-murder-mystery](https://github.com/NUKnightLab/sql-murder-mystery) | ⭐17K | Learn SQL by solving a crime |
| 3 | [SQL-for-Data-Analysis](https://github.com/ptyadana/SQL-Data-Analysis-and-Visualization-Projects) | — | Real-world queries |
| 4 | [awesome-db-tools](https://github.com/mgramin/awesome-db-tools) | ⭐4K | Everything database tools |

---

## Phase 3: Build Real Projects (Where You Actually Learn)

### [project-based-learning](https://github.com/practical-tutorials/project-based-learning) ⭐216K

> Build real things. Tutorials organized by language and difficulty.

**Your path — projects that connect to your existing repos:**

| Your Repo | Project to Build | Language | Time |
|-----------|-----------------|----------|------|
| malaysia-fuel-bot | Build a Web Scraper | Python | 1 weekend |
| malaysia-fuel-bot | Build a Twitter/X Bot | Python | 1 day |
| my-malaysia-bot | Build a Chat Application | JavaScript | 3 days |
| dbx-guide | Build a Database Engine | Python | 2 weeks |
| notes | Build a Static Site Generator | Python | 1 week |

### More Project Repos

| Repo | Stars | Approach |
|------|-------|----------|
| [build-your-own-x](https://github.com/codecrafters-io/build-your-own-x) | ⭐350K | Build your own DB, Git, OS, neural network |
| [app-ideas](https://github.com/florinpop17/app-ideas) | ⭐82K | Tiered app ideas: Beginner → Advanced |
| [realworld](https://github.com/gothinkster/realworld) | ⭐82K | Same app in 100+ frameworks |
| [system-design-primer](https://github.com/donnemartin/system-design-primer) | ⭐293K | Learn how big systems work |

---

## Phase 4: Your Roadmap Compass

### [developer-roadmap](https://github.com/kamranahmedse/developer-roadmap) ⭐312K

> Interactive roadmap charts. Click any node to see what to learn + resource links.

**When to open it:**
- Every Sunday: review where you are
- When stuck: find what prerequisite you missed
- Before starting new topic: check if you have the foundation

**Key roadmaps for you:**

| Roadmap | Why It Matters |
|---------|----------------|
| [Backend](https://roadmap.sh/backend) | Your bots are backend — learn the full ecosystem |
| [Python](https://roadmap.sh/python) | Aligned with your primary language |
| [SQL](https://roadmap.sh/sql) | Your DBX and data skills |
| [Git & GitHub](https://roadmap.sh/git-github) | Your version control backbone |

---

## Phase 5: Free Books Library

### [free-programming-books](https://github.com/EbookFoundation/free-programming-books) ⭐355K

> The largest collection of free programming books. English, Chinese, and 50+ languages.

**How to use:** Search by language. Every book is free, legal, and linked directly.

| Language | Must-Read Book (from the list) |
|----------|-------------------------------|
| Python | *Automate the Boring Stuff with Python* — free online |
| JavaScript | *Eloquent JavaScript* — free online |
| SQL | *Use the Index, Luke!* — free online |
| Git | *Pro Git* — free online, official |

---

## Bonus: Language-Specific Repo Collection

### Learn Any Language — Start Here

| Language | Best Starting Repo | Stars |
|----------|-------------------|-------|
| Python | [30-Days-Of-Python](https://github.com/Asabeneh/30-Days-Of-Python) | 44K |
| JavaScript | [30-Days-Of-JavaScript](https://github.com/Asabeneh/30-Days-Of-JavaScript) | 45K |
| TypeScript | [typescript-handbook](https://github.com/microsoft/TypeScript-Handbook) | 9K |
| Go | [go-by-example](https://github.com/mmcgrana/gobyexample) | 7K |
| Rust | [rust-by-example](https://github.com/rust-lang/rust-by-example) | 7K |
| C | [C](https://github.com/TheAlgorithms/C) | 20K |
| C++ | [C-Plus-Plus](https://github.com/TheAlgorithms/C-Plus-Plus) | 31K |
| Java | [Java](https://github.com/TheAlgorithms/Java) | 61K |
| Ruby | [ruby](https://github.com/TheAlgorithms/Ruby) | 1K |
| Swift | [swift-algorithms](https://github.com/apple/swift-algorithms) | 6K |
| Kotlin | [kotlin-by-example](https://play.kotlinlang.org/byExample/overview) | — |
| Zig | [zig-course](https://github.com/daqing/zig-course) | 500+ |
| Lua | [learn-lua](https://github.com/dengwirda/learn-lua) | 200+ |
| Shell | [pure-bash-bible](https://github.com/dylanaraps/pure-bash-bible) | 37K |

---

## Bonus: Domain-Specific Repos

### AI / Machine Learning

| Repo | Stars | What |
|------|-------|------|
| [ML-For-Beginners](https://github.com/microsoft/ML-For-Beginners) | ⭐72K | Microsoft's 12-week curriculum |
| [tensorflow](https://github.com/tensorflow/tensorflow) | ⭐191K | The framework itself |
| [pytorch](https://github.com/pytorch/pytorch) | ⭐89K | PyTorch |
| [transformers](https://github.com/huggingface/transformers) | ⭐145K | Hugging Face, all models |

### Web Development

| Repo | Stars | What |
|------|-------|------|
| [freeCodeCamp](https://github.com/freeCodeCamp/freeCodeCamp) | ⭐413K | Full curriculum, interactive |
| [Front-End-Checklist](https://github.com/thedaviddias/Front-End-Checklist) | ⭐70K | Everything before launch |
| [public-apis](https://github.com/public-apis/public-apis) | ⭐337K | Free APIs for your projects |

### DevOps & Infrastructure

| Repo | Stars | What |
|------|-------|------|
| [90DaysOfDevOps](https://github.com/MichaelCade/90DaysOfDevOps) | ⭐28K | DevOps from zero |
| [docker-curriculum](https://github.com/docker/docker-curriculum) | ⭐6K | Learn Docker (you need this for DBX) |
| [kubernetes-the-hard-way](https://github.com/kelseyhightower/kubernetes-the-hard-way) | ⭐43K | K8s deep dive |

### Cybersecurity

| Repo | Stars | What |
|------|-------|------|
| [HackTricks](https://github.com/HackTricks-wiki/hacktricks) | ⭐50K | Pentesting encyclopedia |
| [Web-Security-Academy](https://portswigger.net/web-security) | — | Free labs by PortSwigger |

---

## How This Connects to Your Existing Repos

| Your Repo | This Roadmap Helps You... |
|-----------|--------------------------|
| **notes** (mechanical Q&A) | Use Python to auto-parse industrial standards; build a searchable DB with SQLite |
| **malaysia-fuel-bot** | Rewrite with cleaner Python structure; add error handling; deploy on cron |
| **my-malaysia-bot** | Convert to TypeScript; add a web dashboard with HTML/CSS |
| **dbx-guide** | Actually use DBX for all your SQL practice; connect it to your project databases |
| **Markdown** | Already mastered — now learn HTML/CSS for richer formatting |
| **douluo-dalu-h5-tw** | Scrape game data with Python; auto-generate strategy pages |
| **book-learn** | This roadmap IS the expanded version of "how to ask AI tools" |

---

## Weekly Learning Template

| Day | Activity | Time |
|-----|----------|------|
| Mon | hello-algo: 1 algorithm chapter | 30 min |
| Tue | Python: 30-Days-Of-Python, 1 day | 30 min |
| Wed | Project: work on your chosen build | 45 min |
| Thu | SQL: 1 W3Schools chapter + practice | 30 min |
| Fri | JavaScript: 33-js-concepts, 1 concept | 30 min |
| Sat | Project deep dive | 2 hrs |
| Sun | Open developer-roadmap, review week, commit to your repos | 30 min |

---

> **Last updated:** 2026-06-25
>
> This roadmap is a living document. As you complete each phase, the next one unlocks.
> Every repo listed is free, open-source, and actively maintained.
