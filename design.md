# Portfolio Design Specification

## Stack
- Single `index.html` file
- Google Font: Inter
- Vanilla CSS, no frameworks

## Colors
- Background: `#0D0D0D`
- Primary Text: `#F0EEE6`
- Surface: `#111111`
- Borders: `#1A1A1A`
- Muted Text: `#555`
- Subtle Elements: `#333`
- No accent color

## Typography
- **Hero:** Inter 900, 96px, -0.05em tracking
- **Section Headings:** Inter 700
- **Body:** Inter 400, 13px, 1.7 line-height
- **Labels:** 11px uppercase, 0.12em letter-spacing

## Layout & Components
- **Sticky Nav:** Name on left; Work, Projects, About, Contact on right
- **Hero:** "SANJAY" (96px) top-left; "SRIRAM" (96px) vertical right side (rotated 180deg)
- **Borders:** 0.5px `#1A1A1A` (no shadows, no gradients)
- **Experience:** 3-column grid (year / content / badge)
- **Projects:** 2x3 card grid with hard borders
- **About:** 2-column (statement left, facts right)
- **Contact:** Large "Let's talk." left, links right
- **Rules:** Zero border-radius (except 2px max on tags), square corners everywhere.

## Content to include:
### Experience
1. **Rox, Engineering Intern (2026, Current):** Building revenue agents, agent orchestration and context retrieval pipelines.
2. **Ernst & Young, Applied ML Intern (2025):** MCP server with LangGraph, hybrid RAG (BM25 + dense vector) cutting turnaround from days to under an hour, autonomous document extraction agent.
3. **Boxsy.io, Applied AI Sub-Team Lead (2025):** AI investor update agent cutting drafting by 70%, pgvector similarity search, Vertex AI workflows.

### Projects
1. **Sift:** Multimodal local search, Qwen3-VL, CLAP adapter, Qdrant, BLAKE3 indexing.
2. **KernelFusion:** CUDA + Triton kernel fusion benchmarking, Nsight profiling, torch.compile study.
3. **LPCVC 2026 (In Progress):** Competition entry, MobileCLIP-S2, 35ms latency constraint on Qualcomm XR2 Gen 2, AIMET INT8 quantization, WiSE-FT.
4. **Outsync:** LangGraph agentic email generation, RAG over resume with ChromaDB, deployed at outsync.vercel.app.
5. **Glimpse:** AI newsletter SaaS, Celery parallel summarization, ElevenLabs TTS, deployed at glimpse-digest.vercel.app.
6. **Backtest Engine:** Modular Python backtester, dynamic slippage, Sharpe/Sortino/drawdown metrics, Streamlit UI.
