## RExBench : A Research Extension Benchmark for Autonomous Coding Agents

**Authors**: Anonymous


### 📂 Repository Structure

```bash
.
├── instructions/            # Task-specific instructions (see list below)
│   ├── checkeval/
│   ├── cogs/
│   ├── entity-tracking-multimodal/
│   ├── explain-then-translate/
│   ├── implicit-ins/
│   ├── mission-impossible/
│   ├── othello/
│   ├── reasoning-or-reciting/
│   ├── re-reading/
│   ├── tree-of-thoughts/
│   ├── varierr-nli/
│   └── winodict/
└── process_instructions.py     # Script for processing instructions
```

Each subdirectory inside instructions/ contains an instructions.md file that describes the task setting.

### 🎒 Dataset 
: ([Dataset Link](https://drive.google.com/file/d/1v4prWb-5lu69teNTdd6PZwsdMXxz_xqn/view?usp=drive_link))

### ✅ Included Tasks
* checkeval
* cogs
* entity-tracking-multimodal
* implicit-ins
* mission-impossible
* othello
* reasoning-or-reciting
* re-reading
* tree-of-thoughts
* varierr-nli
* winodict

### 🧠 Baseline Agents
* Agent 1: aider ([GitHub](https://github.com/RExBench2025/aider))
* Agent 2: OpenHands ([GitHub](https://github.com/RExBench2025/OpenHands))
* Agent 3: Claude Code