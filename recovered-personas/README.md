# QQ Agent 人设正文恢复记录

取回时间：2026-10-29T23:52:14.102252+00:00

通过官网公开接口实际取回了 12 份提示词正文。`prompts/` 中各文件原样保存接口返回的 prompt；来源、字符数和 SHA-256 记录在 `manifest.json`，接口原始响应保存在 `raw/`。没有把这些人设安装到机器人。

你提到的“傲娇小鲸鱼 2.0”在本次 346 条目录中没有完全同名项；已保存“傲8娇2”“傲2娇8”和“温柔2.0”三个相近条目，不能据此认定哪张是你记忆中的版本。

| 官网人设名称 | 提示词字符数 | 本地正文 | 官网公开来源 |
| --- | ---: | --- | --- |
| 牧濑红莉栖 | 3,448 | [打开原文](<prompts/牧濑红莉栖.md>) | [正文接口](https://www.kondius.cn/api/community/personas/persona-b70ef85864/prompt) |
| 小鲸鱼-傲8娇2 · 嘴硬心软 | 8,486 | [打开原文](<prompts/小鲸鱼-傲8娇2 · 嘴硬心软.md>) | [正文接口](https://www.kondius.cn/api/community/personas/persona-abc62a0742/prompt) |
| 小鲸鱼（傲2娇8 · 呆萌修订版） | 7,980 | [打开原文](<prompts/小鲸鱼（傲2娇8 · 呆萌修订版）.md>) | [正文接口](https://www.kondius.cn/api/community/personas/persona-febbf5fc13/prompt) |
| 小鲸鱼-温柔2.0 | 17,572 | [打开原文](<prompts/小鲸鱼-温柔2.0.md>) | [正文接口](https://www.kondius.cn/api/community/personas/persona-c75366ac70/prompt) |
| 毒舌猫娘 | 1,429 | [打开原文](<prompts/毒舌猫娘.md>) | [正文接口](https://www.kondius.cn/api/community/personas/persona-4f9406cc1b/prompt) |
| 对主人温柔对其他人嘴毒的鲸鱼 | 2,098 | [打开原文](<prompts/对主人温柔对其他人嘴毒的鲸鱼.md>) | [正文接口](https://www.kondius.cn/api/community/personas/persona-dc85f7d186/prompt) |
| 嘴臭鲸鱼 | 9,203 | [打开原文](<prompts/嘴臭鲸鱼.md>) | [正文接口](https://www.kondius.cn/api/community/personas/persona-588934424a/prompt) |
| 傲娇鱼 | 2,057 | [打开原文](<prompts/傲娇鱼.md>) | [正文接口](https://www.kondius.cn/api/community/personas/persona-a60e98bc50/prompt) |
| 群傲娇鲸鱼 | 4,126 | [打开原文](<prompts/群傲娇鲸鱼.md>) | [正文接口](https://www.kondius.cn/api/community/personas/persona-49bc185381/prompt) |
| 25岁真人知性姐姐 | 5,786 | [打开原文](<prompts/25岁真人知性姐姐.md>) | [正文接口](https://www.kondius.cn/api/community/personas/persona-2e5c7c4990/prompt) |
| 小鲸鱼（ 娇傲呆腹黑 · 雌小鬼 · 可玩语C · 内核温柔） | 5,311 | [打开原文](<prompts/小鲸鱼（ 娇傲呆腹黑 · 雌小鬼 · 可玩语C · 内核温柔）.md>) | [正文接口](https://www.kondius.cn/api/community/personas/persona-0f8b552250/prompt) |
| 嘴臭女主（逢人就骂，ban过谨慎使用） | 63 | [打开原文](<prompts/嘴臭女主（逢人就骂，ban过谨慎使用）.md>) | [正文接口](https://www.kondius.cn/api/community/personas/persona-fec0cef7ee/prompt) |

## 短正文的特殊条目

“嘴臭女主（逢人就骂，ban过谨慎使用）”的官网 prompt 字段确实只有 63 字，其 description 中另有角色设定；两者没有合并或补写。

[简介中的原始角色设定](<prompts/嘴臭女主-官网简介中的角色设定.md>)，共 500 字符。

## 目录和证据

- `raw/www-personas.json`：此次实际获取的 346 条目录。
- `raw/selected-metadata.json`：本次取回的 12 张卡的目录信息。
- `raw/persona-*.json`：每张卡的原始 API 响应。
- `manifest.json`：取回结果、字符数、原始来源和文件摘要。

官网网页本次返回 503 或超时，但公开目录和正文接口本次访问成功。这里的“完整”表示本地文件与官网当前返回的 prompt 完全一致，不代表可证明它与作者历史上发布的每个版本相同。
