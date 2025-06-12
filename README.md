# LLM-Fail-to-Acquire-Context
A Benchmark for Evaluating LLMs' Ability to Request Missing Information in Math Problems

**Blog:** <a href="https://sunset-jupiter-cf3.notion.site/LLM-Fail-to-Acquire-Context-20fb7e977237802ca126ed554ccb8083?pvs=74">
    <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white" width="80" style="vertical-align: middle;">
</a>


[Benchmark](#benchmark) | [Experiments](#experiments) | [Cite](#cite) 

---

A common frustration arises when LLMs provide mismatched implementations or make uncontrolled assumptions, leading to unexpected and undesirable results. This challenge often occurs when LLMs encounter incomplete or ambiguous inquiries, which users may unconsciously provide due to their interaction habits and expectations.

We build a benchmark to investigate this intriguing challenge faced by Large Language Models (LLMs):

1. LLM's tendency to **directly answer** when **curial context is missing** and their **significant performance degradation** as a result.
2. LLM may stuck in a **special type hallucinations-as-assumption** then answer directly when **curial context is missing**, which leads to completely wrong answers.

![overview](asset/overview.png)

> (Left) Performance degradation from full context to missing context, even though LLM are explicitly prompted about asking questions. (Right) LLMs' tendency to make wrong assumptions when context is missing, leading to hallucinations and incorrect answers.

## Benchmark
We are uploading the benchmark to HuggingFace Datasets, which will be available soon. Feel free to play with the nano version of the benchmark in the `benchmark` folder.

## Experiments

Codes `really` coming soon!

## Cite

```bibtex
@misc{shen2025llmfail,
	title={LLM Fail to Acquire Context},
	author={Shen, Xinjie},
	year={2025},
	howpublished={\url{https://sunset-jupiter-cf3.notion.site/Failing-to-Acquire-Context-A-Benchmark-for-Evaluating-LLMs-Ability-to-Request-Missing-Information--20fb7e977237802ca126ed554ccb8083}},
	note={Notion Blog},
}
```