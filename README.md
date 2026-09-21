<div align="center">

  ![Typing](https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=22&pause=1200&color=0F6B4A&center=true&vCenter=true&width=700&lines=Systems+Engineer%2C+hardware+to+software;LLVM+contributor%2C+now+deep+in+MLIR;Building+compilers%2C+not+just+using+them;Coimbatore+%C2%B7+Fedora+%C2%B7+ship+at+-O3)
  
<p align="center">
  <a href="https://starone01.me">starone01.me</a> ·
  <a href="https://www.linkedin.com/in/StarOne01/">linkedin</a> ·
  <a href="https://x.com/iamstarone01">x @iamstarone01</a> ·
  <a href="mailto:ping@starone01.me">ping@starone01.me</a>
</p>

  <sub>final-year EEE @ Coimbatore · self-taught on a phone through Termux · now deep in LLVM / MLIR</sub>

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

I'm Prashanth, known online as **StarOne01**. Final-year Electrical and Electronics Engineering student, but most of what I do lives in the gap between hardware and software: **compilers, model inference, and the systems that make AI run efficiently on real silicon.**

Self-taught, starting on a phone through Termux before I ever owned a laptop. Since then: a production multilingual clinical AI system, **LLVM contributions**, a film engine on custom embeddings, and multilingual LLM research. Now going deep on **compiler internals and MLIR**, the layer where models actually meet hardware.

> *I wrote my first production code on a phone. No laptop. Just Termux, a cracked screen, and WiFi that dropped every twenty minutes. People said wait for the right setup. I didn't.*

---

### what i ship

|  | project | what it is |
|---|---|---|
| `op @medclara` | **[Medclara](https://starone01.me/#work)** — Clinical AI · Founding Engineer | Voice-first multilingual clinical docs. **IndicConformer** ASR + fine-tuned **Gemma** for SOAP notes. Architecture, infra, and compliance, solo. |
| `op @movieslikethis` | **[MoviesLikeThis](https://movieslikethis.starone01.me)** — Embeddings | *The films that stay with you.* Same feeling, different film, matched by **emotional experience, not genre.** Custom embeddings + content fingerprinting. |
| `op @sherlock_sft` | **Sherlock SFT** — Fine-Tuning | Character-consistent LM via SFT. Iterated on data quality and debugged a **QLoRA NaN loss down to root cause.** |
| `op @bfloat16` | **[bfloat16](https://github.com/StarOne01/bfloat16)** — Numerics | Lightweight **C++** impl of Google Brain's bfloat16. Same 8-bit exponent as FP32, 7-bit mantissa, the format ML hardware actually speaks. |
| `op @phrasenux` | **[PhraseNuX](https://github.com/StarOne01/PhraseNuX)** — where it started | C++ CLI password manager, **AES encryption**, zero deps, written entirely on a phone. |

---

### open source — llvm

Contributions across the stack, now pushing into MLIR:

- **Backend / codegen:** X86 target-specific lowering for `_Float16` ops — `FABS`, `FNEG`, `FCOPYSIGN` at instruction-selection level.
- **Frontend:** New Clang diagnostic in the Sema layer for function-like macro references requiring parentheses, through full review and CI.
- **libc docs:** Series of POSIX header documentation additions (`dirent`, `unistd`, `termios`, `sys/stat`, `sys/wait`, `netinet/in` …), each through review.

> *Started with docs, proved out backend and frontend, now going deeper into MLIR. Progression over assertion.*

→ All of it lives at **[github.com/StarOne01](https://github.com/StarOne01)**

---

### stack — loaded dialects

<p align="left">
  
  <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=go,py,cpp,ts,nextjs,postgres,aws,gcp,docker,linux&perline=10" alt="stack" /></a>

</p>

```
Languages       →  Go · Python · C++ ★ · TypeScript / Next.js
Systems         →  LLVM · MLIR (in progress) · Compilers · System Design · Local LLM Inference · CUDA (in progress)
ML / AI         →  SFT / QLoRA · ASR Pipelines · Embeddings · RAG
Infra & Data    →  AWS · GCP · PostgreSQL · Qdrant · Fedora
```

---

### currently

- Deepening into **MLIR dialects and passes**, building on the X86 backend + Clang Sema foundation
- **Local LLM inference**, deploying open models in production, Ollama internals, scheduling engines
---

<div align="center">
  <sub>— built on Fedora · shipped at -O3 · Coimbatore, India —</sub>
  <br/>
  <sub><a href="https://starone01.me">starone01.me</a> · <a href="https://www.linkedin.com/in/StarOne01/">linkedin</a> · <a href="https://x.com/iamstarone01">x</a> · <a href="mailto:ping@starone01.me">ping@starone01.me</a></sub>

</div>
