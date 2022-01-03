# MediaTek PCM (SPM) Processor Module for Ghidra

**NOTE**: This is a work-in-progress. Most instructions are supported, but
many of them have not been tested on real hardware. Because of this, the
decompiler output for those untested instructions may be incorrect.

Big thanks to [Paul Kocialkowski][paulk] for doing the original reverse
engineering work for this ISA ([video][video], [slides][slides], [updated
slides][slides-updated]).

## Build and Install

```
$ cd ghidra_9.*/Ghidra/Processors
$ git clone https://github.com/cyrozap/ghidra-pcm.git PCM
$ cd PCM
$ make
```


[paulk]: https://paulk.fr/
[video]: https://www.youtube.com/watch?v=9rKxfo7Gkqo
[slides]: https://web.archive.org/web/20171030164527/https://ecc2017.coreboot.org/uploads/talk/presentation/30/reverse-engineering-mt8173-pcm-firmwares-isa-fully-free-boot-chain.pdf
[slides-updated]: https://paulk.fr/media/2018-thsf/2018-thsf-mt8173-pcm.pdf
