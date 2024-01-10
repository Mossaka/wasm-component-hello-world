# wasm component hello world

To build the wasm component, you need to install the rust toolchain and the wasm32-wasi target and `cargo-component`:

```bash
rustup target add wasm32-wasi
cargo install cargo-component
```

Then you can build the wasm component with:

```bash
cargo component build --release
```

the wasm component artifact is located at `target/wasm32-wasi/release/component-hello-world.wasm`