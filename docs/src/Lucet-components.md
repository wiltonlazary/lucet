# Lucet components

* [`lucetc`](lucetc.md): the Lucet Compiler.

* [`lucet-runtime`](lucet-runtime.md): the runtime for WebAssembly modules compiled through
  `lucetc`.

* [`lucet-wasi`](./lucet-wasi.md): runtime support for the [WebAssembly System Interface
  (WASI)](https://wasi.dev).

* [`lucet-objdump`](./lucet-objdump.md): an executable for inspecting the contents of a shared
object generated by `lucetc`.

* [`lucet-spectest`](./lucet-spectest.md): a driver for running the official WebAssembly spec test
  suite under Lucet.

* [`lucet-wasi-sdk`](./lucet-wasi-sdk.md): convenient wrappers around the WASI Clang toolchain and
  `lucetc`.

* [`lucet-module`](./lucet-module.md): data structure definitions and serialization functions that
  we emit into shared objects with `lucetc`, and read with `lucet-runtime`.
