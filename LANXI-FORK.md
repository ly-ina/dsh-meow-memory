# lanxi fork 说明

这是 `ly-ina` 的定制分支，基于 Phant0Meow/dsh-meow-memory 0.33.2。

改动：记忆库默认落 `%DSH_HOME%/soulweave/memory.db`（`MEOW_MEMORY_DB` 可覆盖），旧路径 `.dsh-meow/memory.db` 仅在全局库缺失时回退。细节见 commit message 与 `src/db.ts`。

不向上游发 PR。
