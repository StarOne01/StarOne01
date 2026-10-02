<div align="center">

  ![Typing](https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=22&pause=1200&color=0F6B4A&center=true&vCenter=true&width=700&lines=EEE+undergrad+interested+in+systems;Learning+LLVM+and+MLIR;Coimbatore+%C2%B7+Fedora)
  
<p align="center">
  <a href="https://starone01.me">starone01.me</a> ·
  <a href="https://www.linkedin.com/in/StarOne01/">linkedin</a> ·
  <a href="https://x.com/iamstarone01">x @iamstarone01</a> ·
  <a href="mailto:ping@starone01.me">ping@starone01.me</a>
</p>

  <sub>final-year EEE @ Coimbatore · learning LLVM / MLIR</sub>

</div>

---

```mlir
// pipeline.mlir — how I think about building
func.func @starone01(%idea: !prod.prototype) -> !prod.shipped {
  %ast     = "frontend.parse"(%idea)       : (!prod.prototype) -> !ir.ast
  %lowered = "midend.lower"(%ast)          : (!ir.ast) -> !mlir.module
  %opt     = "midend.canonicalize"(%lowered): (!mlir.module) -> !mlir.module
  %bin     = "backend.emit"(%opt) {target = "prod", opt = "-O3"} : (!mlir.module) -> !prod.shipped
  return %bin : !prod.shipped
} // scroll ↓ to execute each pass
```

### about

I'm Prashanth, **StarOne01**. Final-year EEE student interested in where hardware meets software: compilers, inference, and systems around AI.

Started coding on a phone with Termux. Since then I've helped build a clinical AI system, made some small LLVM contributions, and tried out embeddings and multilingual LLM work. Currently learning MLIR.

---

### projects

|  | project | what it is |
|---|---|---|
| `medclara` | **[Medclara](https://starone01.me/#work)** — Clinical AI | Voice-first multilingual clinical docs. IndicConformer + Gemma for SOAP. Worked on arch + infra. |
| `movieslikethis` | **[MoviesLikeThis](https://movieslikethis.starone01.me)** — Embeddings | Match films by feeling, not genre. Small custom embeddings experiment. |
| `sherlock_sft` | **Sherlock SFT** — Fine-Tuning | Character LM via SFT. Spent a while tracking down a QLoRA NaN loss. |
| `bfloat16` | **[bfloat16](https://github.com/StarOne01/bfloat16)** — Numerics | Small C++ bfloat16 implementation. |
| `phrasenux` | **[PhraseNuX](https://github.com/StarOne01/PhraseNuX)** — origin | C++ CLI password manager, AES, zero deps. Early project, written on a phone. |

---

### stack

<p align="left">
  
  <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=go,py,cpp,ts,nextjs,postgres,aws,gcp,docker,linux&perline=10" alt="stack" /></a>

</p>

```
Languages  →  Go · Python · C++ · TS / Next.js
Systems    →  LLVM · MLIR · Compilers · Local Inference · CUDA (learning)
ML / AI    →  SFT / QLoRA · ASR · Embeddings · RAG
Infra      →  AWS · GCP · Postgres · Qdrant · Fedora
```

---

### currently

- Learning MLIR dialects + passes, building on X86 + Sema work
- Playing with local LLM inference, Ollama internals
---

<div align="center">
  <sub>Coimbatore, India </sub>
  <br/>
  <sub><a href="https://starone01.me">starone01.me</a> · <a href="https://www.linkedin.com/in/StarOne01/">linkedin</a> · <a href="https://x.com/iamstarone01">x</a> · <a href="mailto:ping@starone01.me">ping@starone01.me</a></sub>

</div>
