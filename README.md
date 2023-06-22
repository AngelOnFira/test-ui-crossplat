# Test Ui Crossplay

To cross-compile this Rust project for Windows from a Linux machine, follow these steps:

1. Install the Rust target for Windows: `rustup target add x86_64-pc-windows-gnu`
2. Install the mingw-w64 toolchain:
    - Apt: `sudo apt-get install mingw-w64`
    - Pacman: `sudo pacman -S mingw-w64-gcc`
3. Build the project using the --target flag: `cargo build --target x86_64-pc-windows-gnu`
