# CH32V00x Cargo Generate Template

Just a basic Rust project template for an application based off of the [`ch32v00x-hal`](https://github.com/ch32-rs/ch32v00x-hal) crate to get up and running quickly.

Please ensure you are have a recent version of Rust nightly installed.

## How to use:

1. Install [`cargo generate`](https://crates.io/crates/cargo-generate): 
    ```bash
    cargo install cargo-generate
    ```
2. Generate your project:
    ```bash
    cargo generate --git https://github.com/fred314159265/ch32v00x-hal-template.git
    ```
3. Build:
    ```bash
    cd ./{PROJ_NAME}
    cargo b
    ```

Check out `.cargo/config.toml` for some runner/programming options.