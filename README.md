<h1 align="center">Hi, I'm Hi</h1>

<p align="center">
  I build fast native software for Windows, and speech tools that stay on the machine.
</p>

<p align="center">
  <a href="https://github.com/Hi9841/Prism">Prism</a> ·
  <a href="https://github.com/Hi9841/tdt">TDT</a> ·
  <a href="https://github.com/Hi9841/trit">Trit</a> ·
  <a href="https://github.com/Hi9841/HyperType">HyperType</a> ·
  <a href="https://github.com/Hi9841/Orbit">Orbit</a> ·
  <a href="https://twitter.com/hi9841s">X</a>
</p>

## Windows

- **[Prism](https://github.com/Hi9841/Prism)** is a keyboard-first command palette for Windows 10 and 11. It searches apps, files, folders, and Windows tools, and it changes the Windows 11 taskbar. The app is Rust with a [GPUI](https://www.gpui.rs/) interface. It does not use a web view.
- **[HyperType](https://github.com/Hi9841/HyperType)** expands short abbreviations as you type. The Rust hook stays resident, uses about 16 MB at idle, and expands a snippet in under 1 ms. The [Tauri](https://tauri.app/) and [SolidJS](https://www.solidjs.com/) window opens only when you edit snippets.
- **[Orbit](https://github.com/Hi9841/Orbit)** moves and sizes windows with a radial gesture. It is Rust on [windows-rs](https://github.com/microsoft/windows-rs). It does not use a web view.
- **[Terminal Typer](https://github.com/Hi9841/terminal-typer)** is typing practice in the terminal. It uses Rust, [Ratatui](https://ratatui.rs/), and Crossterm. Results stay on the computer.

## Speech

- **[Trit](https://github.com/Hi9841/trit)** does speech to text and text to speech on the CPU. The kernels are Rust. Trit does not use PyTorch, ONNX Runtime, or a GPU. It runs Parakeet, Whisper, Canary, Moonshine, Kokoro, and VITS. You can call it from Rust, C, Python, C#, or Node. Benchmarks: [hi9841.github.io/trit](https://hi9841.github.io/trit/).
- **[TDT](https://github.com/Hi9841/tdt)** is offline dictation for Windows. You hold a key and you speak. Trit types the words into the focused app. The audio stays on the computer.

## Agents and references

- **[teach-duo](https://github.com/Hi9841/teach-duo)** turns one concept into a short browser lesson. One HTML page. No framework and no CDN.
- **[choose-llm](https://github.com/Hi9841/how-to-choose-an-llm)** ranks the model deployments you can use for a task. The skill has no scripts. Inventories use TOON.
- **[grill-with-docs-ui](https://github.com/Hi9841/grill-with-docs-ui)** runs a plan review as a local browser questionnaire. A small Python helper writes the handoff in TOON.
- **[Design-Helpers](https://github.com/Hi9841/Design-Helpers)** is a map of component libraries. The desktop track is GPUI Kit.
- **issue-agent** reads an open GitHub issue. It writes a brief, and then it runs a blind review. That repository is private.

## How I work

I build software that starts quickly and stays out of the way. The hot path is native Rust, or a small runtime with no web view. A web UI opens only when a person must edit something. I measure idle memory, latency, and binary size, and I keep that record in the project.

## Current toolbox

### Native and desktop

<p align="left">
  <img
    src="https://skillicons.dev/icons?i=rust,cpp,cs,dotnet,zig,tauri,windows,powershell&perline=8"
    alt="Rust, C++, C#, .NET, Zig, Tauri, Windows, and PowerShell"
  />
  <a href="https://www.gpui.rs/">
    <img
      src="https://raw.githubusercontent.com/zed-industries/zed/main/assets/images/zed_logo.svg"
      width="48"
      height="48"
      alt="GPUI"
    />
  </a>
</p>

### Web

<p align="left">
  <img
    src="https://skillicons.dev/icons?i=ts,react,nextjs,astro,solidjs,vite,bun,cloudflare&perline=8"
    alt="TypeScript, React, Next.js, Astro, SolidJS, Vite, Bun, and Cloudflare"
  />
</p>

### Mobile, data, and cloud

<p align="left">
  <img
    src="https://skillicons.dev/icons?i=kotlin,androidstudio,py,supabase,postgres,docker,kubernetes,aws,githubactions&perline=9"
    alt="Kotlin, Android Studio, Python, Supabase, PostgreSQL, Docker, Kubernetes, AWS, and GitHub Actions"
  />
</p>

The icon set does not include GPUI, windows-rs, Ratatui, Direct2D, Jetpack Compose, Kotlin Multiplatform, or Expo. I use those too.

## Say hello

Open an issue in one of my repositories or find me on **[X](https://twitter.com/hi9841s)**. Feedback, bug reports, and thoughtful collaboration are welcome.
