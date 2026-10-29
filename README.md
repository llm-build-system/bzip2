# bzip2 - llm port

Original project: [bzip2/libbzip2](https://sourceware.org/bzip2/), version 1.0.8.
Original author: Julian Seward, with contributions from the upstream community.
[Original repository](https://sourceware.org/git/bzip2.git).

The library is the work of its original authors, not a product of llm-build-system.
This repository only maintains its llm build integration and source layout.
It is not an official upstream release. All source and header files are unchanged.
Library files are arranged in `src/` and `include/`. Upstream build files,
command-line tools and manuals are omitted.

The original license is preserved verbatim in [LICENSE](LICENSE).
[Upstream license](https://sourceware.org/git/?p=bzip2.git;a=blob;f=LICENSE;hb=bzip2-1.0.8).

Build the static library with `llm build --release`.
Consumers use `#include <bzlib.h>`. There are no external dependencies.

Additional upstream notices: [NOTICE](NOTICE).
