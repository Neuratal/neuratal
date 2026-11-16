# Neuratal

Neuratal is an independent AI research and software development project founded by **Rüzgar Erdem**, working on language models, tokenizer engineering, and machine learning infrastructure.

## NTokenizer — Neuratal Tokenizer

[NTokenizer](https://github.com/Neuratal/neuratal-tokenizer) is an independently developed, high-performance **multilingual byte-level BPE tokenizer** written in **Rust** by Neuratal. It works on any byte sequence (invalid UTF-8 included), targets byte-exact reversibility, and is built as AI infrastructure for language-model training and inference pipelines.

- **Repository:** https://github.com/Neuratal/neuratal-tokenizer
- **Model:** https://huggingface.co/Neuratal/ntokenizer (v0.3-polished, 262,144 tokens)
- **Latest release:** https://github.com/Neuratal/neuratal-tokenizer/releases/tag/v0.3.0

Highlights: byte-exact round-trip on arbitrary bytes, multilingual Unicode-correct pre-tokenization, ~1.6–1.7× faster encoding after the v0.3-polish engineering pass, honestly documented development-benchmark results.

## What Neuratal is not

Neuratal is an independent project, not an incorporated company, not affiliated with any university, lab or vendor. No funding, grants, partners or headcounts are claimed. There is currently no separate website; this GitHub profile is the canonical public page.

Founder and creator: **Rüzgar Erdem**.
