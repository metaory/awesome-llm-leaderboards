<div align="center">
  <h1>Awesome LLM Leaderboards</h1>
  <p><b>Find where to compare LLMs, not which model to pick.</b></p>
  <p>A directory of LLM leaderboards, pricing tables, and comparison tools.</p>
  <p><a href="https://metaory.github.io/awesome-llm-leaderboards/">metaory.github.io/awesome-llm-leaderboards</a></p>
</div>

## Why

Rankings, price sheets: dozens of sites
Search "best coding model", "Claude vs GPT price": scattered bookmarks, tabs, ...

This indexes those sources in one place: where to compare, not which model

## Contribute a source

Know a leaderboard, pricing table, comparison tool that belongs here? Add it

Index places to compare models; not individual models, vendor landing pages
Prefer the deep link (leaderboard, pricing table, explorer)

Add one entry to [`collection.json`](collection.json):

```json
{
  "id": "short-slug",
  "url": "https://example.com/",
  "tags": ["leaderboard"]
}
```

One site, one entry. Unique `id`, `url`. Tags from: `benchmarks`, `calculator`, `catalog`, `coding`, `comparison`, `leaderboard`, `pricing`

Name, description, icon: inferred on collect. Override when page metadata is wrong, missing. Optional `wait` (ms): slow pages finish before screenshot

Open a PR. CI: metadata, screenshots, Sources list
Locally: `npm run collect` then `npm run readme`

## How it works

[`collection.json`](collection.json) in git: source of truth
CI on schedule, on push: refresh metadata, screenshots; regenerate README Sources; build, publish to GitHub Pages

<!-- BEGIN LIST -->

## Sources

- [AI Compare API Calculator](https://www.aicompare.ninja/en/api-calculator) - Estimate monthly LLM API costs from token usage and compare models using published OpenRouter prices. Free, no signup.
- [AI Data Hub](https://www.aidatahub.io/data/llm-pricing) - Compare LLM API input and output token prices, context windows, and capabilities across major AI models in 2026.
- [Arena](https://arena.ai/leaderboard/code/webdev) - See which AI models rank highest at building real web apps: frontend, fullstack, games and dashboards. Ranked by developers on real builds.
- [Artificial Analysis](https://artificialanalysis.ai/) - Comparison and analysis of AI models and API hosting providers. Independent benchmarks across key performance metrics including quality, price, output speed & latency.
- [BenchLM](https://benchlm.ai/) - Compare 889 AI models across 625 benchmarks, with 216 ranked scores, source evidence, API pricing, context windows, runtime, and head-to-head pages.
- [CloudQuell](https://cloud.cloudquell.com/llm/?status=ga) - Compare API pricing for 59 LLMs from 8 providers (Anthropic, OpenAI, Google, xAI and more): input, output, cached and batch rates per 1M tokens.
- [Comparity](https://comparity.ai/leaderboard.html)
- [EmproIT](https://emproit.com/tools/llm-cost-calculator/) - Compare AI API costs across OpenAI, Anthropic, Google, Mistral. Daily, monthly, annual projections. Free, no signup.
- [LeadsCalc](https://www.leadscalc.com/calculators/ai/api-cost-estimator) - Calculate and compare API costs and benchmarks for OpenAI, Anthropic, Google Gemini, and DeepSeek for free. Estimate token usage, vision processing, and batch discounts instantly.
- [LiveBench](https://livebench.ai/)
- [LLM Registry](https://llm-registry.com/) - Compare 1,500+ AI models side by side. Independent benchmark rankings for GPT, Claude, Gemini, DeepSeek, Llama and more - with provenance, pricing, and performance data.
- [LLM Stats](https://llm-stats.com/leaderboards/best-ai-for-coding) - Compare the best AI for coding using live coding arena results, benchmark performance, and real generation examples for code generation, debugging, and software engineering.
- [llm.ing](https://llm.ing/) - LLM benchmarks, prices, and comparisons - aggregated from public sources with per-score provenance.
- [LLMCompare](https://llmcompare.dev/browse) - Browse and compare pricing for all LLM models. Sort by price, context window, speed, and more.
- [LLM Cost Hub](https://llmcosthub.com/pricing/) - Search, filter, and compare LLM API pricing across major providers in one place.
- [LLM Economics](https://llmeconomics.app/leaderboard) - Compare verified OpenAI, Claude, Gemini, and DeepSeek API prices by standard workload, input tokens, cached input, and output tokens.
- [LLMversus](https://llmversus.com/llm/pricing) - Compare LLM API pricing for GPT-4o, Claude Opus 4, Gemini 2.5 Pro, and 20+ more models. Sortable table with input/output costs, context windows, speed, and capabilities. Updated weekly.
- [ModelBenchmark](https://modelbenchmark.io/) - Independent ranking of 202 AI models from 16 public benchmarks, plus prices, context windows, and release dates for 2,406 models.
- [modelgrep](https://modelgrep.com/) - Find the best AI model for your use case: 300+ LLMs ranked by benchmarks, live speed, latency and price. Filter by cost, licence, context or capability - updated hourly.
- [OpenCode Data](https://opencode.ai/data/) - As of October 9, 2026, space-bunny led OpenCode usage over the past 7 days with 42T tokens, followed by Muse Spark 1.3 Contributor (35T) and DeepSeek V4.1 Flash (34T).
- [OpenRouter](https://openrouter.ai/models) - Compare 500+ LLMs from OpenAI, Anthropic, Google, Meta and more - pricing, context length, and benchmarks side by side, all through one API.
- [Price Per Token](https://pricepertoken.com/) - Free LLM API pricing comparison. Compare GPT-5, Claude, Gemini & DeepSeek costs instantly. Updated daily with official prices from OpenAI, Anthropic & more.
- [RankLLMs](https://rankllms.com/) - Research-backed AI model and coding-tool reviews, head-to-head comparisons, pricing analysis and practical guides to help you choose what to use.
- [TokenCost](https://tokencost.app/pricing) - Compare API pricing for GPT-5.4, Claude Opus 4.6, Gemini 3.1, Grok 4, and 158+ LLMs. Sortable table with benchmarks. Free.
- [Top AI Hubs](https://topaihubs.com/llm-leaderboard) - Comprehensive comparison and ranking of over 180 AI models (LLMs) across key metrics including quality, price, performance, speed (tokens per second & latency), context window & benchmark scores.
- [Vakati](https://www.vakati-tech.ai/compare) - Head-to-head comparisons of the top language models: LiveBench scores across seven categories, input and output pricing, context windows, and the measured cost of a point of capability. Updated every 15 minutes.
- [Vellum](https://www.vellum.ai/best-llm-for-coding) - Guidance and evaluations for choosing coding models.
- [Vercel AI Gateway](https://vercel.com/ai-gateway/models) - Compare capabilities, pricing, and performance across leading AI providers.
- [WhatLLM](https://whatllm.org/explore) - Live LLM leaderboard ranking 100+ AI models by Intelligence Index, Agentic Index, cost per task, token price, speed, and context. Refreshed daily.

<!-- END LIST -->

## License

[MIT](LICENSE)
