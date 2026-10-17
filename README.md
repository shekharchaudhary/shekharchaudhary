# Hi, I'm Shekhar 👋

I'm an AI-focused software engineer in the San Francisco Bay Area. I build reliable, human-centered AI products—from agent workflows and retrieval systems to production web and mobile experiences.

My current focus is learning how to determine whether AI systems actually work: designing evaluations, studying evaluator failure modes, measuring risk, and turning evidence into better engineering decisions.

## What I build

- AI agents that use tools, delegate work, and recover from failures
- Retrieval-augmented generation with citations and evaluation
- Full-stack AI products with TypeScript, Python, React, and Next.js
- Product-quality workflows with tests, observability, privacy, and safety boundaries

## AI Evaluation Learning Journey

I am building a public, evidence-first learning record around AI evaluation. Rather than presenting polished conclusions too early, I will publish hypotheses, datasets, rubrics, experiments, negative results, and changes in my understanding.

### What I will study

- **LLM-as-judge reliability:** position bias, verbosity bias, score stability, rubric sensitivity, and agreement with human labels
- **RAG evaluation:** separating retrieval failures from generation failures; measuring context relevance, answer correctness, citation support, and appropriate abstention
- **Risk-category evals:** unsupported claims, privacy leakage, unsafe guidance, prompt injection, overconfidence, stereotyping, and tool misuse
- **Evaluation failure modes:** ambiguous ground truth, label imbalance, dataset contamination, reward hacking, test-set overfitting, correlated graders, and aggregate scores that hide rare severe failures
- **Human calibration:** annotation protocols, disagreement analysis, confidence, and determining when an automated grader should abstain

### Planned experiments

1. Measure position bias by grading the same response pairs in both orders.
2. Test whether judges prefer longer answers when semantic quality is held constant.
3. Attribute RAG errors under correct, missing, distracting, and conflicting context.
4. Compare rule-based checks, LLM judges, and human review across a small risk taxonomy.

Each experiment will include versioned prompts and rubrics, reproducible inputs, raw results, failure analysis, limitations, and a clear next question. The upcoming repository will be called **AI Evaluation Lab**.

## Systems I have built

### [ReadOpp](https://github.com/shekharchaudhary/readopp)

An AI-assisted visual-story publishing product that transforms source material into editable, shareable content. My work spans the generation pipeline, structured editing experience, templates, accessibility, regression testing, and production deployment.

**Engineering themes:** structured generation, human-in-the-loop editing, durable workflows, evaluation, responsive UX, and production reliability.

### Agent Swamp

A multi-agent mission-control system for delegating work to specialized agents, reviewing intermediate results, recovering long-running missions, and delivering artifacts. A public engineering case study is in progress.

**Engineering themes:** orchestration, tool use, bounded review loops, durable execution, cancellation, owner isolation, and artifact delivery.

### SipPal

An iOS beverage-intelligence product focused on understandable nutrition data and responsible health-adjacent UX. Its deterministic evaluation suite currently covers 111 synthetic scenarios alongside regression tests.

**Engineering themes:** evaluation-driven development, multimodal product design, data quality, Swift, privacy, and explicit safety boundaries.

## How I work

I care about more than a successful demo. For AI systems, I document:

- What success means and how it is measured
- Where the model or system can fail
- How users review, correct, or stop automated work
- Latency, cost, privacy, and security tradeoffs
- The evidence behind product and engineering decisions

## Current research questions

- When can an LLM judge be trusted, and how should that trust be measured?
- How can a RAG evaluation identify which layer caused the failure?
- Which rare but severe failures disappear inside an aggregate score?
- How should automated evaluators be calibrated against human judgment?
- How can risk evaluations remain specific, reproducible, and honest about their limits?

## Connect

- GitHub: [@shekharchaudhary](https://github.com/shekharchaudhary)

I'm interested in applied AI and agent-engineering teams working on ambitious, broadly useful systems.
