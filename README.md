# llama-cpu-bench

Speed of a small public model (Qwen3-0.6B, Q4_K_M GGUF) with llama.cpp on GitHub's Windows runners, in a normal
and a portable (no AVX/AVX2) build. Synthetic benchmark only (`llama-bench`); CI virtual machines are faster than
typical low-end PCs, so treat these numbers as an upper bound.
