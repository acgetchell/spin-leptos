# Spin + Leptos sandbox

[This] is a simple example of a Spin server that serves a Leptos application.

## Prerequisites

- Rust [with the `wasm32-wasi` target](https://developer.fermyon.com/spin/v2/install) - `rustup target add wasm32-wasi`
- [Spin]
- [cargo-leptos] - `cargo install --locked cargo-leptos`

Build and run:

- `spin up --build` to build and run the server. It will print the application URL.

[This]:https://cloud.fermyon.com/app/spin-leptos
[Spin]:https://developer.fermyon.com/spin/v2/install
[cargo-leptos]:https://github.com/leptos-rs/cargo-leptos#getting-started
