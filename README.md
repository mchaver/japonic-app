# japonic-app

```
rustup update
rustup toolchain install nightly
rustup target add wasm32-unknown-unknown --toolchain nightly
cargo +nightly build --target wasm32-unknown-unknown --release
wasm-gc target/wasm32-unknown-unknown/release/japonic_app.wasm -o japonic_app.gc.wasm

wasm-gc target/wasm32-unknown-unknown/release/japonic_app.wasm -o build/romaji.gc.wasm
```
