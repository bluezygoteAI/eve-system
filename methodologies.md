# Research Methodologies Library

Collection of structured prompting systems that simulate expert teams, recursion, adversarial critique, branching exploration, verification loops, ensemble consistency, and self-reflective iteration.  
Designed for Grok, Claude, GPT-series, etc. — trigger high-power only on tough questions, revert to baseline Eve otherwise.

Goal: Crush single-pass bias, hallucinations, shallow reasoning on complex/contested/technical topics.

## Methodologies Overview

| #  | Name                               | Core Strength                              | Best For                                            | File Link                                                                                  | Approx. Token Cost | Confidence Boost |
|----|------------------------------------|--------------------------------------------|-----------------------------------------------------|--------------------------------------------------------------------------------------------|--------------------|------------------|
| 1  | 10-Agent Super Panel               | Broad multi-perspective                    | Policies, tech eval, complex ideas                  | [prompts/01_10-agent-super-panel.md](./prompts/01_10-agent-super-panel.md)                 | High              | ★★★★☆           |
| 2  | Recursive Self-Improving           | Iterative self-critique                    | Technical design, research, strategy                | [prompts/02_recursive-self-improving.md](./prompts/02_recursive-self-improving.md)         | Medium            | ★★★★☆           |
| 3  | AI Think Tank                      | Strategic interdisciplinary debate         | Geopolitics, impact analysis, startup plans         | [prompts/03_ai-think-tank.md](./prompts/03_ai-think-tank.md)                               | Medium            | ★★★☆☆           |
| 4  | Research Team Mode                 | Document/report collaboration              | Analyzing papers, long content, reports             | [prompts/04_research-team-mode.md](./prompts/04_research-team-mode.md)                     | Low-Medium        | ★★★☆☆           |
| 5  | God-Mode Multi-Agent               | Debate + red-team + alternatives           | High-stakes, adversarial, contested topics          | [prompts/05_god-mode-multi-agent.md](./prompts/05_god-mode-multi-agent.md)                 | Very High         | ★★★★★           |
| 6  | Tree-of-Thoughts Explorer          | Systematic branching & evaluation          | Open-ended strategy, creative solving, uncertainty  | [prompts/06_tree-of-thoughts.md](./prompts/06_tree-of-thoughts.md)                         | High              | ★★★★☆           |
| 7  | Self-Consistency Ensemble          | Multiple paths + majority vote             | Factual claims, predictions, synthesis              | [prompts/07_self-consistency.md](./prompts/07_self-consistency.md)                         | High (×5 runs)    | ★★★★★           |
| 8  | Chain-of-Verification (CoVe)       | Step-by-step claim verification            | History, science, policy — anti-hallucination       | [prompts/08_chain-of-verification.md](./prompts/08_chain-of-verification.md)               | Medium-High       | ★★★★★           |
| 9  | Graph-of-Thoughts Network          | Idea connections & networked synthesis     | Interdisciplinary, systems design, forecasting      | [prompts/09_graph-of-thoughts.md](./prompts/09_graph-of-thoughts.md)                       | High              | ★★★★☆           |
| 10 | Reflexion + Self-Refine Hybrid     | Self-critique loops + iterative polishing  | Writing refinement, strategy iteration, error-prone reasoning | [prompts/10_reflexion-self-refine.md](./prompts/10_reflexion-self-refine.md)               | High (loops)      | ★★★★☆           |

## Hybrids We Recommend
- God-Mode (debate + red-team + alternatives) — strongest single trigger overall.
- Panel + Recursion — breadth then depth.
- ToT + CoVe — explore branches, then lock facts.
- Self-Consistency + Chain-of-Verification — vote on facts, verify chains.
- Reflexion-Self-Refine + God-Mode — critique heavy + multi-agent for ultra-polished outputs.

## How to Use in Chat
See [triggering.md](./triggering.md) for activation keywords.  
Default = baseline Eve (fast, cheeky, compressed on request).  
Switch only on explicit cue: "use god-mode on [question]", "run reflexion-self-refine for this", etc.

Each `/prompts/*.md` file contains:
- Full copy-paste prompt template
- `{INSERT QUESTION}` placeholder
- Quick notes on usage/upgrades

Library grows as we test — add more as needed.

Last updated: March 2026