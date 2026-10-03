# pi-extensions

Extensions I've written or maintain for [Pi](https://github.com/earendil-works/pi). Each one lives in its own repo for now; this will become a monorepo later.

Install any of them with `pi install git:github.com/aliceisjustplaying/<name>`.

## Mine

| Extension | What it does |
| --- | --- |
| [pi-batch-order](https://github.com/aliceisjustplaying/pi-batch-order) | Keeps batched tool calls parallel, but orders the ones that conflict |
| [pi-cache-spy](https://github.com/aliceisjustplaying/pi-cache-spy) | Tells you before you send whether your next message will bust the prompt cache, and after whether it did |
| [pi-claude-artifacts](https://github.com/aliceisjustplaying/pi-claude-artifacts) | Publishes claude.ai artifacts |
| [pi-interrupt](https://github.com/aliceisjustplaying/pi-interrupt) | Ctrl+Enter interrupts and sends; Enter steers; Alt+Enter queues |
| [pi-remember-last-model](https://github.com/aliceisjustplaying/pi-remember-last-model) | Restores the last model and thinking level you picked, on startup and `/new` |
| [pi-sync](https://github.com/aliceisjustplaying/pi-sync) | `/sync`: pulls and pushes the git repo your Pi config lives in, then reloads |
| [pi-usage](https://github.com/aliceisjustplaying/pi-usage) | A small Claude and Codex subscription usage widget |
| [pi-wake](https://github.com/aliceisjustplaying/pi-wake) | Runs a command in the background and wakes the agent when it finishes or prints a line you name |
| [pi-you-should-know](https://github.com/aliceisjustplaying/pi-you-should-know) | Every few steps, asks whether there's something you should know but probably missed |
| [pi-arm64-exec](https://github.com/aliceisjustplaying/pi-arm64-exec) | Stops agents from reaching for Python or Ruby just to read or edit files |

## Forks I maintain

| Extension | Forked from | What it does |
| --- | --- | --- |
| [pi-anthropic-compat](https://github.com/aliceisjustplaying/pi-anthropic-compat) | [2h2d-co/pi-anthropic-compat](https://github.com/2h2d-co/pi-anthropic-compat) | Native Anthropic compaction support |
| [pi-black](https://github.com/aliceisjustplaying/pi-black) | [paoloanzn/pi-black](https://github.com/paoloanzn/pi-black) | Use your Claude subscription with Pi |
| [pi-herdr-subagents](https://github.com/aliceisjustplaying/pi-herdr-subagents) | [0xRichardH/pi-herdr-subagents](https://github.com/0xRichardH/pi-herdr-subagents) | Interactive subagents that run in herdr panes |
| [pi-web-search](https://github.com/aliceisjustplaying/pi-web-search) | [ttttmr/pi-web-search](https://github.com/ttttmr/pi-web-search) | Web search through Gemini, OpenAI or Anthropic |
