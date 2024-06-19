# Getting Started

Create [main.rs](./main.rs) with next content:

```rust
fn main() {
    println!("Hello world!");
}
```

## Compile:

```bash
rustc ./main.rs
```

## Execute:

```bash
./main
# ./main.exe in windows
```

## Create Cargo proyect:

```bash
cargo new project_name
```

## Build Cargo Project:
```bash
cargo build
```

## Execute Cargo Project
```bash
./target/debug/{project-name}

# or

cargo run
```

## Check if code it's okay:
```bash
cargo check
```

## Build for release:
```bash
cargo build --release
```