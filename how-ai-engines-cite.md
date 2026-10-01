# how ai engines cite

only ~11% domain overlap between chatgpt and perplexity. optimize per engine. ([averi benchmark](https://www.averi.ai/how-to/chatgpt-vs.-perplexity-vs.-google-ai-mode-the-b2b-saas-citation-benchmarks-report-(2026)))

## chatgpt

- training data + bing retrieval
- top source: wikipedia (~48%)
- win: get on authoritative roundups, dense docs
- slow to update. right or wrong, citations stick.

## perplexity

- live web first
- top source: reddit (~47%)
- win: fresh dates, primary sources, real reddit presence
- cites ~22 sources per answer vs chatgpt's ~8

## google ai overviews

- grounded in google index
- top source: youtube (~23%)
- win: whatever ranks on google serps + multi-modal
- kills clicks. 60% of searches end without one.

## claude

- training-data heavy, web search when enabled
- behaves closer to chatgpt than perplexity
- win: clean markdown docs, structured content

## copilot / bing chat

- bing index
- win: bing seo is relevant again

## coding agents (cursor, claude code, devin)

- pull your actual docs into context
- win: markdown, stable urls, llms.txt, runnable code
- if the quickstart fails, you lose the install

## test loop

quarterly, per engine, same prompt families:
- "best [category] for [use case]"
- "x vs y vs z"
- "how do i do [task] with [product]"
- "does [product] support [constraint]"

record: present, cited (url), accurate.
