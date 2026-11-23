---
layout: default
title: "Horizon Summary: 2026-11-23 (EN)"
date: 2026-11-23
lang: en
---

> From 28 items, 2 important content pieces were selected

---

**Technology News**
1. [Perplexity as a Lens on Model Intelligence](#item-tech-news-1) ⭐️ 8.0/10

**Technology Blog**
1. [Productive Flailing Under Uncertainty](#item-tech-blog-1) ⭐️ 6.0/10

---

## Technology News

<a id="item-tech-news-1"></a>
### [Perplexity as a Lens on Model Intelligence](https://openai.com/index/perplexity-and-intelligence/) ⭐️ 8.0/10

An OpenAI article argues that model intelligence should be evaluated through perplexity and the quality of next-token prediction, connecting these metrics to learning, compression, and reasoning. The supplied material does not establish whether the article introduces a novel evaluation method or presents an insightful synthesis of existing ideas, so the article&\#x27;s specific claims and evidence cannot be independently characterized from the available excerpt.

hackernews · acossta · Nov 22, 17:06 · [Discussion](https://news.ycombinator.com/item?id=50601525)

**「Why Perplexity Matters」** Perplexity measures how surprising a model finds the tokens it predicts, with lower values indicating better prediction under the model&\#x27;s tokenization and evaluation setup. In the discussion, commenters relate this measure to cross-entropy loss and to compression, arguing that stronger prediction can reflect a more effective internal model of the data.

**「Practical Implication」** If perplexity remains informative across model generations, developers and organizations may be able to use a comparatively simple held-out metric alongside task-specific benchmarks. The discussion also reports that Microsoft is sharing pre-training progress on a common evaluation set, including a reported log-perplexity of 0.819 for MAI-2 Base, but the supplied material does not independently verify that figure or establish how comparable the evaluation conditions are.

**「Community Debate」** Participants found the perplexity-intelligence connection surprising but plausible, with one commenter arguing that prediction and compression capture the extraction of world models from raw data. Another commenter welcomed perplexity as a simple benchmark while questioning its role in an era of increasing reinforcement learning and more complicated evaluations; the discussion also raised uncertainty about how earlier reasoning models, including GPT-4.5 and o1, fit into the reported trend.

**Tags**: `#artificial-intelligence`, `#language-models`, `#perplexity`, `#machine-learning-evaluation`, `#technical-analysis`

---

## Technology Blog

<a id="item-tech-blog-1"></a>
### [Productive Flailing Under Uncertainty](https://seangoedecke.com/when-in-doubt-flail-about/) ⭐️ 6.0/10

rss · Sean Goedecke · Nov 23, 00:00

**「Background」** When guidance is scarce, engineers often wait for a complete understanding before acting, but the author argues that this caution can waste time and lock teams into poorly informed plans. The alternative is deliberately trying multiple approaches, paying close attention to feedback, and quickly abandoning ideas that are not working.

**「Solution」** The author frames this approach as flailing: try many things, learn from direct contact with reality, and ruthlessly drop approaches that produce no positive signal. Trying several options increases the chance of finding a good one while reducing emotional investment in any single plan. He distinguishes three forms: product flailing, in which teams explore around an uncertain value proposition until one idea gains traction; engineering flailing, in which speculative changes reveal how a complex system responds before deeper investigation; and organizational flailing, in which engineers try concrete interventions when teams are not communicating or cannot articulate their problems. His experience with GitHub Models illustrates the product form, where several unsuccessful features and integrations led to the unexpectedly useful idea of running AI inference with a GitHub Actions token, which became the seed of Continuous AI. The approach depends on reading feedback from both technical results and people, especially in organizational work, where continuing with a failing intervention can redirect anger toward the engineer. Although the article offers little evidence about cost, coordination overhead, or when analysis is preferable, it presents experimentation as a way to overcome both uncertainty and the psychological discomfort of acting before certainty exists.

**「Takeaway」** The article’s central claim is that uncertainty is best navigated through parallel, feedback-driven experiments rather than passive analysis or premature commitment. Its broader significance is that effective engineering judgment includes knowing when to explore broadly, discard weak paths quickly, and treat repeated failure as a normal part of learning.

**Tags**: `#engineering-leadership`, `#experimentation`, `#feedback-loops`, `#technical-decision-making`

---