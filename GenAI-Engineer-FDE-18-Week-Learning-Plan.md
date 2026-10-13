# GenAI Engineer & FDE 18-Week Learning Plan

Oct 13, 2026 · Simran

## How to use this plan

This plan makes you job-ready for GenAI Developer / AI Engineer roles by week 12, then adds the Forward Deployed Engineer (FDE) layer by week 18. It assumes about 10–12 hours a week alongside a full-time job.

**Weekly routine**

- Weekdays (1 hour on 4 days): concepts, courses and docs.
- Weekend (6–8 hours): building. Every week ends with something pushed to GitHub.
- Throughout: build with an AI coding assistant, and post short LinkedIn updates about what you build.

**Milestones**

- Week 12: start applying to GenAI Developer and AI Engineer roles.
- Week 18: start applying to Forward Deployed, AI Deployment and Applied AI Engineer roles.

**How links work in this plan**

GitHub repos, courses and articles link straight to the page. Where a YouTube link says "(YouTube search)", it opens YouTube results for that exact channel and video, so you always land on the current upload.

**Two master courses to keep open throughout**

- [Microsoft — Generative AI for Beginners (21 lessons)](https://github.com/microsoft/generative-ai-for-beginners): concept and build lessons with code in Python and TypeScript.
- [Krish Naik — Data Science & GenAI playlist index](https://github.com/krishnaik06/Data-Science-Gen-AI-Playlist-2024): links his YouTube playlists on LangChain, LlamaIndex, fine-tuning, AWS Bedrock and end-to-end GenAI projects.

## Phase 1: Foundations (weeks 1–3)

By the end of week 3 you write clean Python services and call LLM APIs with reliable, structured output.

### Week 1: Production Python and Git

**Topics:** type hints, Pydantic, async/await, error handling, virtual environments, project structure, Git branches and pull requests.

**Resources**

- YouTube: [Corey Schafer — Python OOP tutorials](https://www.youtube.com/results?search_query=Corey+Schafer+Python+OOP+tutorial) (YouTube search)
- YouTube: [ArjanCodes — Pydantic and clean project structure](https://www.youtube.com/results?search_query=ArjanCodes+Pydantic) (YouTube search)
- YouTube: [CodeWithHarry — Git and GitHub tutorial (Hindi)](https://www.youtube.com/results?search_query=CodeWithHarry+git+github+tutorial) (YouTube search)
- Book: [Pro Git (free online book)](https://git-scm.com/book)

**Build:** turn one of your MSc notebooks into a clean Python package on GitHub.

### Week 2: APIs and FastAPI

**Topics:** REST, FastAPI, request/response models, environment variables and secrets, retries and rate limits.

**Resources**

- Docs: [Official FastAPI tutorial](https://fastapi.tiangolo.com/tutorial/)
- YouTube: [freeCodeCamp — FastAPI course for beginners](https://www.youtube.com/results?search_query=freeCodeCamp+FastAPI+course+for+beginners) (YouTube search)
- YouTube: [CampusX — FastAPI (Hindi)](https://www.youtube.com/results?search_query=CampusX+FastAPI) (YouTube search)

**Build:** a small FastAPI service with 2–3 endpoints.

### Week 3: How LLMs work, calling APIs, prompting

**Topics:** tokens, context windows, temperature, embeddings, hallucination; calling the OpenAI, Claude and Gemini APIs; running a local model with Ollama; system prompts, few-shot prompting, structured JSON output validated with Pydantic.

**Resources**

- YouTube: [Andrej Karpathy — [1hr Talk] Intro to Large Language Models](https://www.youtube.com/watch?v=zjkBMFhNj_g)
- YouTube: [Andrej Karpathy — Deep Dive into LLMs like ChatGPT](https://www.youtube.com/results?search_query=Andrej+Karpathy+Deep+Dive+into+LLMs+like+ChatGPT) (YouTube search)
- GitHub: [Anthropic courses — API fundamentals, prompt engineering, prompt evaluations, tool use](https://github.com/anthropics/courses)
- GitHub: [Microsoft Generative AI for Beginners — lessons 1–6](https://github.com/microsoft/generative-ai-for-beginners)
- Setup: [Google AI Studio (free Gemini API key)](https://aistudio.google.com/) and [Ollama (free local models)](https://ollama.com/)

**Build:** a script that extracts structured fields from messy text and validates them with Pydantic.

## Phase 2: Core GenAI engineering (weeks 4–8)

By the end of week 8 you can build, evaluate and deploy a RAG and agent system on Azure, which covers the core of most Indian GenAI job descriptions.

### Week 4: RAG from scratch

**Topics:** document loading, chunking strategies, embeddings, vector databases (Chroma, FAISS), retrieval and generation.

**Resources**

- GitHub: [LangChain — RAG From Scratch notebooks](https://github.com/langchain-ai/rag-from-scratch)
- YouTube: [LangChain — RAG From Scratch playlist](https://www.youtube.com/results?search_query=LangChain+RAG+From+Scratch) (YouTube search)
- Course: [DeepLearning.AI free short courses](https://learn.deeplearning.ai/) — "LangChain: Chat with Your Data" and "Building and Evaluating Advanced RAG"

**Build:** a RAG app with no framework: Python, an embedding model and Chroma.

### Week 5: Advanced RAG and Azure AI Search

**Topics:** LangChain or LlamaIndex, hybrid search, re-ranking, metadata filtering, query rewriting, Azure AI Search as a vector store.

**Resources**

- YouTube: Krish Naik's LangChain and LlamaIndex playlists, linked from his [GenAI playlist index](https://github.com/krishnaik06/Data-Science-Gen-AI-Playlist-2024)
- Microsoft Learn: [Azure AI Engineer (AI-102) free learning path](https://learn.microsoft.com/en-us/credentials/certifications/azure-ai-engineer/) — RAG and Azure AI Search modules only for now

**Build:** rebuild your week 4 app with LangChain and add hybrid search.

### Week 6: Evaluation and responsible AI

**Topics:** test sets, faithfulness and relevance metrics, LLM-as-a-judge, tracing; hallucination, bias and safety testing.

**Resources**

- Article: [Hamel Husain — Your AI Product Needs Evals](https://hamel.dev/blog/posts/evals/)
- Docs: [Ragas — RAG evaluation metrics](https://docs.ragas.io/) and [Langfuse — open-source tracing](https://langfuse.com/docs)
- GitHub: [Anthropic courses — "Prompt evaluations" course](https://github.com/anthropics/courses)
- GitHub: [Microsoft Generative AI for Beginners — lessons 3 (responsible AI) and 13 (security)](https://github.com/microsoft/generative-ai-for-beginners)

**Build:** an evaluation report for your RAG app with at least 30 test questions, including safety cases.

### Week 7: Tool calling, agents, LangGraph and MCP

**Topics:** function calling, agent loops, workflows vs agents, LangGraph state and memory, Model Context Protocol (MCP).

**Resources**

- Article: [Anthropic — Building Effective Agents](https://www.anthropic.com/research/building-effective-agents)
- Course: [LangChain Academy — Introduction to LangGraph (free)](https://academy.langchain.com/)
- GitHub: [Microsoft — AI Agents for Beginners](https://github.com/microsoft/ai-agents-for-beginners)
- GitHub: [Microsoft — MCP for Beginners](https://github.com/microsoft/mcp-for-beginners)

**Build:** an agent that queries a SQL database and calls one external API.

### Week 8: Deployment, CI/CD and cloud

**Topics:** Docker, Azure deployment (Azure OpenAI, Azure AI Foundry, Container Apps), GitHub Actions CI/CD, logging, cost tracking, caching, basic AWS Bedrock.

**Resources**

- YouTube: [TechWorld with Nana — Docker tutorial for beginners](https://www.youtube.com/results?search_query=TechWorld+with+Nana+Docker+tutorial+for+beginners) (YouTube search)
- YouTube: [TechWorld with Nana — GitHub Actions tutorial](https://www.youtube.com/results?search_query=TechWorld+with+Nana+GitHub+Actions+tutorial) (YouTube search)
- Docs: [GitHub Actions documentation](https://docs.github.com/en/actions)
- YouTube: Krish Naik's AWS Bedrock playlist, linked from his [GenAI playlist index](https://github.com/krishnaik06/Data-Science-Gen-AI-Playlist-2024)

**Build:** Dockerize your RAG app, deploy it to Azure, and add a GitHub Actions workflow that runs tests. Activate your Azure free account this week, not earlier.

## Phase 3: Gaps from Indian job descriptions (weeks 9–10)

Indian GenAI and FDE postings often ask for a simple frontend and some fine-tuning, so these two weeks close those gaps.

### Week 9: JavaScript/TypeScript and React basics

**Topics:** JS fundamentals, TypeScript basics, React components and state, calling a backend API, a simple chat UI.

**Resources**

- Docs: [javascript.info — The Modern JavaScript Tutorial](https://javascript.info/)
- Docs: [React — official tutorial](https://react.dev/learn)
- Course: [Full Stack Open — parts 0–2 only](https://fullstackopen.com/en/)
- GitHub: [Microsoft — Web Dev for Beginners](https://github.com/microsoft/Web-Dev-For-Beginners)
- YouTube: [CodeWithHarry — JavaScript course (Hindi)](https://www.youtube.com/results?search_query=CodeWithHarry+JavaScript+course) (YouTube search)
- YouTube: [Traversy Media — React crash course](https://www.youtube.com/results?search_query=Traversy+Media+React+crash+course) (YouTube search)

**Build:** a React chat interface connected to your FastAPI backend.

### Week 10: PyTorch and fine-tuning

**Topics:** PyTorch basics, Hugging Face Transformers, LoRA and QLoRA, when fine-tuning beats RAG and when it doesn't.

**Resources**

- Course: [Hugging Face LLM Course (free)](https://huggingface.co/learn/llm-course/chapter1/1) — chapters 1–3, then the fine-tuning chapters
- GitHub: [Unsloth — free Colab fine-tuning notebooks](https://github.com/unslothai/notebooks)
- Docs: [PyTorch — Learn the Basics](https://pytorch.org/tutorials/beginner/basics/intro.html)
- YouTube: [Andrej Karpathy — Neural Networks: Zero to Hero (first 2 videos)](https://www.youtube.com/results?search_query=Andrej+Karpathy+Neural+Networks+Zero+to+Hero) (YouTube search)
- YouTube: Krish Naik's LLM fine-tuning playlist, linked from his [GenAI playlist index](https://github.com/krishnaik06/Data-Science-Gen-AI-Playlist-2024)

**Build:** fine-tune a small open model on a narrow task, such as classifying grocery support tickets, using a free Colab GPU.

## Phase 4: First project and job applications (weeks 11–12)

Week 11 produces your flagship GenAI project, and week 12 is when you start applying.

### Week 11: Project 1 — a text-to-SQL agent

**Idea:** "Ask questions about grocery replenishment data in plain English." Use an agent that writes and runs SQL, a React frontend, Azure deployment, CI/CD and an evaluation report.

**Resources**

- Docs: [LangChain docs](https://python.langchain.com/docs/) — search for the SQL question-answering tutorial
- GitHub: [Microsoft — AI Agents for Beginners](https://github.com/microsoft/ai-agents-for-beginners) and [MCP for Beginners](https://github.com/microsoft/mcp-for-beginners)
- GitHub: [Microsoft — Mastering GitHub Copilot](https://github.com/microsoft/Mastering-GitHub-Copilot-for-Paired-Programming) (Copilot has a free plan)

**Deliverable:** a README with an architecture diagram, evaluation results and limitations.

### Week 12: Interview prep and applications

**Topics:** explaining RAG, agents and evaluation out loud; GenAI system design, such as "design a document Q&A system for a bank".

**Resources**

- Article: [Eugene Yan — Patterns for Building LLM-based Systems & Products](https://eugeneyan.com/writing/llm-patterns/)
- Blog: [Chip Huyen](https://huyenchip.com/blog/) — read "Building A Generative AI Platform"
- YouTube: [Exponent — system design mock interviews](https://www.youtube.com/results?search_query=Exponent+system+design+mock+interview) (YouTube search)
- YouTube: [Krish Naik — GenAI interview questions](https://www.youtube.com/results?search_query=Krish+Naik+generative+AI+interview+questions) (YouTube search)

**Action:** update your CV and LinkedIn with a GenAI Engineer headline and your projects, then start applying to GenAI Developer and AI Engineer roles in Germany and India.

## Phase 5: The FDE layer (weeks 13–17)

These five weeks add what makes an FDE different from an AI Engineer: messy-data integration, enterprise systems, problem scoping and customer skills. Keep applying to GenAI roles while you learn them.

### Week 13: Advanced SQL and data integration

**Topics:** window functions, CTEs, query optimization; cleaning messy data from PDFs, Excel and APIs into one pipeline; data warehouse basics (Snowflake, BigQuery, Databricks).

**Resources**

- Practice: [SQLBolt — interactive SQL lessons](https://sqlbolt.com/)
- Practice: [LeetCode — SQL 50 study plan (free)](https://leetcode.com/studyplan/top-sql-50/)
- YouTube: [Alex The Analyst — advanced SQL](https://www.youtube.com/results?search_query=Alex+The+Analyst+advanced+SQL) (YouTube search)

### Week 14: Enterprise systems and security

**Topics:** what CRMs, ERPs and ticketing tools do (Salesforce, SAP, Jira); OAuth, webhooks, reading unfamiliar API docs; PII handling, GDPR, private cloud deployment.

**Resources**

- YouTube: [ByteByteGo — OAuth 2.0 explained](https://www.youtube.com/results?search_query=ByteByteGo+OAuth+2.0+explained) (YouTube search)
- YouTube: [freeCodeCamp — APIs for beginners](https://www.youtube.com/results?search_query=freeCodeCamp+APIs+for+beginners) (YouTube search)
- GitHub: [Microsoft Generative AI for Beginners — lesson 13, securing AI apps](https://github.com/microsoft/generative-ai-for-beginners)

**Practice:** connect an agent to a free developer sandbox, such as Jira or HubSpot.

### Week 15: Problem scoping and business thinking

**Topics:** turning vague client requests into scoped plans, success metrics, rough ROI estimates, AI use cases by industry (banking, retail, logistics), deciding when AI is not needed.

**Resources**

- YouTube: [Exponent — product sense and case interviews](https://www.youtube.com/results?search_query=Exponent+product+sense+interview) (YouTube search)
- Article: [Anthropic — Building Effective Agents](https://www.anthropic.com/research/building-effective-agents) (reread with a client lens: workflow or agent?)
- Read real FDE job descriptions from Palantir, OpenAI and Bengaluru startups on LinkedIn and Naukri.

**Practice:** one case question every two days, out loud and recorded.

### Week 16: Project 2 — a client-engagement project

**Idea:** a supplier invoice checker for a grocery company. It takes messy PDFs and CSVs, uses an agent integrated with 2–3 tools, and includes evaluation and an ROI estimate.

**Deliverable:** a README written as a client report (problem, approach, results, ROI, next steps) plus a 3-minute demo video recorded with [OBS Studio (free)](https://obsproject.com/).

### Week 17: Customer skills, a workshop, STAR stories

**Topics:** explaining tradeoffs to non-technical people, running demos, managing expectations.

**Actions**

- Write one blog post on [Hashnode](https://hashnode.com/) or Medium, or record a short workshop video explaining RAG simply.
- Prepare 5 STAR stories from Infosys client work, Picnic, Flink/Getir and your MSc.
- YouTube: [Exponent — behavioral interview STAR method](https://www.youtube.com/results?search_query=Exponent+behavioral+interview+STAR+method) (YouTube search)

## Phase 6: FDE interview readiness (week 18)

Week 18 rehearses the four FDE interview rounds, then you start applying to FDE roles.

- [ ] Practical coding round: Python and data manipulation, timed.
- [ ] Decomposition case: a vague client problem scoped into a first version, out loud.
- [ ] System design: an AI system for a specific client, covering data flow, model choice, evaluation, security and deployment.
- [ ] Behavioral round: your 5 STAR stories.
- [ ] Live build: a small RAG app or data pipeline in 2–3 hours.
- [ ] Apply to Forward Deployed, AI Deployment and Applied AI Engineer roles.

**Resources**

- YouTube: [Exponent — mock interviews](https://www.youtube.com/results?search_query=Exponent+mock+interview) (YouTube search)
- Practice partners: free peer communities such as the Discord linked from [Microsoft Generative AI for Beginners](https://github.com/microsoft/generative-ai-for-beginners), or LinkedIn GenAI groups.

## What's free and what costs money

About 95% of this plan is free; a realistic total is $10–15 (about ₹850–1,300) of API usage over 18 weeks.

| Need | Free option | Cost | When to use |
| --- | --- | --- | --- |
| LLM API (main) | [Google AI Studio — Gemini API free tier](https://aistudio.google.com/) | Free | Weeks 3–7, everyday building |
| Local models | [Ollama](https://ollama.com/) | Free (needs ~16 GB RAM for small models) | RAG and agent practice |
| Fast open-model testing | [Groq](https://console.groq.com/) | Free tier, rate-limited | Optional |
| Open models + fine-tuning | [Hugging Face](https://huggingface.co/) and Google Colab free GPU | Free | Week 10 |
| OpenAI / Anthropic API | [Anthropic courses](https://github.com/anthropics/courses) use the cheapest model | ~$10–15 total | Week 3 courses; projects that name OpenAI |
| Cloud | [Azure free account](https://azure.microsoft.com/free/) — $200 credit for 30 days | Free if timed well | Activate in week 8 to cover weeks 8–11 |
| Model catalog on Azure | [Azure AI Foundry](https://ai.azure.com/) | Uses Azure credit | Deployed projects |
| AI coding assistant | [GitHub Copilot free plan](https://github.com/features/copilot) | Free | Throughout |

**Optional costs (not needed to get hired)**

- AI-102 certification exam: the [learning path](https://learn.microsoft.com/en-us/credentials/certifications/azure-ai-engineer/) is free, but the exam is paid. Watch for Microsoft promotions with free or discounted vouchers.
- Paid certificates on Coursera or DeepLearning.AI specializations.
- Paid coding tools (Cursor Pro, Claude Code subscriptions) and Colab Pro.

**Note:** GitHub Models is no longer an option; it was [fully retired on July 30, 2026](https://docs.github.com/en/github-models). In the Microsoft Generative AI for Beginners course, skip the GitHub Models setup steps and use the OpenAI API, Azure OpenAI, Gemini or Ollama instead.

Set a budget alert on every cloud and API account before you start.
