## Rafael Viotti

**AI Engineer — infrastructure, retrieval, and the measurement layer in between.**

I came to AI from operations. Hardware repair, then field support, then monitoring a
transport company's network, then analysing operational graphs and integrity signals at
a gaming operator — before six months as sole architect of a company's AI platform.

That order shapes how I build. Most people arrive at RAG from the model side and
discover reliability later. I arrived from the side where things page you at 3am, so I
build measurement and recovery first, and treat a vector index as derived, rebuildable
state rather than something precious.

### What I work on

- **Retrieval systems** — chunking, embeddings, vector search, and the evaluation most
  RAG deployments never get around to
- **Self-hosted AI infrastructure** — Qdrant, Ollama, LangFuse, LlamaIndex, running on
  hardware I administer myself
- **Agent orchestration** — bounded delegation, isolated contexts, fail-closed by default
- **Operations** — Linux, nginx, VPN-restricted boundaries, and recovery drills that are
  actually rehearsed

### Currently

Building **ragfit** — a benchmark that measures what a RAG stack actually does on *your*
corpus and *your* machine. Every tutorial says "install Ollama and a vector database";
none tells you whether it will work on your hardware, with your documents, in your
language. Brazilian Portuguese first, because that is where the gap between what is
asserted and what is measured is widest.

### A note on this profile

Most of what I build lives in private repositories — client work, personal data, or
infrastructure configuration that has no business being public. What is here is what can
honestly be here. I am glad to walk through the rest on a call.

---

📍 Belo Horizonte, Brazil · working across US and European timezones
✉️ rafaelviotti@gmail.com · [LinkedIn](https://www.linkedin.com/in/rafael-viotti-86364b1a1)
