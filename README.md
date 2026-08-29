# bagusm

ai student. i build autonomous agents that run entirely on android phones.

```kotlin
val rikka = agent {
    name = "rikka-agent"
    home = "on-device"                    // no cloud required
    skills = listOf("rag", "memory", "self-improvement")
    providers = 62                        // openai-compatible + local models
    speaks = listOf("en", "id")
}

// thesis in progress: does on-device rag actually make agents better?
// measuring it with ragas + g-eval, one emulator run at a time.
```

> rag, in one line: an agent that opens its own notes before answering.

## $ ls ~/projects

```text
rikka-agent/    android-native autonomous agent runtime — on-device rag,
                slash commands, permanent memory, self-improving skills
opengym/        open-source gym web app (my fork) — shipping features
                and fixes upstream
```

## $ ./stats --theme=tokyonight

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=udin-petot&theme=tokyonight" alt="stats" width="49%"/>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=udin-petot&theme=tokyonight" alt="languages" width="49%"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=udin-petot&theme=tokyonight&hide_border=true" alt="streak"/>
</p>

## $ ./snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/udin-petot/udin-petot/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/udin-petot/udin-petot/output/github-contribution-grid-snake.svg" />
    <img alt="contribution snake" src="https://raw.githubusercontent.com/udin-petot/udin-petot/output/github-contribution-grid-snake.svg" />
  </picture>
</p>

---

something broken on this page? [open an issue](https://github.com/udin-petot/udin-petot/issues/new?title=profile+bug&body=found+something+on+this+profile+that+looks+wrong%3A) — i treat everything like a test case.
