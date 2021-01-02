# Example from 
https://doc.rust-lang.org/book/ch01-03-hello-cargo.html

# Run
```
build_and_run.bat
```
*See sources of batch files to see what is exactly called.*

# Notes
1. Following cargo command generate /src/main.rs with Hello world functionality, so you don't write any code.

```shell
cargo new hello_cargo
```

2. When you are finished use `cargo build --release` (more optimalized -> faster execution && slower build)

3. `cargo run` do build (or use cached build) and run the code (knows where generated binary is) 
4. `cargo check` checks if it is buildable, but doesn't generate any binary files