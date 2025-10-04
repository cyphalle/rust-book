# WARP.md

This file provides guidance to WARP (warp.dev) when working with code in this repository.

## Repository Purpose

This is a learning repository for working through "The Rust Programming Language" book with chapter-by-chapter exercises.

## Repository Structure

- Organized into `chap_1` through `chap_20` directories, plus `appendices/`
- Each chapter directory contains:
  - `chapter.txt` - Full chapter text extracted from the book
  - `README.md` - Chapter overview and notes
  - Subdirectories for code exercises and Cargo projects
- Mix of standalone `.rs` files and full Cargo projects
- The `chapters/` directory contains documentation (INDEX.md and README.md) for quick reference

## Common Commands

### Standalone Rust Files
- Compile: `rustc path/to/file.rs`
- Run compiled binary: `./binary_name`

### Cargo Projects
Navigate to the specific project directory first, then:
- Build: `cargo build`
- Run: `cargo run`
- Build optimized: `cargo build --release`
- Check without building: `cargo check`
- Run tests: `cargo test`
- Format code: `cargo fmt`
- Lint code: `cargo clippy`

## Development Workflow

- Each chapter is self-contained with its own exercises
- Navigate to specific project directories before running cargo commands
- Standalone files (like `hello_world/main.rs`) are compiled with `rustc` directly
- Cargo projects have their own `Cargo.toml`, `src/` directory, and `target/` build output

## Architecture Notes

- No workspace-level Cargo.toml; each project is independent
- Target directories are kept local to each project (not gitignored based on presence in repository)
- Edition 2024 is used in Cargo.toml files
- Current Rust toolchain: 1.90.0
