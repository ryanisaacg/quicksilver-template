# {{project-name}}

This is a generated template for a game made with [Quicksilver](https://github.com/ryanisaacg/quicksilver.)

To create your own version of this template, install and use [`cargo-generate`](https://github.com/ashleygwilliams/cargo-generate).

Check out `src/lib.rs` for the `app` function, which is the core of your game.

To compile for desktop, just use `cargo build` and `cargo run` (make sure to use the `--release` flag when you're distributing binaries!)

For web, you'll want to install [`wasm-pack`](https://github.com/rustwasm/wasm-pack) to build your game and a web server to make it accessible for local development ([basic-http-server](https://crates.io/crates/basic-http-server) is a good option). Run `wasm-pack build --target web` to generate the Javascript and WebAssembly. 
