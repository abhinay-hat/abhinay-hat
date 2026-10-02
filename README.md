<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=190&color=0:0d1117,50:1f6feb,100:2ea043&text=Abhinay%20Reddy%20Padidam&fontColor=ffffff&fontSize=40&fontAlignY=36&desc=AI%20engineer%20%C2%B7%20systems%20that%20show%20their%20work&descAlignY=58&descSize=17" width="100%" alt="Abhinay Reddy Padidam"/>

<a href="https://plumb.iamabhinay.com"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=3200&pause=900&color=2EA043&center=true&vCenter=true&width=640&lines=Shows+the+SQL+it+ran.;Asks+when+a+term+is+ambiguous.;Refuses+when+the+data+can't+answer.;Runs+on+your+own+hardware." alt="Typing SVG"/></a>

<br/>

<a href="https://plumb.iamabhinay.com"><img src="https://img.shields.io/badge/plumb-live%20demo-2ea043?style=for-the-badge&logo=duckdb&logoColor=white" alt="plumb live demo"/></a>
<a href="https://iamabhinay.com"><img src="https://img.shields.io/badge/site-iamabhinay.com-1f6feb?style=for-the-badge&logo=vercel&logoColor=white" alt="website"/></a>
<a href="https://linkedin.com/in/abhinay-padidam"><img src="https://img.shields.io/badge/LinkedIn-abhinay--padidam-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:abhinaypadidam97@gmail.com"><img src="https://img.shields.io/badge/email-abhinaypadidam97-30363d?style=for-the-badge&logo=gmail&logoColor=white" alt="email"/></a>

</div>

---

```text
$ whoami
  AI engineer, Hyderabad. 3+ years shipping production AI end to end:
  LLM apps, RAG, document + speech AI, agents, and the platforms around them.

$ cat principle.txt
  The machine should be checkable. An answer you cannot verify is not an answer,
  and data that has to leave your device to be useful usually did not have to.

$ cat status.txt
  Open to relocation (Poland, Ireland, Australia) and remote roles.
```

### Shipped in production

| Area | What runs |
|---|---|
| **Call intelligence** | faster-whisper large-v3 + Qwen on a single RTX 5090. Calls transcribed and analysed on-prem, nothing sent to a cloud API. |
| **Document extraction** | Docling + Moondream + Claude over financial paperwork, with a retrieval agent that answers only from its sources. |
| **Geospatial platform** | 15,000+ properties, live. |
| **PO automation** | 22 extractors mapped to SAP fields, live since January 2025. |
| **Digital shelf** | Pricing, availability and market share across 12 marketplaces for FMCG brands. |
| **MCP server** | OAuth 2.1, serving analytics to Claude. |

### Open source

