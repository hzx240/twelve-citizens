# 十二公民

用十二个性格不同的陪审员并行审计一份已经生成的计划。十二份意见都回来之后，审判长核对原文，再决定有没有必要修改。票数只供对照。

## 别人怎么安装

这个仓库是一个 Cursor 插件市场，里面只有 `twelve-citizens` 一个插件。

1. 打开 Cursor 的 Customize。
2. 选择从 GitHub 仓库导入（From GitHub Repository）。
3. 填入本仓库地址。
4. 安装 **twelve-citizens**。

安装后，在对话里把计划发出来，并说「用十二公民审一下」。

Cursor 官方市场需要另外提交审核：[cursor.com/marketplace/publish](https://cursor.com/marketplace/publish)。审核通过后，别人也可以在市场里直接搜索安装。

## 使用

对已经写好的计划开庭。它会同时派出 12 个子代理，全部返回后才由审判长汇总。默认只给裁决，不改计划；明确说「按裁决改」时，只改必须修改的条目。

一次审计会启动 12 个代理，适合拿来压一份准备执行的计划，不适合每一句草稿都跑一遍。

## 许可

[MIT](twelve-citizens/LICENSE)
