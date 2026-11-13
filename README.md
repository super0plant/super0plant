### super0plant

Local-first tools for [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness) (DSH).
Windows · no telemetry · no accounts · everything stays on disk.

#### Game Time — per-game playtime tracker

Tracks how long each game actually runs, straight from the running processes (the launcher does not have to be running), and charts daily / weekly / monthly / all-time totals with a per-platform split. Ships as a DSH sidebar panel, plus a standalone tray app that works without DSH.

- Repository: [dsh-plugin-game-time](https://github.com/super0plant/dsh-plugin-game-time)
- Install: `dsh plugin --profile desktop add github:super0plant/dsh-plugin-game-time`
- Data stays in `%USERPROFILE%\.dsh\storages\game-time\`