<div align="center">

![Profile Banner](assets/room2.png)

# Hi there! <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px">

### AI Engineer | Full Stack Developer | Mechatronics Engineer

I'm a developer with a Master's in Mechatronics Engineering who likes to **ship things that actually run in production** — full-stack web, mobile, AI-powered tools, and the occasional piece of hardware. I work terminal-first and AI-paired (Arch/Omarchy + Claude Code on the CLI), which keeps more of the work on architecture and judgment.

### 🖥️ **[joeyvigil.github.io](https://joeyvigil.github.io)** — my portfolio

A developer portfolio that reads like a terminal session on an Arch box — Waybar status bar, tiled windows, nine themes, and a **real shell** you can type into (press <kbd>`</kbd>).

Built from scratch, no UI library, no tracking. **[Source](https://github.com/joeyvigil/joeyvigil.github.io)** &nbsp;·&nbsp; React 19 · TypeScript · Vite · Tailwind v4

<a href="https://joeyvigil.github.io">
  <img src="assets/portfolio.gif" alt="joeyvigil.github.io — a tour through the sections, the built-in shell running neofetch, and live theme switching" width="100%">
</a>

</div>

---

### 🧰 **Projects**

<table>
<tr>
<td width="50%" valign="top">

#### 💘 [Charmed](https://github.com/joeyvigil/charmed-dating)

<a href="https://github.com/joeyvigil/charmed-dating"><img src="https://raw.githubusercontent.com/joeyvigil/charmed-dating/main/docs/charmed-demo.gif" width="100%" alt="Charmed — landing, search, profiles, and real-time chat"></a>

**A free, no-swipe dating app** — search for people by what matters to you and message anyone. A React web app and a React Native mobile app share one **FastAPI** backend and a single real-time WebSocket, running in production on a **$0 cloud stack**.

**[Live demo](https://charmed.lol)** &nbsp;·&nbsp; **[Source](https://github.com/joeyvigil/charmed-dating)** &nbsp;·&nbsp; FastAPI · React · React Native · Postgres · WebSockets · 122 tests

</td>
<td width="50%" valign="top">

#### 📝 [LaTeX Editor](https://joeyvigil.github.io/latex-editor/)

<a href="https://joeyvigil.github.io/latex-editor/"><img src="assets/latex-editor.png" width="100%" alt="LaTeX Editor — building blocks, editor, and live preview"></a>

A beginner-friendly, **in-browser LaTeX editor** for people who don't know LaTeX — a clickable palette of building blocks, live preview, and a real **pdfLaTeX** compile that runs entirely in your browser via WebAssembly. No install, no backend.

**[Live demo](https://joeyvigil.github.io/latex-editor/)** &nbsp;·&nbsp; **[Source](https://github.com/joeyvigil/latex-editor)** &nbsp;·&nbsp; React · TS · Vite · WASM

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🏰 [Dan's Labyrinth — Tower Defense](https://play.google.com/store/apps/details?id=com.joeyvigil.danslabyrinth)

<a href="https://play.google.com/store/apps/details?id=com.joeyvigil.danslabyrinth"><img src="assets/dans-labyrinth.png" width="100%" alt="Dan's Labyrinth — Tower Defense"></a>

A **maze / tower-defense mobile game** built in **Godot 4.6** — your towers act as walls and enemies pathfind through the gaps. A 20-level hand-authored campaign, 10 distinct towers, infinite escalating waves, boss rounds, and a global leaderboard. **Live on Google Play.**

**[Get it on Google Play](https://play.google.com/store/apps/details?id=com.joeyvigil.danslabyrinth)** &nbsp;·&nbsp; Godot 4.6 · Android · Closed-source

</td>
<td width="50%" valign="top">

#### 🤖 [joey-bot](https://github.com/joeyvigil/discord-bot)

<a href="https://github.com/joeyvigil/discord-bot"><img src="https://raw.githubusercontent.com/joeyvigil/discord-bot/master/docs/screenshots/help.png" width="100%" alt="joey-bot — Discord slash-command bot"></a>

A **Discord bot** built with discord.py using slash commands — games, live button polls, trivia, tic-tac-toe, and API-powered toys. Dockerized and deployed on **Fly.io**.

**[Invite it](https://discord.com/oauth2/authorize?client_id=1516042370439839784)** &nbsp;·&nbsp; **[Source](https://github.com/joeyvigil/discord-bot)** &nbsp;·&nbsp; Python · discord.py · Docker · Fly.io

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🧬 [sql-to-rest](https://joeyvigil.github.io/sql-to-rest/)

<a href="https://joeyvigil.github.io/sql-to-rest/"><img src="https://raw.githubusercontent.com/joeyvigil/sql-to-rest/main/docs/screenshot.png" width="100%" alt="sql-to-rest — SQL schema to FastAPI app"></a>

Paste SQL `CREATE TABLE` statements and get back a **runnable FastAPI app** — SQLAlchemy models, Pydantic schemas, and per-table CRUD routers (optional Docker + pytest), downloadable as a `.zip`.

**[Live demo](https://joeyvigil.github.io/sql-to-rest/)** &nbsp;·&nbsp; **[Source](https://github.com/joeyvigil/sql-to-rest)** &nbsp;·&nbsp; React · TS · FastAPI codegen

</td>
<td width="50%" valign="top">

#### 📻 radi.sh — Terminal Internet Radio

<img src="assets/radish.png" width="100%" alt="radi.sh — 50,000 radio stations, behind a command line">

A **terminal-aesthetic radio player** for Android — ~50,000 stations from the community Radio Browser directory, driven by a vim-style `:` command line. A **real** 512-point FFT spectrum analyser drawn from decoded PCM, now-playing titles read straight off the ICY stream, background playback with lock-screen controls, and 32 colour themes. 13 runtime dependencies — no UI kit, no state library, no nav library.

Android · React Native · Expo SDK 57 · TypeScript · Closed-source

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🦆 [Ducky Tech Interview](https://github.com/joeyvigil/ducky-tech-interview)

<a href="https://github.com/joeyvigil/ducky-tech-interview"><img src="assets/ducky.png" width="100%" alt="Ducky Tech Interview — pick a topic, answer out loud, get graded against a rubric"></a>

Mock tech interviews the rubber-duck way — a question is **read aloud**, you **answer out loud**, and your spoken answer is transcribed and **graded against a rubric by a local LLM**. Runs fully offline on **Ollama**; rubrics and model answers stay server-side so you can't peek. Swap the grader model from the home page.

**[Source](https://github.com/joeyvigil/ducky-tech-interview)** &nbsp;·&nbsp; FastAPI · Ollama · React · Vite · Web Speech API · SQLite

</td>
<td width="50%" valign="top">

#### ⌨️ [k3yb0rg](https://github.com/joeyvigil/k3yb0rg)

<a href="https://github.com/joeyvigil/k3yb0rg"><img src="assets/k3yb0rg.jpg" width="100%" alt="k3yb0rg — a 3D-printed, hand-wired 49-key mechanical keyboard"></a>

A **3D-printable, hand-wired 49-key mechanical keyboard** inspired by the v4n4g0n ergo layout — printed case, hand-soldered switch matrix, and a Pro Micro running **QMK**. The repo is the full build guide: print, wire, flash, assemble, and remap the layers.

**[Build guide](https://github.com/joeyvigil/k3yb0rg)** &nbsp;·&nbsp; QMK · ATmega32U4 · CAD · 3D printing

</td>
</tr>
</table>

---

### 🐧 **Terminal & Omarchy**

Small things I actually use every day, packaged so other people can install them too.

- 🎛️ **[omasettings](https://github.com/joeyvigil/omasettings)** — a terminal UI for [Omarchy](https://omarchy.org) settings: theme, keybindings, displays, audio, notifications, all in one menu. **[On the AUR](https://aur.archlinux.org/packages/omasettings)** (`yay -S omasettings`) and in Omarchy's install menu. *Shell*
- 📌 **[omarchy-taskbar](https://github.com/joeyvigil/omarchy-taskbar)** — pinned app icons for the Omarchy bar. Click to launch or focus, with running-state indicators; pin and unpin from the bar itself, no config editing. *QML*
- 🐟 **[cfish](https://github.com/joeyvigil/cfish)** — a terminal aquarium in the spirit of `cmatrix` and `cbonsai`: fish swim across your terminal trailing bubbles and wake. `yay -S cfish`. *C · ncurses*
- 📖 **[cnovel](https://github.com/joeyvigil/cnovel)** — a terminal screensaver that writes a novel one keystroke at a time, at the cadence of a real typist — bursts, pauses, and the occasional backspaced typo. `yay -S cnovel`. *C · ncurses*
- 🍇 **[dionysus](https://github.com/joeyvigil/omarchy-dionysus-theme)** — an Omarchy theme derived from PewDiePie's `dionysus` Hyprland rice: a One Dark / Nord hybrid keyed on neon cyan, carried into terminal, bar, lock screen, btop, Helix, Neovim, and VS Code.

---

### 🚀 **About Me**

- 🤖 **AI Engineer** — LLM-powered apps and tools with **LangChain**, **LangGraph**, **Ollama**, and vector databases (see **[Ducky](https://github.com/joeyvigil/ducky-tech-interview)**, graded end to end by a local model)
- 🐍 **Full-stack end to end** — Python/FastAPI back ends, React/React Native front ends, Postgres, Docker, CI, and small deploys on **AWS**
- 📱 **Ships to phones** — React Native and Godot on Android, from release signing through the Play listing
- 🔧 **Master's in Mechatronics Engineering** — robotics, embedded systems, CAD, and 3D printing
- 🐧 **Terminal-first on Arch/Omarchy** — and I package what I build: two AUR releases and an Omarchy bar plugin
- 🎲 Building small products through **[Squeak Inc. Games](https://squeakincgames.com/)**

### 🛠️ **Tech Stack**

[![My Skills](https://skillicons.dev/icons?i=py,java,js,ts,html,css,bash,fastapi,flask,spring,hibernate,nodejs,react,angular,vite,tailwind,bootstrap,materialui,godot,postgres,mysql,sqlite,aws,docker,kubernetes,githubactions,vercel,linux,git,github,maven,gradle,postman,selenium,arduino,vscode&perline=12)](https://skillicons.dev)
