# Prompt Pack

Run prompts in this order:

1. Source cards: create or audit source records.
2. Topic scoring: pick the strongest article angles.
3. Outline: turn one angle into a publishable structure.
4. Draft review: improve trust, completion, and conversion clarity.
5. Knowledge Planet post: convert public content into member delivery.
6. Weekly review: decide what to repeat, change, or stop.

## Topic Scoring

```text
基于下面的来源卡和目标用户，给我 10 个可写选题。
每个选题输出：标题方向、用户痛点、可交付结果、可引用来源、需要补充的人类经验、风险点、推荐优先级。
输出 JSON array 或 Markdown table。
```

## Outline

```text
用这些来源卡生成公众号文章提纲。
要求：
1. 前 150 字直接说明解决什么问题；
2. 每 300-400 字有一个新信息、表格、步骤或案例；
3. 至少加入一个我自己的经验/测试/截图位置；
4. 不写保证收益；
5. 保留来源链接位置。
```

## Draft Review

```text
审查这篇草稿，提高完读率、信任感和转化清晰度。
检查：标题具体性、前 150 字、事实来源、个人经验、表格密度、CTA、夸大承诺、隐私信息、平台敏感表达。
输出：保留什么、修改什么、重写后的标题 5 个、最终发布清单。
```

## Knowledge Planet Post

```text
把这篇公众号文章改成知识星球主题。
输出：
1. 主题标题；
2. 3 段正文；
3. 一个可执行作业；
4. 标签建议；
5. 置顶/精华判断；
6. 评论区引导问题。
语气像认真分享的同行，不像卖课。
```

## Weekly Review

```text
基于本周数据复盘知识付费流水线。
字段：文章阅读、完读/互动、加私域、模板包购买、星球新增、退款/投诉、成员问题。
输出：本周有效动作、无效动作、下周 3 个实验、要停掉的 1 件事。
```
