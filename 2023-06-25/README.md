# 2023-06-25

This collection includes benchmarks run on 3 different platforms:

- [benchmark_intel.json](benchmark_intel.json): server with Intel Xeon CPU E3-1270 v6 (x86)
- [benchmark_amd.json](benchmark_amd.json): server with AMD EPYC 7302P CPU (x86)
- [benchmark_rpi.json](benchmark_rpi.json): Raspberry Pi 4 with ARM Cortex-A72 CPU (ARM)

Selected engines:

- Duktape
- Espruino
- JerryScrip (32-bit)
- JerryScrip (16-bit)
- MuJS
- QuickJS
- XS
- V8 (as a reference)

Selected workloads:

- array-find
- array-push
- array-slice
- array-sort
- array-tostring
- proto-chain
- regex
- [nano-neuro](https://github.com/trekhleb/nano-neuron)
- [lzma-js](https://github.com/LZMA-JS/LZMA-JS)
- [convnetjs](https://github.com/karpathy/convnetjs)
