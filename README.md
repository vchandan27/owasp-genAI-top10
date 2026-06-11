# OWASP GenAI Top 10 · Interactive Explorers

Interactive, single-file visualizations of the OWASP GenAI Security Project Top 10 documents: architecture maps with clickable risk hotspots and full detail panels for each risk (description, examples, attack scenarios, and prevention/mitigation guidance).

**Live hub:** [https://vchandan27.github.io/owasp-genAI-top10/](https://vchandan27.github.io/owasp-genAI-top10/)

| Explorer | Source document | Path |
|----------|----------------|------|
| [Top 10 for LLM Applications](https://vchandan27.github.io/owasp-genAI-top10/llm/) | OWASP Top 10 for LLM Applications v2.0 (2025) | `/llm/` |
| [Top 10 for Agentic Applications](https://vchandan27.github.io/owasp-genAI-top10/agentic/) | OWASP Top 10 for Agentic Applications (2026) | `/agentic/` |

## The risks

| LLM Top 10 (2025) | Agentic Top 10 (2026) |
|---|---|
| LLM01 Prompt Injection | ASI01 Agent Goal Hijack |
| LLM02 Sensitive Information Disclosure | ASI02 Tool Misuse and Exploitation |
| LLM03 Supply Chain | ASI03 Identity and Privilege Abuse |
| LLM04 Data and Model Poisoning | ASI04 Agentic Supply Chain Vulnerabilities |
| LLM05 Improper Output Handling | ASI05 Unexpected Code Execution (RCE) |
| LLM06 Excessive Agency | ASI06 Memory & Context Poisoning |
| LLM07 System Prompt Leakage | ASI07 Insecure Inter-Agent Communication |
| LLM08 Vector and Embedding Weaknesses | ASI08 Cascading Failures |
| LLM09 Misinformation | ASI09 Human-Agent Trust Exploitation |
| LLM10 Unbounded Consumption | ASI10 Rogue Agents |

## Usage

Every page is a dependency-free single HTML file; open it in any browser or serve via GitHub Pages. Deep links work per risk, e.g. `llm/#llm01` or `agentic/#asi06`. Keyboard: arrow keys switch risks, Esc closes the panel.

## Attribution and license

Content is from the [OWASP GenAI Security Project](https://genai.owasp.org) documents "OWASP Top 10 for LLM Applications v2.0" and "OWASP Top 10 for Agentic Applications 2026", licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Changes were made: the document content was reformatted into interactive pages. These adaptations are distributed under the same CC BY-SA 4.0 license.

This is an independent educational project. It is **not** affiliated with or endorsed by OWASP or Palo Alto Networks.
