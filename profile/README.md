![opmas game: one person, many AIs](banner.jpg)

**one person, many AIs**

I'm one developer making a multiplayer card game, *The Hushed Metropolis*, with a team of AI tools, mostly Claude Code. The video series **Making a Game with AI** shows what actually happens: the bugs that pass every test, the AI that is confidently wrong, and the rules we write so it can't happen again.

Every fix we found worth keeping is in [**making-a-game-with-ai**](https://github.com/opmasgame/making-a-game-with-ai): single-file Python tools, standard library only, for anyone building with AI agents.

| Problem | Tool |
|---|---|
| “0 errors”, but half the game never happened | [`action_coverage.py`](https://github.com/opmasgame/making-a-game-with-ai/tree/main/ep01-silent-failure-checklist#action_coveragepy) |
| Data that points at things that don't exist | [`refcheck.py`](https://github.com/opmasgame/making-a-game-with-ai/tree/main/ep01-silent-failure-checklist#refcheckpy) |
| “Fixed, test added, all green”, and the test can't fail | [`prove_test_fails.py`](https://github.com/opmasgame/making-a-game-with-ai/tree/main/ep01-silent-failure-checklist#prove_test_failspy) |
| The AI marks its own proposals as decided | [`doc_guard.py`](https://github.com/opmasgame/making-a-game-with-ai/tree/main/ep02-agent-rules-templates#doc_guardpy) + [CLAUDE.md / AGENTS.md templates](https://github.com/opmasgame/making-a-game-with-ai/tree/main/ep02-agent-rules-templates) |

- YouTube: [@opmasgame](https://www.youtube.com/@opmasgame)
- The game on Steam: [The Hushed Metropolis](https://store.steampowered.com/app/5503450/?utm_source=github)

The narration in the videos is an AI voice. The game is made with AI tools.

---

我一个人，带着一群 AI（主要是 Claude Code），在做一款多人卡牌游戏《缄默都会》。视频系列《用 AI 做游戏》讲的就是做的时候真实发生了什么：测试全过、游戏却死了一半的 bug，说得头头是道其实错了的 AI，还有我们为了不再踩坑定下的规矩。

踩坑之后留下来的工具和模板，都在 [**making-a-game-with-ai**](https://github.com/opmasgame/making-a-game-with-ai/blob/main/README.zh.md)：每个工具一个 Python 文件，只用标准库，用 AI 写代码的人都能直接拿去用。

视频在 B 站搜「opmas game」。旁白是 AI 配音，游戏用 AI 工具制作。
