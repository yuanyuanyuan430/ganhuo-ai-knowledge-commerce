# Platform Map

## Feishu

Use Feishu as the operating ledger:

- Bitable `Content`: content ID, title, niche, stage, owner, channel, review status, source count, risk level, draft links, platform IDs, metrics.
- Bitable `Sources`: source URL/contract, owner, author, date, license/permission, allowed use, forbidden use, key points, original angle.
- Bitable `Actions`: content ID, platform, action, automation level, external ID, status, error note, executor.
- Docs: canonical drafts, voice guide, templates, weekly review notes.

Prefer sequential Bitable writes. Use unique IDs for content and source URLs.

## WeChat Official Account

Use automation to improve drafting speed, not to remove editorial control.

- Good automation target: upload media, create or update draft, write back `media_id`, query draft status.
- Human gate: final title, cover, factual claims, CTA, original/declaration settings, and publish click.
- Certified accounts with current permissions may use official publish APIs, but keep human approval before public release.

## Knowledge Planet

Use 知识星球 as the paid delivery room.

- Good AI target: generate topic copy, tags, weekly digest, answer draft, member onboarding checklist, renewal summary.
- Human target: publish theme, set essence, reply sensitive questions, handle refunds, manage members, and decide what becomes paid-only content.
- Avoid non-official reverse API workflows unless the platform explicitly allows them.

## n8n

Use n8n as the main orchestration layer:

1. scheduled trigger or manual trigger;
2. read source allowlist;
3. collect RSS/API/public pages;
4. write source cards;
5. call LLM/RAG workflow;
6. wait for topic approval;
7. create draft;
8. wait for final approval;
9. create公众号草稿 or platform action;
10. collect metrics.

## RAG/Knowledge Tools

Pick one first:

- Dify: visual workflow and API-first app layer.
- AnythingLLM: local-first document chat and simple agent tasks.
- RAGFlow: stronger document parsing-heavy RAG.
- Open WebUI: local/open model UI with knowledge and tools.
- LlamaIndex/Haystack: code-first production RAG.

Use LangGraph or CrewAI after the simple workflow proves useful.
