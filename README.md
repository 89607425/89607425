<!-- ============================================================
     the whole profile is one terminal session.
     no headers, no badges, no banners — just commands and output.
     ============================================================ -->

```bash
$ ssh guest@houjunyi2005.dev
# connected — session started (uptime since 2005)
```

```bash
$ cat about.ts
```

```ts
const junyi = {
  name: "Junyi Hou · 侯竣译",
  base: "Shenyang, Liaoning, CN",
  education: "BS Software Engineering — Central South University",
  since: 2023,
} as const;  // not planning to change
```

```bash
$ ls ~/stack -1
languages/   python · java · typescript · javascript
frameworks/  fastapi · react
infra/       docker · chromadb
```

```bash
$ git log --oneline --author=junyi
```

`a1b2c3d` [**feat(SparrowDB)**](https://github.com/89607425/SparrowDB) — a full-stack SQL database written from scratch · compiler → engine → storage  
`f4e5d6c` [**feat(PHDS_RAG)**](https://github.com/89607425/PHDS_RAG) — enterprise RAG for wiki documents · query rewriting · BM25 + ChromaDB hybrid · BGE-Reranker · LLM-as-Judge  
`7a8b9c0` [**feat(RevYou)**](https://github.com/89607425/RevYou) — PM, Dev and Tester agents take turns reviewing your PRD  
`0d1e2f3` [**feat(PhotoForYou)**](https://github.com/89607425/PhotoForYou) — 500 photos picked in 30 seconds · built for people who take too many pictures  
`4a5b6c7` [**feat(jianlide)**](https://github.com/89607425/jianlide) — AI resume diagnosis · ATS pass rate · content · project experience · job matching  
`9e8d7c6` [**feat(chunfeng)**](https://github.com/89607425/chunfeng) — tarot & six-yao divination · when unsure, ask the spring breeze

```bash
$ crontab -l
0  7 * * *    /usr/bin/gym          # lift heavy things, clear mental cache
0  18 * * 0   /usr/bin/photo-walk   # hunt good light around Shenyang
# feeds into PhotoForYou — I take way too many photos
```

```bash
$ watch git activity --live
```

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/89607425/89607425/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/89607425/89607425/output/github-contribution-grid-snake.svg" />
  <img alt="github contribution grid snake" src="https://raw.githubusercontent.com/89607425/89607425/output/github-contribution-grid-snake.svg" width="100%" />
</picture>

```bash
$ exit
# connection closed — come back anytime, the session logs itself.
```

<div align="center">
  [main ●]&nbsp;&nbsp;junyi@shenyang&nbsp;&nbsp;·&nbsp;&nbsp;uptime 21y&nbsp;&nbsp;·&nbsp;&nbsp;<a href="https://github.com/89607425"><img src="https://komarev.com/ghpvc/?username=89607425&color=0e7526&style=flat-square&label=visitors" alt="visitors" /></a>
</div>
