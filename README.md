### hi, i'm paul

embedded linux and edge ai engineer in vienna, austria. secure, reproducible, fast, and boring in production

- cto at [STØK](https://thestokclub.com) (company in formation): real-time stocksport scoring from cameras on a jetson running nixos. that code is closed source
- before that at agilox: moved a fleet of 3,000+ autonomous robots to measured boot, full disk encryption and secure boot, plus the tpm provisioning and ota updates behind it
- bsc in ai at jku linz, now doing the msc there

### what's here

- [llama.cpp-opt](https://github.com/invaliddayta/llama.cpp-opt): llama.cpp fork with my own cuda kernels. a 27b model on one rtx 3090 verifies 8 tokens per step in 33 ms instead of 54, and the kernel changes are bit-exact
- [llm-opt](https://github.com/invaliddayta/llm-opt): the benchmarks and notes behind it
- [s90c-tools](https://github.com/invaliddayta/s90c-tools): root, screenshots and app cleanup for my samsung s90c tv. tested on one tizen 7 build
- [nixos-orangepi-zero2w](https://github.com/invaliddayta/nixos-orangepi-zero2w) and [nixos-rockpi-s](https://github.com/invaliddayta/nixos-rockpi-s): nixos on tiny arm boards. one nix build, bootable sd card
- [agent-perch](https://github.com/invaliddayta/agent-perch): a small browser terminal for coding agents, on top of tmux

### upstream

- llama.cpp: fixed a shared-memory race in the cuda flash attention kernel ([#30573](https://github.com/ggml-org/llama.cpp/pull/30573))
- omarchy-mlx: fast quantized matmul for 4-bit group 32 and 8-bit models on apple silicon linux ([#179](https://github.com/joshuaswarren/omarchy-mlx/pull/179))

### work with me

open to freelance projects in embedded linux, device security and edge ai. on-site in vienna or linz, or remote. [linkedin](https://www.linkedin.com/in/paul-mairhofer/) or paul@protom.eu
