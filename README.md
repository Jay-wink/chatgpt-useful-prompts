# ChatGPT Useful Prompts

This repo stores reusable ChatGPT prompts, making them easy to reuse across learning, planning, explanation, and work scenarios.

Some tasks are better suited for ChatGPT than coding agents such as Codex. The reason is that ChatGPT is stronger at explanation and planning: it explains concepts in a more accessible way, plans in more detail, and is better at breaking complex tasks down step by step. Codex usually responds more concisely and focuses more on execution and code implementation, which is useful when writing code, but can be less suitable for understanding new knowledge or organizing thoughts.

A good current usage pattern is to place these prompts in the Project Instructions of a ChatGPT Project. After that, when creating a new Chat inside the Project, you can call the corresponding `/command` directly, similar to commands in Claude Code.

## Prompts

- `explain_knowledge`: Use `/knowExplain` to explain new concepts from slides, webpages, papers, screenshots, assignments, or code repositories.
