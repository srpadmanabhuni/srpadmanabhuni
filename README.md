# Dr Srinivas Padmanabhuni

**Agentic AI testing and assurance** — building open tools and checklists so teams can judge AI agents with evidence, not vibes.

CTO & Co-founder, [AiEnsured / testAIng.com](https://testaing.com). PhD 2000, University of Alberta. Upcoming book on Agentic AI.

Contact: **srinivas AT testAIng.com**

## Links

| | |
|---|---|
| **agentest** (offline agent test runner) | https://github.com/srpadmanabhuni/agentest |
| **Agentic AI Test Checklist 110** (Hugging Face) | https://huggingface.co/datasets/srinivaspadmanabhuni/agentic-ai-test-checklist-110 |
| **Assurance Report Card** (HF Space) | https://huggingface.co/spaces/srinivaspadmanabhuni/agentest-assurance-report-card |
| **Boardroom AI Brief** (Substack) | https://boardroomaibrief.substack.com |
| **Site** | https://sites.google.com/view/srinivaspadmanabhuni |
| **ORCID** | https://orcid.org/0009-0002-3904-7204 |

## Pinned project: agentest

[agentest](https://github.com/srpadmanabhuni/agentest) is an offline, deterministic test runner for agentic AI. It covers the open [Agentic AI Test Checklist 110](https://huggingface.co/datasets/srinivaspadmanabhuni/agentic-ai-test-checklist-110): give it an agent's OpenTelemetry GenAI traces (plus optional A2A AgentCard and MCP tools) and it returns pass / fail / n/a for each check. No account, token, network, or model judge required.

- Try the [Assurance Report Card Space](https://huggingface.co/spaces/srinivaspadmanabhuni/agentest-assurance-report-card)
- Pick a [`good first issue`](https://github.com/srpadmanabhuni/agentest/labels/good%20first%20issue) if you want to contribute
- Subscribe to [Boardroom AI Brief](https://boardroomaibrief.substack.com) for short notes on AI governance and assurance

```bash
pip install git+https://github.com/srpadmanabhuni/agentest
agentest std run --agent a14
```
