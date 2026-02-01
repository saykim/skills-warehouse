---
name: news-producer
description: Produce concise news briefs focused on AI, tech, IT big tech, Korea-related tech/economy, and economics. Use this skill when asked to create, summarize, or deliver a curated news report or daily tech/economy digest. Must gather sources, summarize 핵심만, then have Gemini CLI review before presenting final output.
---

# News Producer

## Overview
Curate and summarize the latest AI/tech/big-tech/Korea/economy news, then pass the draft through Gemini for factual/clarity review before delivering the final brief.

## Workflow
1) Collect sources (fresh, reputable) via web_search/web_fetch.
2) Draft concise summaries (핵심만) with links.
3) Run Gemini review on the draft and apply fixes.
4) Deliver final output to the user.

## Step 1: Collect sources
- Use `web_search` for: AI, tech, IT big tech, Korea-related tech/economy, and macro economy.
- Prefer official/company blogs, major outlets, and government/financial institutions.
- Keep 4–10 items total unless the user requests more.

## Step 2: Draft concise summaries (핵심만)
- 1–2 sentences per item, 최대 3줄.
- Include link(s) for each item.
- Focus on: what happened, why it matters, immediate impact.

**Draft format (example):**
- [분야] 제목 — 핵심 요약 1–2문장. (출처 링크)

## Step 3: Gemini review (mandatory)
- Use Gemini CLI to review the draft and fix factual/clarity issues.
- Command template:
  - `gemini -p "다음 뉴스 요약을 사실성/명확성 기준으로 검수하고, 수정/보완이 필요하면 고쳐서 최종본만 출력해줘.\n\n[초안 붙여넣기]" -o text`
- Apply Gemini’s corrections before final delivery.
- If Gemini CLI is unavailable, report the failure and ask the user to proceed without review or retry.

## Final output format (default)
섹션별(목적/영역 기준)로 제공:

**AI**
- …

**Big Tech / IT**
- …

**Korea (Tech/Economy)**
- …

**Economy**
- …

(요청 시) 간단 리스트 형으로 전환 가능.
