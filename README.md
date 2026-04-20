<h1 align="center">Anand Okade</h1>
<h3 align="center">AI Engineer | Production LLM Systems | Agentic Infrastructure</h3>

<p align="center">
  <img src="https://user-images.githubusercontent.com/90754521/232019995-624fdcae-6240-4d88-af1c-f7215b55a4e3.png" alt="Artboard 1" />
</p>

<p align="center">
  <a href="https://github.com/AlgoRexx">
    <img src="https://komarev.com/ghpvc/?username=AlgoRexx&label=Profile%20views&color=0e75b6&style=flat" alt="profile views" />
  </a>
  <a href="https://linkedin.com/in/anand-okade-a9614a220">
    <img src="https://img.shields.io/badge/LinkedIn-Anand%20Okade-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="linkedin" />
  </a>
  <a href="mailto:anandokade03@gmail.com">
    <img src="https://img.shields.io/badge/Email-anandokade03%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white" alt="email" />
  </a>
</p>

<p align="center">Building AI systems that move from research to reliable production.</p>

<hr/>

<h2>Impact Snapshot</h2>
<blockquote>
  <p><strong>Terminal</strong></p>
  <pre><code class="language-bash">$ section --show impact_snapshot</code></pre>
</blockquote>

<ul>
  <li>Fine-tuned <code>Qwen3-8B</code> on a 75k sustainability dataset: <strong>78.3% -&gt; 89.7%</strong> domain accuracy (internal eval).</li>
  <li>Built distributed LLM infrastructure that reduced evaluation costs by <strong>~50%</strong> through architecture and orchestration changes.</li>
  <li>Built multi-agent systems that generate structured research outputs from unstructured documents in minutes.</li>
  <li>Designed retrieval and decision systems with traceable outputs and auditability.</li>
</ul>

<hr/>

<h2>Projects</h2>

<h3>OpenBloom Terminal — Institutional Equity Intelligence Platform</h3>
<blockquote>
  <p><strong>Terminal</strong></p>
  <pre><code class="language-bash">$ cd projects/openbloom && cat OVERVIEW.md</code></pre>
</blockquote>
<p>
Most equity dashboards force analysts to combine disconnected signals manually. OpenBloom runs the full pipeline from one terminal-style interface.
It combines factor analytics, sentiment, ownership intelligence, geopolitical risk, and regime detection into a unified composite signal.
Engines run as independently scalable services with integrity gates and audit trails so outputs are traceable to source data.
</p>

<p><strong>Tech Stack</strong></p>
<p>
  <img src="https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/FastAPI-009688.svg?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/React-20232A.svg?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192.svg?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Neo4j-008CC1.svg?style=for-the-badge&logo=neo4j&logoColor=white" alt="Neo4j" />
  <img src="https://img.shields.io/badge/Redis-DC382D.svg?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/Celery-37814A.svg?style=for-the-badge&logo=celery&logoColor=white" alt="Celery" />
  <img src="https://img.shields.io/badge/Docker-2496ED.svg?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/AWS-232F3E.svg?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS" />
</p>

<hr/>

<h3>SAGE — Intraday Options Decision System</h3>
<blockquote>
  <p><strong>Terminal</strong></p>
  <pre><code class="language-bash">$ cd projects/sage && cat SYSTEM.md</code></pre>
</blockquote>
<p>
Discretionary options trading breaks when execution discipline collapses. SAGE acts as a hard risk gate between trader intent and broker execution.
It ingests live spot, strike-wise LTP/OI, and order-book depth, computes per-strike Greeks/IV via a custom Black-Scholes engine, and adds chart context through local vision inference.
A deterministic 5-stage decision funnel emits <code>TRADE / KILL / STANDBY</code>, with decisions persisted in WAL-backed logs.
</p>

<p><strong>Tech Stack</strong></p>
<p>
  <img src="https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Playwright-2EAD33.svg?style=for-the-badge&logo=playwright&logoColor=white" alt="Playwright" />
  <img src="https://img.shields.io/badge/Electron-2B2E3A.svg?style=for-the-badge&logo=electron&logoColor=9FEAF9" alt="Electron" />
  <img src="https://img.shields.io/badge/SQLite-07405E.svg?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/JSONL-000000.svg?style=for-the-badge&logoColor=white" alt="JSONL" />
  <img src="https://img.shields.io/badge/MLX-111111.svg?style=for-the-badge&logo=apple&logoColor=white" alt="MLX" />
</p>

<hr/>

<h3>RAG-KG-AI — Relationship-Aware Retrieval Pipeline</h3>
<blockquote>
  <p><strong>Terminal</strong></p>
  <pre><code class="language-bash">$ cd projects/rag-kg-ai && cat ARCHITECTURE.md</code></pre>
