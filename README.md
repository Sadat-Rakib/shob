# shob

A GPU-accelerated terminal emulator built for developers orchestrating AI coding agents.

Built with Rust and GPUI.

## Building

Requires Rust 1.94.1 or newer.

On Ubuntu/Debian, install the system dependencies first:

```bash
sudo apt install -y libwayland-dev libxkbcommon-dev libfontconfig1-dev libssl-dev cmake pkg-config
```

Then:

```bash
cargo run                 # dev build
cargo build --release     # release build
```

## Usage

Run AI coding agents alongside your terminals, manage multiple projects, and track active sessions — all in one native workspace.

Configure agent integrations:

```bash
shob integration setup
```

## License

Dual-licensed under [MIT](LICENSE-MIT) or [Apache-2.0](LICENSE-APACHE). Bundled Zed file icons are licensed under GPL-3.0-or-later — see [assets/zed_file_icons/NOTICE.md](assets/zed_file_icons/NOTICE.md).
