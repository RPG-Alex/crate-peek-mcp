# Contribute
- [ ] complete this MD. 
## Development Environment Setup

### Rust Toolchain
This project uses the stable Rust toolchain.  
Install Rust using [rustup](https://rustup.rs/), then verify:

```bash
rustup update
rustc --version
cargo --version
```

Rustfmt and Clippy are required for formatting and linting:

```bash
rustup component add rustfmt clippy
```

Check formatting and lints before committing:

```bash
cargo fmt --all --check
cargo clippy --all-targets -- -D warnings
```
### Taplo (TOML Formatter)

We use [Taplo CLI](https://taplo.tamasfe.dev/) to format all `.toml` files.

Install it once globally:

```bash
cargo install taplo-cli
```

Format the workspace TOMLs:

```bash
taplo format
```