</blockquote>
<p>
Vanilla RAG returns top chunks but misses cross-document structure. RAG-KG-AI combines semantic retrieval with graph reasoning to return connected context.
It extracts entities/relations, stores semantic vectors, maps graph links, and ranks using relevance + connection strength + recency.
</p>

<p><strong>Tech Stack</strong></p>
<p>
  <img src="https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/LangGraph-121D33.svg?style=for-the-badge&logo=langchain&logoColor=white" alt="LangGraph" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FF9D00.svg?style=for-the-badge&logo=huggingface&logoColor=white" alt="Hugging Face" />
  <img src="https://img.shields.io/badge/Milvus-00A1EA.svg?style=for-the-badge&logoColor=white" alt="Milvus" />
  <img src="https://img.shields.io/badge/Neo4j-008CC1.svg?style=for-the-badge&logo=neo4j&logoColor=white" alt="Neo4j" />
  <img src="https://img.shields.io/badge/FastAPI-009688.svg?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Docker-2496ED.svg?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
</p>

<hr/>

<h3>investment-memo — AI Investment Memo Generation Pipeline</h3>
<blockquote>
  <p><strong>Terminal</strong></p>
  <pre><code class="language-bash">$ cd projects/investment-memo && python start_api.py</code></pre>
</blockquote>
<p>
Investment memo writing is repetitive and inconsistent across analysts. This pipeline automates memo generation from templates and source documents.
It parses DOCX placeholders, executes multi-prompt workflows (company, market, financials, strategy, risk), and fills structured outputs via an API backend with optional research enrichment.
</p>

<p><strong>Tech Stack</strong></p>
<p>
  <img src="https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/FastAPI-009688.svg?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Gemini-4285F4.svg?style=for-the-badge&logo=google&logoColor=white" alt="Gemini API" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C.svg?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/Tavily-0A84FF.svg?style=for-the-badge&logoColor=white" alt="Tavily" />
  <img src="https://img.shields.io/badge/python--docx-2B579A.svg?style=for-the-badge&logo=microsoftword&logoColor=white" alt="python-docx" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E.svg?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/AWS%20S3-569A31.svg?style=for-the-badge&logo=amazon-s3&logoColor=white" alt="AWS S3" />
</p>

<hr/>

<h3>Deepfake — Multi-Modal Deepfake Detection Interface</h3>
<blockquote>
  <p><strong>Terminal</strong></p>
  <pre><code class="language-bash">$ cd projects/deepfake && streamlit run UI.py</code></pre>
</blockquote>
<p>
Deepfake workflows are usually split by modality. This project provides a single interface to run video/image/audio detection paths.
It uses a Streamlit control layer to orchestrate inference scripts, manage uploads, and display prediction outputs for analysis.
</p>

<p><strong>Tech Stack</strong></p>
<p>
  <img src="https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8.svg?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C.svg?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/Conda-44A833.svg?style=for-the-badge&logo=anaconda&logoColor=white" alt="Conda" />
</p>

<hr/>

<h2>Experience</h2>
<blockquote>
  <p><strong>Terminal</strong></p>
  <pre><code class="language-bash">$ cat experience.log</code></pre>
</blockquote>

<h3>AI Engineer — VAIA Investment Advisory LLP </h3>
<ul>
  <li>Fine-tuning and RL training workflows (<code>GRPO</code>) for domain-adapted reasoning and tool use.</li>
  <li>Reasoning distillation pipelines to transfer large-model capability to smaller deployable models.</li>
  <li>Built secure workflow systems for investment operations and research automation.</li>
  <li>Deployed LLM systems across AWS and Modal with cost-aware scaling.</li>
</ul>


<hr/>

<h2>Evaluation &amp; Benchmarking</h2>
<blockquote>
  <p><strong>Terminal</strong></p>
  <pre><code class="language-bash">$ benchmark --list</code></pre>
</blockquote>
<p>
  <code>MMLU</code> <code>HellaSwag</code> <code>BigBench</code> <code>IFEVAL</code> <code>F1</code> <code>Perplexity</code>
  <code>DeepEval</code> <code>BLEU</code> <code>ROUGE</code>
</p>

<hr/>

<h2>Education</h2>
<blockquote>
  <p><strong>Terminal</strong></p>
  <pre><code class="language-bash">$ cat education.txt</code></pre>
</blockquote>
<ul>
  <li><strong>B.E. in AI &amp; ML</strong> — RNS Institute of Technology (<code>2021 - 2025</code>)</li>
  <li><strong>Pre-University</strong> — Sadhana College (<code>2019 - 2021</code>)</li>
</ul>
