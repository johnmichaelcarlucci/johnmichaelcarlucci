# John Michael Carlucci

Interpretability tooling. Python.
Indianapolis, IN

---

### Focus

Open bug reports in interpretability libraries: reproduce on current main, find the fix or the cause, close them out. CUDA on Windows.

---

### Open-source contributions

#### [SAELens](https://github.com/decoderesearch/SAELens)

- **[#186](https://github.com/decoderesearch/SAELens/issues/186) `ActivationsStore` with models that have no tokenizer.** Reproduced on main (`ef4c208`, v6.51.3): a tokenizer-less model on a pretokenized dataset, with `prepend_bos` and `exclude_special_tokens` on, trains through `LanguageModelSAETrainingRunner` and `run_evals` completes. Traced the fix to [#181](https://github.com/decoderesearch/SAELens/pull/181). Closed by the maintainer.
