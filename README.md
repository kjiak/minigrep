# Minigrep

## Build
create new package: `cargo new hello_world --bin (binary)(default)/--lib (library)` <br>
build: <br>
`cargo build` <br>
`./target/debug/hello_world` <br>
build & run project in one step: `cargo run` <br>
check code for compilation: `cargo check` <br>
optimisation & release: `cargo build --release` <br>
testing: `cargo test` <br>
lib.rs: modify Cargo.toml <br>

## Run
case insensitive search: <br>
`$env:CASE_INSENSITIVE=""` <br>
`$env:CASE_INSENSITIVE=1` <br>
`cargo run to poem.txt`

output to output.txt: <br>
`cargo run to poem.txt > output.txt`

## Credits
Rust book