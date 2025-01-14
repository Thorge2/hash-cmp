# hash-cmp
![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white)\
Calculate and compare hash values quickly and easily

## Supported Hashing Algorithms
- Sha256

## How to use
```bash
./hash-cmp -h
./hash-cmp [optional: -q (quiet mode)] <file path> <expected hash>
```

## Exit codes
- **0**: Hashes are equal
- **255**: Hashes are not equal

## Example
### Verbose mode
![image](https://user-images.githubusercontent.com/77125551/181935367-3dd1910d-70be-4a01-80c7-9bd893a4682e.png)

### Quiet mode
![image](https://user-images.githubusercontent.com/77125551/181935391-d6f9275c-9bd8-4af5-b302-f50bb641d7a3.png)


## Roadmap
- Support multiple hash functions
- Automatically figure out suitable hash-functions based on hash length
- optimized source code
- a man page
