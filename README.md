# Tai-Chi-Sword-32-Form
Tai Chi Sword 32 Form

https://messinasystems.github.io/Tai-Chi-Sword-32-Form/

## 本地改动（2026-10）

- 视频源从 YouTube（`K1priHbQxP8`）换成 B 站「[32式太极剑全套背向演示](https://www.bilibili.com/video/BV1b3411i7XN)」（BV1b3411i7XN，228 秒），背向演示方便跟练。
- 分段按钮改为：点击后从该段起始时间重新加载 B 站播放器并自动播放（`?t=秒`）。
- B 站外链播放器不支持跨域 JS 控制，原版的"段内播完自动循环"功能无法保留；需要循环时用播放器自带的循环键即可。
- 四段为时长均分（每段约 57 秒），可在 `config.json` 里按视频实际套路段落微调，再同步到 `index.html` 内嵌的 Sections 数据。
- 页底新增链接：李德印教学·刘志华演示分解动作（BV1h34y1r7WE）、带口令背向演练（BV1YBSYBgEJk）。
- `10-Form/` 目录仍为上游的占位（内容与 32 式相同），未改动。
