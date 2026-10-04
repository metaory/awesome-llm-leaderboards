<div align="center">
  <h1>Awesome LLM Leaderboards</h1>
  <p><b>Find where to compare LLMs, not which model to pick.</b></p>
  <p>A directory of LLM leaderboards, pricing tables, and comparison tools.</p>
  <p><a href="https://metaory.github.io/awesome-llm-leaderboards/">metaory.github.io/awesome-llm-leaderboards</a></p>
</div>

## Why

Model rankings and price sheets live on dozens of sites. Searching for "best coding model" or "Claude vs GPT price" scatters you across bookmarks and tabs. This project indexes those sources in one place so you can find where to compare, not which model to pick.

<!-- BEGIN LIST -->

## Sources

- [AI Data Hub](https://www.aidatahub.io/data/llm-pricing) - LLM API pricing data and comparison.
- [Arena](https://arena.ai/leaderboard/code/webdev) - Community-driven model leaderboard for web development.
- [Artificial Analysis](https://artificialanalysis.ai/) - Independent model and AI agent performance analysis.
- [BenchLM](https://benchlm.ai/) - Current LLM leaderboard and benchmark results.
- [Claude cost vs quality](https://claude-models.agensse.com/) - Every Claude model compared on cost and quality at each effort level, from public measurements, with open data.
- [CloudQuell](https://cloud.cloudquell.com/llm/?status=ga) - LLM API pricing with input, output, cached, and batch rates.
- [Comparity](https://comparity.ai/leaderboard.html) - AI model leaderboard and comparisons.
- [DeepSeek Research Hub](https://dseek.app/api-pricing) - Unofficial DeepSeek API price table with peak and off-peak rates and a cost calculator, cited from DeepSeek's pricing page.
- [EmproIT](https://emproit.com/tools/llm-cost-calculator/) - LLM API cost calculator and pricing comparison.
- [LeadsCalc](https://www.leadscalc.com/calculators/ai/api-cost-estimator) - API pricing calculator with benchmark context.
- [LiveBench](https://livebench.ai/) - Contamination-free benchmark leaderboard for LLMs.
- [LLM Registry](https://llm-registry.com/) - Compare LLM models by benchmark scores and modality.
- [LLM Stats](https://llm-stats.com/leaderboards/best-ai-for-coding) - Leaderboards focused on the strongest models for coding.
- [llm.ing](https://llm.ing/) - Model prices, benchmarks, and comparison tables.
- [LLMCompare](https://llmcompare.dev/browse) - Browse and compare LLMs side by side.
- [LLM Cost Hub](https://llmcosthub.com/pricing/) - LLM API pricing comparison table.
- [LLM Economics](https://llmeconomics.app/leaderboard) - Verified LLM API costs and price leaderboard.
- [LLMversus](https://llmversus.com/llm/pricing) - Compare LLM API providers on pricing and benchmarks.
- [modelgrep](https://modelgrep.com/) - Search and compare hundreds of models by capability and cost.
- [OpenCode Data](https://opencode.ai/data/) - Open data and rankings for AI coding models.
- [OpenRouter](https://openrouter.ai/models) - A broad model catalog with API pricing, context, and capabilities.
- [Price Per Token](https://pricepertoken.com/) - API cost tables and LLM rankings.
- [RankLLMs](https://rankllms.com/) - Model rankings across speed, reasoning, coding, and cost.
- [TokenCost](https://tokencost.app/pricing) - A frequently updated table of LLM API pricing.
- [Top AI Hubs](https://topaihubs.com/llm-leaderboard) - An LLM model comparison leaderboard.
- [Vakati](https://www.vakati-tech.ai/compare) - Compare models by score, price, and cost per point.
- [Vellum](https://www.vellum.ai/best-llm-for-coding) - Guidance and evaluations for choosing coding models.
- [Vercel AI Gateway](https://vercel.com/ai-gateway/models) - Model catalog for Vercel AI Gateway providers.
- [WhatLLM](https://whatllm.org/explore) - Explore and compare a live LLM leaderboard.

<!-- END LIST -->

## How it works

[`collection.json`](collection.json) in git is the source of truth. CI runs on a schedule (and on push): it refreshes metadata and screenshots from each listed site, then builds and publishes the static directory to GitHub Pages.

## Contribute a source

Know a leaderboard, pricing table, or comparison tool that belongs here? Add it.

Only index places to compare models, not individual models or vendor landing pages. Prefer the deep link to the useful page (leaderboard, pricing table, explorer).

Add one entry to [`collection.json`](collection.json):

```json
{
  "id": "short-slug",
  "name": "Display Name",
  "url": "https://example.com/",
  "description": "One short sentence.",
  "tags": ["leaderboard"],
  "icon": "https://example.com/favicon.ico"
}
```

One site, one entry. Keep `description` to one sentence. Tags must be from: `benchmarks`, `calculator`, `catalog`, `coding`, `comparison`, `leaderboard`, `pricing`. `id` and `url` must be unique.

Open a PR. Run `npm run readme` after editing `collection.json` (CI also regenerates the Sources list). Screenshots and metadata refresh on the next collect run.

## License

[MIT](LICENSE)
