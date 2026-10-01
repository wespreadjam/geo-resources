# practical

## day 1

pick 20 prompts. four buckets:
- buyer: "best [category] for [persona]"
- compare: "x vs y"
- execute: "how do i [task] with [product]"
- edge: "does [product] support [constraint]"

run on chatgpt, perplexity, google ai mode, claude. record: present, cited, accurate. this is baseline.

## week 1

- ship `llms.txt` at root. [llmstxt.org](https://llmstxt.org/)
- check robots.txt: gptbot, claude-web, perplexity-user, google-extended. decide intentionally.
- add schema.org `softwareapplication` + `techarticle` to docs and compare pages
- docs must render without js

## weeks 2–4: fact density

princeton paper's top tactics. ([arxiv 2311.09735](https://arxiv.org/abs/2311.09735))

per top-10 pages, add:
- 3 statistics ("10k events/sec" not "fast")
- 3 primary-source citations
- 1 named quote

## weeks 2–4: devtool pages

1. compatibility matrix (table)
2. honest comparison page (include your limits)
3. quickstart tested with claude code or cursor
4. migration guide from top 2 competitors
5. dated changelog

## ongoing

**reddit.** perplexity cites it 47%. find 5 subreddits. one real answer/week from the founder account. no spam.

**hacker news.** show hn, thoughtful comments on technical threads.

**monthly:** re-run the 20 prompts. find factual errors → fix the source (reddit comment, old post, stale docs).

## tooling

sheet is fine for 30 days. buy a platform at 50 prompts × 4 engines × weekly. see [tools.md](./tools.md).

## 90-day target

- citation share up 2–5× on top 20 prompts
- 0 persistent factual errors
- 1 agent-tested quickstart
- monthly measurement loop running
