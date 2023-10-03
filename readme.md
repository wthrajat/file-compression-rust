[![RUST](https://img.shields.io/badge/made%20with-RUST-red.svg?style=for-the-badge&logo=rust)](https://www.rust-lang.org/)

## File Compressor
This simple program uses the `flate2` crate to implement the compression.
Know more about `flate2` here: [flate2](https://docs.rs/flate2/latest/flate2/)

After file compression, you can use any File Extractor to decompress the file.

## Usage
```bash
cargo run source_file target_file
```
`source_file` is the file you want to compress and `target_file` is the output file that will be saved in the `pwd`
(Make sure to put the file names with their extensions e.g., `target_file.pdf`, `source_file.zip`)