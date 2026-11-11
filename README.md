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
- [airbench](https://airbench.ai/leaderboard) - AI agents as people actually run them, model plus harness (Claude Code, Codex, opencode, Hermes...), hosted or local, scored pass or fail on real tasks: vision, email, online shopping, math and code. Each run records quantization, GPU and harness.
- [Global AI model rankings](https://aisubhub.top/en/rankings/) - Compare task performance, text preferences and coding agents separately. Each source measures a different kind of result.
- [aivs.tv](https://aivs.tv/vs/) - Side-by-side AI model matchups built from posts on X where both models got the same prompt, with outputs shown as video and reported cost and time.
- [Arena](https://arena.ai/leaderboard/code/webdev)
- [Artificial Analysis](https://artificialanalysis.ai/) - Comparison and analysis of AI models and API hosting providers. Independent benchmarks across key performance metrics including quality, price, time per task & latency.
- [BenchLM](https://benchlm.ai/) - Compare 1021 AI models across 814 benchmarks, with 214 ranked scores, source evidence, API pricing, context windows, runtime, and head-to-head pages.
- [CloudQuell](https://cloud.cloudquell.com/llm/?status=ga) - Compare API pricing for 67 LLMs from 8 providers (Anthropic, OpenAI, Google, xAI and more): input, output, cached and batch rates per 1M tokens.
- [Comparity](https://comparity.ai/leaderboard.html)
- [Compute Comparison](https://computecomparison.com/compare-two-llm-providers) - Compare any two LLM API providers side-by-side on input/output token pricing, latency, throughput, and context window. Covers OpenAI, Anthropic, Google, Groq, and 14+ more.
- [EmproIT](https://emproit.com/tools/llm-cost-calculator/) - Compare AI API costs across OpenAI, Anthropic, Google, Mistral. Daily, monthly, annual projections. Free, no signup.
- [LeadsCalc](https://www.leadscalc.com/calculators/ai/api-cost-estimator) - Calculate and compare API costs and benchmarks for OpenAI, Anthropic, Google Gemini, and DeepSeek for free. Estimate token usage, vision processing, and batch discounts instantly.
- [livebench.ai](https://livebench.ai/) - LiveBench 2.0 - a challenging, contamination-free long-horizon AI benchmark. Models do real work (decks, research reports, bug fixes, apps that run for hours) and we grade what they hand back.
- [LLM Registry](https://llm-registry.com/) - Compare 1,500+ AI models side by side. Independent benchmark rankings for GPT, Claude, Gemini, DeepSeek, Llama and more - with provenance, pricing, and performance data.
- [LLM Stats](https://llm-stats.com/leaderboards/best-ai-for-coding) - Compare the best AI for coding using live coding arena results, benchmark performance, and real generation examples for code generation, debugging, and software engineering.
- [llm.ing](https://llm.ing/) - LLM benchmarks, prices, and comparisons - aggregated from public sources with per-score provenance.
- [LLMCompare](https://llmcompare.dev/browse) - Browse and compare pricing for all LLM models. Sort by price, context window, speed, and more.
- [LLM Cost Hub](https://llmcosthub.com/pricing/) - Search, filter, and compare LLM API pricing across major providers in one place.
- [LLM Economics](https://llmeconomics.app/leaderboard) - Compare verified OpenAI, Claude, Gemini, and DeepSeek API prices by standard workload, input tokens, cached input, and output tokens.
- [LLMversus](https://llmversus.com/llm/pricing) - Compare LLM API pricing for GPT-4o, Claude Opus 4, Gemini 2.5 Pro, and 20+ more models. Sortable table with input/output costs, context windows, speed, and capabilities. Updated weekly.
- [LLM Versus API Cost Calculator](https://llmversus.vercel.app/tools/api-cost-calculator/)
- [ModelBenchmark](https://modelbenchmark.io/) - Independent ranking of 202 AI models from 16 public benchmarks, plus prices, context windows, and release dates for 2,406 models.
- [modelgrep](https://modelgrep.com/) - Find the best AI model for your use case: 300+ LLMs ranked by benchmarks, live speed, latency and price. Filter by cost, licence, context or capability - updated hourly.
- [Models Rank](https://modelsrank.org/en/) - Minimal AI model leaderboard that answers three questions: which model is smartest, fastest and cheapest. Aggregates public third-party benchmarks (Artificial Analysis, Arena), updated weekly. Open source.
- [OpenCode Data](https://opencode.ai/data/) - As of November 11, 2026, DeepSeek V4.1 Flash led OpenCode usage over the past 7 days with 158T tokens, followed by GLM-5.3-Flash (7.4T) and Muse Spark 1.3 Contributor (6.2T).
- [OpenRouter](https://openrouter.ai/models) - Compare 600+ LLMs from OpenAI, Anthropic, Google, Meta and more - pricing, context length, and benchmarks side by side, all through one API.
- [Just a moment...](https://pricepertoken.com/)
- [RankLLMs](https://rankllms.com/) - Independent AI model leaderboard and LLM research: benchmark analysis, coding-agent reviews, head-to-head comparisons, API pricing and practical guides.
- [Spicy Lab](https://spicyapi.app) - Independent comparison and benchmark site ranking NSFW AI image, video, and chat models with side-by-side test runs and published methodology (not a generator).
- [The Aggregate](https://theaggregate.ai/models) - Every tracked model on one rating scale fitted across thousands of public benchmarks, with uncertainty and benchmark coverage shown for each.
- [TokenCost](https://tokencost.app/pricing) - Input and output prices per 1M tokens for 173 LLM APIs from 30 providers, in one sortable table with benchmark scores. Cheapest: Qwen3.7 Flash at $0.03 / $0.13.
- [Top AI Hubs](https://topaihubs.com/llm-leaderboard) - Comprehensive comparison and ranking of over 180 AI models (LLMs) across key metrics including quality, price, performance, speed (tokens per second & latency), context window & benchmark scores.
- [TrustHawk](https://trusthawk.ai/compare) - Compare the companies behind ChatGPT, Claude, Gemini, Grok and other models on safety, transparency, privacy and security. Covers 150+ AI companies, each score linked to its public source.
- [Vakati](https://www.vakati-tech.ai/compare) - Head-to-head comparisons of the top language models: LiveBench scores across seven categories, input and output pricing, context windows, and the measured cost of a point of capability. Updated every 15 minutes.
- [Vellum](https://www.vellum.ai/best-llm-for-coding) - Guidance and evaluations for choosing coding models.
- [Vercel AI Gateway](https://vercel.com/ai-gateway/models) - Compare capabilities, pricing, and performance across leading AI providers.
- [VSModels](https://vsmodels.app/#comparisons) - Source-linked editorial model comparisons with browser cost calculators. Published benchmark conditions and third-party examples are distinguished from illustrative previews.
- [WhatLLM](https://whatllm.org/explore) - Live LLM leaderboard ranking 100+ AI models by Intelligence Index, Agentic Index, cost per task, token price, speed, and context. Refreshed daily.
- [Word Spies AI Arena](https://wordspies.com/arena) - LLMs play a team word-association game against each other; every clue graded and every guess judged. Ratings per model, replays, and the 376-game dataset on Hugging Face.

<!-- END LIST -->

## License

[MIT](LICENSE)
