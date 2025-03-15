# Kiyo template

This repository acts as a template to easily get started using kiyo.

It is a Rust project setup with kiyo as a dependency, and contains the necessary code to run a simple shader.

## Kiyo version
You can set the version of Kiyo by editing `Cargo.toml` and specifying a specific release version published on [crates.io](https://crates.io/crates/kiyo/).
```toml
kiyo = "0.0.6"
```

Or use the latest git commit:
```toml
kiyo = { git = "https://github.com/angelocarly/kiyo" }
```
If you want to pull the latest git version, you would use `cargo update`

Or use a specific git commit:
```toml
kiyo = { git = "https://github.com/angelocarly/kiyo", rev = "8eb08954530a9a947b644828062d7d03a10218b" }
```