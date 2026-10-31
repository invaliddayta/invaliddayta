### hi, i'm paul

aspiring cyborg, trying to fix the limited bandwidth of humans

cto, linux and edge ai engineer. i like building robots

- [STØK](https://thestokclub.com): stocksport is still scored with a tape measure. in 2026. we do it with four cameras and a jetson running nixos instead. that code is closed, sorry
- before that at agilox i prepared the environment for moving the robot fleet onto measured boot, full disk encryption and secure boot, plus the tpm provisioning and ota updates behind it
- bsc in ai at jku linz, now doing the msc there

### things i made behave

- [samsung-tv-tools](https://github.com/invaliddayta/samsung-tv-tools): my samsung tv kept nagging me with update popups and apps i never asked for. so i rooted it. turns out i wasn't the only one being nagged: s90d and s95c owners report it works on theirs too, up to tizen 9
- [nixos-rockpi-s](https://github.com/invaliddayta/nixos-rockpi-s) and [nixos-orangepi-zero2w](https://github.com/invaliddayta/nixos-orangepi-zero2w): i keep putting nixos on tiny arm boards and nobody can stop me
- [llama.cpp-opt](https://github.com/invaliddayta/llama.cpp-opt): not everyone has a datacenter. i have one rtx 3090 hanging off an oculink cable. my cuda kernels take a 27b model's verify step from 54 ms to 33. if the output hashes don't match, it doesn't ship
- [agent-perch](https://github.com/invaliddayta/agent-perch): a small browser terminal for my coding agents, on top of tmux. so i can check on them from my phone

### fixed upstream

- llama.cpp: a shared-memory race in the cuda flash attention kernel. 2.2 million racecheck hazards down to zero ([#30573](https://github.com/ggml-org/llama.cpp/pull/30573))
- omarchy-mlx: 4-bit group 32 and 8-bit models were stuck on a slow fallback kernel. on my macbook air running linux a 7b model now reads prompts ~8x faster ([#179](https://github.com/joshuaswarren/omarchy-mlx/pull/179))

### work with me

freelance embedded linux, device security and edge ai. vienna, linz or remote. [linkedin](https://www.linkedin.com/in/paul-mairhofer/) or paul@protom.eu
