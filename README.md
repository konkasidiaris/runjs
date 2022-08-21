# Mini JavaScript runtime on top of Deno core

1. uses `tokio` as an event loop implementation
2. implements `console` API
3. binds `readFile`, `writeFile`, `removeFile` to **Rust**'s respective implementions

### example.js

contains working JavaScript examples

### how to run the project

1. ensure that you have Rust 1.62 or later by running `cargo --version`
2. run `cargo run`
