# Hi, I’m Sai Charan Teja Vulli

## Selected AI engineering projects

I study computer science and build local AI applications, backend services and evaluation tools.

| Project | Evidence |
| --- | --- |
| Proof | [Follow the failing and corrected pull-request checks](https://github.com/saicharanteja-vulli/relay-agent-gateway/pull/1). Four candidate checks passed after the correction. |
| Orbit | [Compare two models and three retrieval methods](https://github.com/saicharanteja-vulli/orbit-agent-control-center/blob/feat/evaluated-document-research/evaluation/results/README.md). On 30 fictional test questions, Qwen3 1.7B passed 26 automatic checks with hybrid retrieval and 20 with BM25. |
| Aegis | [Inspect the synthetic code-review evaluation](https://github.com/saicharanteja-vulli/aegis-security-auditor/blob/feat/evaluated-ai-review/evaluation/results/v2/test-qwen3-4b.md). Adding model findings to static review introduced 48 false positives without increasing true positives across 72 cases. |
| Dues | [Try the invoice and duplicate-payment workflow](https://github.com/saicharanteja-vulli/dues-receivables#try-the-workflow). |
| Relay | [Review a scoped proposal and approve the exact payload](https://github.com/saicharanteja-vulli/relay-agent-gateway). |

I’m a university student building projects in **C++, data analysis, databases and local AI**. I use coursework and personal prototypes to turn concepts into working tools, then document how they work and where their limits are.

### Project portfolio

| Project | What it explores | Built with |
|---|---|---|
| [StatLens](https://github.com/saicharanteja-vulli/statlens) | Browser-based probability, inference and regression | JavaScript · HTML · CSS |
| [ReliefLink](https://github.com/saicharanteja-vulli/relieflink) | A synthetic disaster-relief database model | MongoDB · Python |
| [Nova](https://github.com/saicharanteja-vulli/nova-mac-assistant) | Local AI conversation and reviewed Mac actions | Swift · SwiftUI · Ollama |
| [Online Retail Analysis](https://github.com/saicharanteja-vulli/online-retail-analysis) | Data cleaning, visualisation and sales exploration | Python · pandas · Plotly |
| [Emergency Service Management](https://github.com/saicharanteja-vulli/emergency-service-management) | FIFO request processing and console reports | C++17 · STL |
| ParkEasy | Parking allocation, search, billing and reports | C++ · arrays · vectors |

### What I’m learning

Data structures and algorithms, statistical reasoning, database design, and building software that other people can understand and run.

My repositories include academic group projects and personal experiments. Project READMEs explain scope, setup, limitations and available credits.

## ParkEasy team project

A C++ console parking manager for 18 spaces across three floors. Sai Charan Teja implemented slot statistics and the main menu. Harsha handled entry and allocation, Mounica Sai the grid display, Divya vehicle search, Sreedhar exit and billing, and Adithya sorted reports.

| Walkthrough | Expected result |
| --- | --- |
| Start with an empty grid | 18 available slots; the first two floors hold cars and the third holds bikes. |
| Park two cars and one bike | Statistics show 3 occupied and 15 available. |
| Exit a car after 3 hours | The bill is ₹150 at ₹50 per hour and the slot becomes available. |
| Fill all six bike spaces, then request another bike slot | No eligible bike space remains, even if car spaces are available. |

The presentation demonstrates in-memory records and example bills. The full-lot row gives an acceptance case for a future source release.
