# Spin + Leptos sandbox

[![Build, Test and Deploy](https://github.com/acgetchell/spin-leptos/actions/workflows/ci.yml/badge.svg)](https://github.com/acgetchell/spin-leptos/actions/workflows/ci.yml)

[This] is a simple example of a Spin server that serves a Leptos application.

## Prerequisites

- Rust [with the `wasm32-wasi` target](https://developer.fermyon.com/spin/v2/install) - `rustup target add wasm32-wasi`
- [Spin]
- [cargo-leptos] - `cargo install --locked cargo-leptos`

Build and run:

- `spin up --build` to build and run the server. It will print the application URL.

[This]:https://spin-leptos-h8cj5c3j.fermyon.app
[Spin]:https://developer.fermyon.com/spin/v2/install
[cargo-leptos]:https://github.com/leptos-rs/cargo-leptos#getting-started
