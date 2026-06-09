# Kill Switch Audit

## Vendor Dependency Assessment

| Dimension | Current State | Risk Level | 48-Hour Action |
|---|---|---|---|
| **Provider** | Single provider (OpenAI/Anthropic) | H | Activate secondary provider account already configured |
| **Abstraction** | LLM calls abstracted via middleware layer | M | Middleware routes to backup provider immediately |
| **Routing** | Single-model routing | H | Switch to multi-model routing — triage tasks to cheaper models |
| **Eval** | Evals tied to primary provider outputs | M | Run eval suite against backup provider to measure quality delta |

## Portability Score

**Partial** — abstraction layer exists but proprietary training data
creates medium-term dependency until self-hosted model is ready

## If primary vendor doubles pricing tomorrow:

**48-hour response:**
Absorb the cost increase internally — do not pass to clients.
Activate backup provider (AWS Bedrock) for lower-complexity tasks
immediately to reduce inference spend. Begin accelerating timeline
for self-hosted model training on GridMind's proprietary dataset.
No client communication needed unless quality degrades.

## If primary vendor ships a competing product:

**What's defensible that they can't replicate:**
The proprietary permitting outcome dataset — every project submission,
utility response, approval and rejection signal accumulated through
GridMind usage. A foundation model provider has general intelligence
but zero domain-specific outcome data. GridMind's long-term path is
a self-hosted specialist model trained exclusively on permitting
intelligence data, hosted on AWS SageMaker, that outperforms any
general-purpose model on this specific task at a fraction of the
inference cost.

## Long-term portability plan:

1. **Now** — abstract all LLM calls behind a model-agnostic
   middleware layer. Provider is swappable in hours.
2. **6 months** — begin fine-tuning an open-source base model
   (Llama / Mistral) on GridMind's accumulated dataset.
3. **12-18 months** — deploy self-hosted specialist model on AWS
   SageMaker. Retire dependency on external providers for core
   permitting intelligence tasks.
4. **Ongoing** — maintain multi-model routing for non-core tasks
   where general models are more cost-effective.
