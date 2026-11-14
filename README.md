
<div align="center">

# OpenEvals Datasets

Community-curated test cases, scenarios, trajectories, and evaluation signals — across languages, domains, and real-world tasks.

[Explore OpenEvals](https://github.com/OpenEvals) · [Community & Platform](https://www.cotrust.ai/) · [Contribute](https://github.com/OpenEvals/datasets/issues/new)

</div>

---

## Why This Repository Exists

Evaluation starts with data. We need more than a single score to understand where AI systems succeed, fail, or behave differently depending on the task, language, or context. **OpenEvals Datasets** brings together structured evaluation data that researchers, builders, and communities can inspect, reuse, challenge, and improve.

It's part of [OpenEvals](https://github.com/OpenEvals), an open community building datasets, evaluations, benchmarks, resources, and tooling.

## What Belongs Here

| Data Type | Examples |
| --- | --- |
| **Test Cases & Scenarios** | Prompts, tasks, edge cases, adversarial scenarios, and domain-specific inputs |
| **Model Responses** | Outputs and reference answers for direct evaluation or comparison |
| **Agent Trajectories** | Multi-step interactions, tool calls, observations, and task outcomes |
| **Human Evaluation Signals** | Ratings, preferences, annotations, rationales, and expert judgments |
| **Synthetic Evaluation Data** | Generated test cases or annotations with documented generation and validation methods |

Possible evaluation dimensions include accuracy, usefulness, reasoning, instruction following, linguistic naturalness, task success, tool use, and safety. Not every dataset measures every dimension. Each dataset should clearly document which signals are available and what they mean.

## Dataset Catalog

This repository is just getting started. New datasets will be organized into collections and made available as they are released. Each release will include relevant documentation about its contents, methodology, provenance, license, and known limitations. Want to help shape the collection? [Propose a dataset or use case](https://github.com/OpenEvals/datasets/issues/new).

## Using the Datasets

Browse the available collections and review the documentation for individual datasets before using them.

To work locally:

```bash
git clone https://github.com/OpenEvals/datasets.git
```

Check each dataset's license and provenance before redistribution or use in training.

Evaluation labels reflect particular tasks, rubrics, and annotators (if available). IMPORTANT: They should not automatically be treated as universal ground truth.

## Contributing

We welcome useful datasets, small additions, corrections, annotation improvements, and independent validation — not just large benchmark releases.

1. **Open an [issue](https://github.com/OpenEvals/datasets/issues/new)** to discuss a dataset idea, especially if it is large or needs a new format.
2. **Prepare your contribution** with clear documentation of its contents, collection methodology, attribution, and licensing.
3. **Submit a pull request** explaining what you added, how it was collected or generated, and how you checked its quality.

Please only contribute data you have the right to share.

Do not submit personal or sensitive information, secrets, private agent traces, or confidential or proprietary material without appropriate authorization and consent.

Clearly identify synthetic data and disclose its generation and review process.

We value transparent methods, reproducibility, careful attribution, and honest reporting of limitations. Critical findings and negative results are welcome.

## Related Projects

- **[OpenEvals Resources](https://github.com/OpenEvals/resources)** — Guides, research, taxonomies, and learning materials for AI evaluation.
- **[cotrust.ai](https://www.cotrust.ai/)** — Community activities and hands-on model and agent evaluation.

---

<div align="center">

**Better evaluation is a collective effort.**

[Contribute a Dataset](https://github.com/OpenEvals/datasets/issues/new) · [Explore the Community](https://www.cotrust.ai/)

</div>
