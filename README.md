# pc-beeper

![crates.io](https://img.shields.io/crates/v/pc-beeper.svg)
![docs.rs](https://docs.rs/pc-beeper/badge.svg)

The most primitive audio device available on PC-compatible systems with characteristic "beeps" and "squeaks"

## Usage
```rust
use pc_beeper::Speaker;

let mut speaker = Speaker::new();
speaker.beep();
```