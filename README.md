# Hi, I'm Leo Yu

I focus on AI agents and applied AI: turning model capabilities into applications with clear workflows, useful tools, and ways to check whether they work. My projects span multi-agent systems and RAG, multimodal image generation, user-facing software, and the lower-level foundations behind them.

I'm based in New Zealand and hold a Master of Information Technology from the University of Waikato. I'm looking for opportunities in AI application development and software engineering.

## Core Skills

- **Agents and LLM applications:** ReAct, Plan-and-Solve, multi-agent orchestration, LangChain, LangGraph, RAG, embeddings and vector search, tool and function calling, MCP, prompt and context engineering, short- and long-term memory, agent evaluation, and guardrails.
- **AI application engineering:** Python, FastAPI, Redis, ChromaDB, asynchronous workflows, API design, Docker, monitoring, and automated testing. I pay attention to routing, tool permissions, failure recovery, and quality regression as well as model responses.
- **Applied AI and multimodal:** PyTorch, PyTorch Lightning, Hugging Face Diffusers, CLIP, BLIP, data preparation, model adaptation, training, sampling, and evaluation.
- **Software development:** TypeScript, React, Next.js, Vue, and REST APIs, with project experience connecting interfaces, backend services, and data stores.
- **Systems foundations:** C/C++, RISC-V, operating systems, computer architecture, Verilog CPU design, and LLVM/Clang. This background helps me reason about execution, state, and performance below the application layer.
- **AI-assisted development:** Proficient with Cursor, OpenAI Codex, Claude Code, Gemini, DeepSeek, and ChatGPT, using them alongside requirements analysis, code review, and testing.

## Selected Work

### [EchoMind — Multi-Agent Customer Support](https://github.com/Leo-Xiaoyi/EchoMind)

EchoMind is my Python/Vue application for customer requests that need more than a single chatbot response. It brings fine-grained intent recognition, structured multi-turn state, primary and supporting agents, on-demand RAG, reloadable business Skills, MCP tools, request deduplication, monitoring, and end-to-end evaluation into an observable workflow.

- Combined LLM classification, embeddings, and pattern rules to identify intent and urgency, extract fields such as order IDs, amounts, and error codes, and carry task state into the next turn.
- Gave General, Technical, and Billing agents distinct responsibilities, Skills, and tool permissions. A mixed request such as a login error plus a duplicate charge can involve both specialist agents before one response is composed.
- Used Redis for recent conversations and task state, and ChromaDB for knowledge retrieval, historical summaries, and user profiles. Tool execution includes validation, timeouts, caching, circuit breaking, and fallbacks.
- Added monitoring and LLM-as-Judge evaluation to inspect routing, tool behaviour, and answer quality. The interface supports English and Chinese, with the final reply following the selected language.

### [Storybook Image Generation with ARLDM](https://github.com/Leo-Xiaoyi/ai-storybook-generation-arldm)

My undergraduate thesis connected a LLaMA2-7B story-text stage with an adapted ARLDM image-generation workflow to explore coherent storybook image sequences.

- Prepared paired image-text data from Oxford Reading Tree stories and built five-frame sequences and an HDF5 data pipeline.
- Adapted the public ARLDM workflow's data loading, preprocessing, and configuration, then ran, sampled, and debugged GPU experiments.
- Compared generated outputs with SDXL V1.0 and evaluated text-image consistency and coherence across frames.

### [Waikato Digital & Tech Ecosystem — Industry Internship](https://github.com/Leo-Xiaoyi/WDT-Ecosys)

I worked with a cross-cultural team to deliver a digital and tech ecosystem website for a Waikato client. I owned the frontend implementation and took part in client demonstrations, feedback cycles, and handover.

- Built the responsive homepage and main pages with Next.js, TypeScript, and Tailwind CSS.
- Implemented search and filtering for a directory covering 300+ organisations, along with an interactive map.
- Built Join, Contact, and Opt-out form interfaces and collaborated with the backend teammate on submission integration.

### [UniKiwi Connect — Bilingual Community App](https://github.com/Leo-Xiaoyi/UniKiwi-Connect)

A full-stack university project for international students in New Zealand, designed to bring useful housing, study, work, and everyday-life information into one community space.

- Connected a React frontend, Express API, and MongoDB data layer.
- Implemented registration and login, posts, comments, likes, search and filtering, and English/Chinese interface text.
- Worked through authentication flows, data models, and frontend-backend integration issues.

## Systems Foundations in Practice

### [LoongArch32 Five-Stage Pipelined CPU](https://github.com/Leo-Xiaoyi/LoongArch-CPU)

Designed and debugged an educational Verilog LoongArch32 CPU with pipeline control, hazard handling and forwarding, instruction extensions, CSR, and exception paths. It gave me a concrete way to reason about instructions, state, and performance from the hardware side.

### [UCAS RISC-V Operating System Labs](https://github.com/Leo-Xiaoyi/ucas-os-riscv-lab)

Worked through staged RISC-V teaching-OS projects covering boot flow, scheduling, synchronization, virtual memory, device I/O, and a simple file system. They form part of my foundation in concurrency, memory management, and system interfaces.

## Continued Learning

I completed the Datawhale **Hello-Agents** tutorial and published selected [notes and exercises](https://github.com/Leo-Xiaoyi/hello-agents-learning-lab). It helped me study ReAct, Plan-and-Solve, tool use, RAG, memory, evaluation, and multi-agent workflows, which I connect with the engineering work in projects such as EchoMind.

## Looking For

I'm looking for AI agent, LLM application, applied AI, and software development opportunities in New Zealand, particularly with teams that connect model capabilities and sound engineering to real user needs.

## Contact

- [LinkedIn](https://www.linkedin.com/in/xiaoyiyu-leo/)
- [Email](mailto:yxy001022@gmail.com)
