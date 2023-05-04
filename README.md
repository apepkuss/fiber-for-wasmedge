# fiber-for-wasmedge

This project is derived from [wasmtime-fiber](https://crates.io/crates/wasmtime-fiber). The motivation of creating this project is to solve the version conflict issue between `wasmtime-fiber`s used by Wasmtime and WasmEdge, respectively. It would be much easier for [runwasi](https://github.com/containerd/runwasi) project to integrate these two WebAssembly runtimes.
