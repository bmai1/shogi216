Shogi GUI in Rust with lishogi assets, shogi-rs, and apery_rust shogi engine. 
Currently only supports player vs. engine, or player vs. player on one device.

## Installation

1. Clone and navigate to the repository:
```bash
git clone https://github.com/bmai1/shogi-for-crabs.git
cd shogi-for-crabs
```

2. Install [apery_rust evaluation binaries](https://github.com/HiraokaTakuya/apery_rust), apery_rust should be in root directory (shogi-for-crabs):
```bash
git clone https://github.com/HiraokaTakuya/apery_rust.git && \
cd apery_rust && \
git submodule init && \
git submodule update && \
cargo build --release
```

3. Go back to root directory and run:
```bash
cd ..
cargo run
```

## Demo

https://github.com/user-attachments/assets/58d2ca56-ae4a-4f7f-b5db-17d639507a50
