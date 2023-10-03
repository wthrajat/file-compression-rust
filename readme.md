[![RUST](https://img.shields.io/badge/made%20with-RUST-red.svg?style=for-the-badge&logo=rust)](https://www.rust-lang.org/)

## File compression
This simple program uses the `flate2` utility to implement the compression.
Know more about `flate2` here: [flate2](https://docs.rs/flate2/latest/flate2/)

## Usage
```bash
cargo run source_file target_file
```
`source_file` is the file you want to compress and `target_file` is the output file that will be saved in the `pwd`