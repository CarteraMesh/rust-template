# {{project-name}}

[![Crates.io](https://img.shields.io/crates/v/{{project-name}}.svg)](https://crates.io/crates/{{project-name}})
[![Docs.rs](https://docs.rs/{{project-name}}/badge.svg)](https://docs.rs/{{project-name}})
[![CI](https://github.com/{{gh-username}}/{{project-name}}/workflows/test/badge.svg)](https://github.com/{{gh-username}}/{{project-name}}/actions)
[![Cov](https://codecov.io/github/{{gh-username}}/{{project-name}}/graph/badge.svg?token=dILa1k9tlW)](https://codecov.io/github/{{gh-username}}/{{project-name}})

## Installation

### Cargo

* Install the rust toolchain in order to have cargo installed by following
  [this](https://www.rust-lang.org/tools/install) guide.
* run `cargo install {{project-name}}`


## Development

### Prerequisites

- **Rust Nightly**: Required for code formatting with advanced features
  ```bash
  rustup install nightly
  ```

### Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/CarteraMesh/{{project-name}}.git
   cd {{project-name}}
   ```

2. **Build and test**
   ```bash
   # Build the project
   cargo build

   # Run tests (requires valid Fireblocks credentials in .env)
   cargo test

   # Format code (requires nightly)
   cargo +nightly fmt --all
   ```

### Code Formatting

This project uses advanced Rust formatting features that require nightly:

```bash
# Format all code
cargo +nightly fmt --all

# Check formatting
cargo +nightly fmt --all -- --check
```

## License

 * MIT license
   ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your option.

## Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be
dual licensed as above, without any additional terms or conditions.

See [CONTRIBUTING.md](CONTRIBUTING.md).
