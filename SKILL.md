---
name: ganhuo-ai-knowledge-commerce
description: Designs a reproducible AI-assisted knowledge-commerce pipeline for公众号、知识星球、飞书知识库、私域社群、课程陪跑、内容产品和知识付费项目. Use when the user wants to turn source research, AI drafting, style distillation, publishing, community delivery, and data review into a practical SOP that improves throughput, quality, conversion, and operating safety.
---

# 干活 AI 知识付费流水线

## Overview

Apply this skill to turn a knowledge-product idea into a repeatable operating system: source selection, source cards, AI knowledge base, writing style, content factory,公众号草稿, 知识星球交付, private-domain follow-up, and weekly review.

Keep the posture growth-oriented: improve source quality, improve content velocity, improve trust, improve conversion, and lower avoidable complaint, copyright, platform, and refund risk. Avoid treating AI rewriting as a magic cleanup layer; treat AI as the production assistant and the human operator as the editor, source owner, and final publisher.

## Workflow

1. Define the offer: niche, user pain, promised deliverable, price ladder, trust proof, and the reason this product is better than scattered free content.
2. Build the source engine: separate owned experience, authorized material, public references, public reports, interviews, tool tests, and user-submitted cases.
3. Create source cards: record URL or contract, author, date, license or permission status, usable scope, key points, risk notes, and what original angle will be added.
4. Build the knowledge base: organize source cards into topic clusters, user questions, templates, examples, objections, glossary, and case notes.
5. Distill the voice: define tone, pacing, examples, taboo words, title style, CTA style, and the human story bank. Improve recognizability without copying another creator's expression.
6. Run the content factory: generate topic options, outline, draft, source-linked claims, tables, CTA, and platform-specific variants.
7. Review before publishing: check source traceability, factual accuracy, personal information, commercial claims, AI-generated media disclosure, and platform fit.
8. Ship to channels: create公众号草稿, prepare知识星球主题, generate朋友圈/企微 follow-up copy, and keep public release under human approval.
9. Review the loop: record reads, completion, follows, comments, paid conversion, refund signals, questions, and next week's experiments.

## Operating Stack

Prefer the smallest stack that can be reproduced:

- Feishu Bitable: master content table, source cards, platform action table, metrics table.
- Feishu Docs or a local Markdown folder: canonical draft body and knowledge notes.
- Dify, AnythingLLM, RAGFlow, Open WebUI, LlamaIndex, or Haystack: knowledge base and RAG layer.
- n8n: schedule, RSS/API intake, status updates, review forms, and draft creation.
- WeChat Official Account API or manual editor:公众号草稿 creation, with final publish approval by a person.
- 知识星球: manual publishing and member operation unless an official API is clearly available.

Route to heavier frameworks only when the simple stack is no longer enough:

- LangGraph or CrewAI: multi-agent drafting, critique, and review loops.
- Postgres: durable audit log when Feishu Bitable is not enough.
- Custom scripts: bulk import, export, or deterministic linting.

## Output

Return a compact Knowledge Commerce Pipeline Brief:

- product positioning;
- source map and source-card schema;
- knowledge-base structure;
- publishing workflow;
-公众号 article template;
-知识星球 weekly operating rhythm;
- automation map;
- review checklist;
- 30/60/90-day rollout;
- metrics and experiment backlog.

Use tables for operating design. Limit the first execution plan to the smallest set that improves output quality or conversion this week.

## Growth Copy Rules

Transform hard guarantee language into improvement language:

- Replace "保证收入" with "提高变现概率" or "跑通收入模型".
- Replace "100% AI 写" with "AI 起草, 人工加经验和审稿".
- Replace "搬运资料" with "授权资料、公开资料导读、自有案例、实测复盘".
- Replace "自动赚钱" with "提高选题、写作、交付和复盘效率".
- Replace "必爆" with "提高完读、收藏、转发和转化的可验证动作".

Preserve energy and commercial clarity, but remove claims that cannot be proven.

## References

Read these only when needed:

- `references/checklist.md` for the brief template and scoring checklist.
- `references/platform-map.md` for Feishu, WeChat, 知识星球, and automation boundaries.
- `references/source-policy.md` for source-card rules and safer source categories.
- `references/prompt-pack.md` for reusable prompts.

## Operating Principles

- Improve the user's business goal without turning the SOP into a loophole playbook.
- Prefer one repeatable publishing loop over a giant theoretical funnel.
- Keep AI-generated output grounded in source cards and human experience.
- Keep final public publishing and refund-sensitive decisions under human control.
- Treat user trust as the compounding asset: better claims, clearer limits, faster delivery, and visible proof.
