# John Michael Carlucci

Interpretability tooling. Python.
Indianapolis, IN

---

### Focus

Open-source contributor, AI. Python now; C++ and CUDA kernels next.

---

### Open-source contributions

#### [SAELens](https://github.com/decoderesearch/SAELens)

- **[#186](https://github.com/decoderesearch/SAELens/issues/186) `ActivationsStore` with models that have no tokenizer.** Reproduced on main (`ef4c208`, v6.51.3): a tokenizer-less model on a pretokenized dataset, with `prepend_bos` and `exclude_special_tokens` on, trains through `LanguageModelSAETrainingRunner` and `run_evals` completes. Traced the fix to [#181](https://github.com/decoderesearch/SAELens/pull/181). Closed by the maintainer.
- **[#576](https://github.com/decoderesearch/SAELens/issues/576) Support uv for package management.** Matched the year-old proposal against [#746](https://github.com/decoderesearch/SAELens/pull/746), which had switched SAELens from Poetry to uv without linking it: `uv_build` backend, CI and makefile on uv, contributing guide on `uv sync`, byte-identical package files. Verified on main (`56e0a001`). Closed by the maintainer.