| Project | What it does | Stack |
|---|---|---|
| **[plumb](https://github.com/abhinay-hat/plumb)** · [live](https://plumb.iamabhinay.com) | Ask a spreadsheet in English. It shows the SQL it ran, asks what an ambiguous term means, or says the columns cannot answer. Routing eval 27/30, run in CI. | Python · FastAPI · DuckDB · React |
| **[DocuMind](https://github.com/abhinay-hat/DocuMind)** | PAN and Aadhaar extraction with Moondream's vision model behind FastAPI. Identity documents never leave the machine. | Python · FastAPI · Moondream |
| **[Voice-Dub](https://github.com/abhinay-hat/Voice-Dub)** | Dubs video into English in each speaker's own cloned voice, tone preserved, lips resynced. Fully local. | Python · faster-whisper · pyannote · PyTorch (CUDA) |
| **[SyncDrop](https://github.com/abhinay-hat/SyncDrop)** | OneDrive for your own hardware. macOS menu-bar app that syncs chosen folders to any drive the moment you plug it in. | Swift · SwiftUI |
| **[FinTrack](https://github.com/abhinay-hat/FinTrack)** | Offline personal finance for India. Accounts, budgets, recurring payments; data stays on the phone. | TypeScript · React Native · Expo |

### AI stack

Open-weight models first, run on my own GPU where the data should not leave the building. Frontier APIs where they earn their cost.

**Models**

<p>
<picture><source media="(prefers-color-scheme: dark)" srcset="https://unpkg.com/@lobehub/icons-static-png@latest/dark/claude-color.png"><img src="https://unpkg.com/@lobehub/icons-static-png@latest/light/claude-color.png" width="44" height="44" alt="Claude" title="Claude"></picture>&nbsp;&nbsp;
<picture><source media="(prefers-color-scheme: dark)" srcset="https://unpkg.com/@lobehub/icons-static-png@latest/dark/qwen-color.png"><img src="https://unpkg.com/@lobehub/icons-static-png@latest/light/qwen-color.png" width="44" height="44" alt="Qwen" title="Qwen"></picture>&nbsp;&nbsp;
<picture><source media="(prefers-color-scheme: dark)" srcset="https://unpkg.com/@lobehub/icons-static-png@latest/dark/meta-color.png"><img src="https://unpkg.com/@lobehub/icons-static-png@latest/light/meta-color.png" width="44" height="44" alt="Llama" title="Llama"></picture>&nbsp;&nbsp;
<picture><source media="(prefers-color-scheme: dark)" srcset="https://unpkg.com/@lobehub/icons-static-png@latest/dark/deepseek-color.png"><img src="https://unpkg.com/@lobehub/icons-static-png@latest/light/deepseek-color.png" width="44" height="44" alt="DeepSeek" title="DeepSeek"></picture>&nbsp;&nbsp;
<picture><source media="(prefers-color-scheme: dark)" srcset="https://unpkg.com/@lobehub/icons-static-png@latest/dark/mistral-color.png"><img src="https://unpkg.com/@lobehub/icons-static-png@latest/light/mistral-color.png" width="44" height="44" alt="Mistral" title="Mistral"></picture>&nbsp;&nbsp;
<picture><source media="(prefers-color-scheme: dark)" srcset="https://unpkg.com/@lobehub/icons-static-png@latest/dark/gemma-color.png"><img src="https://unpkg.com/@lobehub/icons-static-png@latest/light/gemma-color.png" width="44" height="44" alt="Gemma" title="Gemma"></picture>&nbsp;&nbsp;
<picture><source media="(prefers-color-scheme: dark)" srcset="https://unpkg.com/@lobehub/icons-static-png@latest/dark/gemini-color.png"><img src="https://unpkg.com/@lobehub/icons-static-png@latest/light/gemini-color.png" width="44" height="44" alt="Gemini" title="Gemini"></picture>&nbsp;&nbsp;
<picture><source media="(prefers-color-scheme: dark)" srcset="https://unpkg.com/@lobehub/icons-static-png@latest/dark/openai.png"><img src="https://unpkg.com/@lobehub/icons-static-png@latest/light/openai.png" width="44" height="44" alt="Whisper" title="Whisper"></picture>&nbsp;&nbsp;
</p>

<sub>Claude · Qwen · Llama · DeepSeek · Mistral · Gemma · Gemini · Whisper (faster-whisper) · Moondream · Docling</sub>

**Serving, agents, tooling**

<p>
<picture><source media="(prefers-color-scheme: dark)" srcset="https://unpkg.com/@lobehub/icons-static-png@latest/dark/huggingface-color.png"><img src="https://unpkg.com/@lobehub/icons-static-png@latest/light/huggingface-color.png" width="44" height="44" alt="Hugging Face" title="Hugging Face"></picture>&nbsp;&nbsp;
<picture><source media="(prefers-color-scheme: dark)" srcset="https://unpkg.com/@lobehub/icons-static-png@latest/dark/ollama.png"><img src="https://unpkg.com/@lobehub/icons-static-png@latest/light/ollama.png" width="44" height="44" alt="Ollama" title="Ollama"></picture>&nbsp;&nbsp;
<picture><source media="(prefers-color-scheme: dark)" srcset="https://unpkg.com/@lobehub/icons-static-png@latest/dark/vllm-color.png"><img src="https://unpkg.com/@lobehub/icons-static-png@latest/light/vllm-color.png" width="44" height="44" alt="vLLM" title="vLLM"></picture>&nbsp;&nbsp;
<picture><source media="(prefers-color-scheme: dark)" srcset="https://unpkg.com/@lobehub/icons-static-png@latest/dark/nvidia-color.png"><img src="https://unpkg.com/@lobehub/icons-static-png@latest/light/nvidia-color.png" width="44" height="44" alt="NVIDIA CUDA" title="NVIDIA CUDA"></picture>&nbsp;&nbsp;
<picture><source media="(prefers-color-scheme: dark)" srcset="https://unpkg.com/@lobehub/icons-static-png@latest/dark/langchain-color.png"><img src="https://unpkg.com/@lobehub/icons-static-png@latest/light/langchain-color.png" width="44" height="44" alt="LangChain" title="LangChain"></picture>&nbsp;&nbsp;
<picture><source media="(prefers-color-scheme: dark)" srcset="https://unpkg.com/@lobehub/icons-static-png@latest/dark/llamaindex-color.png"><img src="https://unpkg.com/@lobehub/icons-static-png@latest/light/llamaindex-color.png" width="44" height="44" alt="LlamaIndex" title="LlamaIndex"></picture>&nbsp;&nbsp;
<picture><source media="(prefers-color-scheme: dark)" srcset="https://unpkg.com/@lobehub/icons-static-png@latest/dark/mcp.png"><img src="https://unpkg.com/@lobehub/icons-static-png@latest/light/mcp.png" width="44" height="44" alt="MCP" title="MCP"></picture>&nbsp;&nbsp;
<picture><source media="(prefers-color-scheme: dark)" srcset="https://unpkg.com/@lobehub/icons-static-png@latest/dark/n8n-color.png"><img src="https://unpkg.com/@lobehub/icons-static-png@latest/light/n8n-color.png" width="44" height="44" alt="n8n" title="n8n"></picture>&nbsp;&nbsp;
</p>

<sub>Hugging Face · Ollama · vLLM · CUDA (RTX 5090) · LangChain · LlamaIndex · MCP · n8n</sub>

**ML, data, and platform**

<p><img src="https://skillicons.dev/icons?i=py,pytorch,sklearn,ts,fastapi,postgres,mongodb,react,nextjs,docker,linux,aws,gcp&perline=13" alt="ML and platform stack"/></p>

**Patterns** RAG · tool calling · multi-step agents · MCP servers · vision-language extraction · speech pipelines · golden-set evals · per-request latency and cost tracking


<img src="https://capsule-render.vercel.app/api?type=waving&height=90&section=footer&color=0:2ea043,50:1f6feb,100:0d1117" width="100%" alt=""/>
