<div align="center">

  ![Typing](https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=22&pause=1200&color=3B82F6&center=true&vCenter=true&width=700&lines=EEE+undergrad+who+wandered+into+compilers;Contributing+to+LLVM+%2F+MLIR;Identifies+identifiers+%28pun+intended%29;Coimbatore+%C2%B7+Fedora)

<p align="center">
  <a href="https://starone01.me">starone01.me</a> ·
  <a href="https://www.linkedin.com/in/StarOne01/">linkedin</a> ·
  <a href="https://x.com/iamstarone01">x @iamstarone01</a> ·
  <a href="mailto:ping@starone01.me">ping@starone01.me</a>
</p>

  <sub>final-year EEE @ Coimbatore · graduating april 2027 · contributing to LLVM / MLIR (still learning, loudly)</sub>

</div>

---

```mlir
// pipeline.mlir — how i think about building
func.func @starone01(%idea: !prod.prototype) -> !prod.shipped {
  %ast     = "frontend.parse"(%idea)       : (!prod.prototype) -> !ir.ast
  %lowered = "midend.lower"(%ast)          : (!ir.ast) -> !mlir.module
  // did someone ask for canonicalization? no. here it is anyway
  %opt     = "midend.canonicalize"(%lowered): (!mlir.module) -> !mlir.module
  %bin     = "backend.emit"(%opt) {target = "prod", opt = "-O3"} : (!mlir.module) -> !prod.shipped
  return %bin : !prod.shipped
} // scroll ↓ to execute each pass
```

### about

I'm Prashanth, **StarOne01**. Final-year EEE student who got curious about where hardware meets software and fell into the compilers hole. Compilers, inference, and the systems around AI.

Started coding on a phone with Termux. Since then I've helped build a clinical AI system, built a film recommendation engine (not collaborative filtering!), played with embeddings and multilingual LLM work, and started sending patches to LLVM / MLIR. The maintainers have been nice about it.

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

- writing a toy compiler's lexer from scratch. It handles `def` and `extern`, and has comments because nobody asked for them
- learning MLIR dialects + passes, building on x86 + Sema work
- poking at local LLM inference, Ollama internals

---

<div align="center">
  <sub>Coimbatore, India </sub>
  <br/>
  <sub><a href="https://starone01.me">starone01.me</a> · <a href="https://www.linkedin.com/in/StarOne01/">linkedin</a> · <a href="https://x.com/iamstarone01">x</a> · <a href="mailto:ping@starone01.me">ping@starone01.me</a></sub>

</div>
