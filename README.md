## kbox

### What it is

`kbox` is a file vault command-line tool written in C and C++ that will use the Linux kernel’s crypto APIs via `AF_ALG` sockets for encryption and decryption. This starter repository only defines the layout and documentation; cryptographic functionality will be added later.

### Why it matters

`kbox` is designed as a systems-level project that exercises:

- systems file I/O
- custom binary file formats
- Linux kernel interface usage (e.g., `AF_ALG`)
- low-level pointers and buffer management in C and C++

### Repo layout

- `spec/` – high-level design notes, protocols, and behavior specs
- `docs/` – user-facing and developer documentation
- `assets/` – diagrams, images, and other non-code artifacts
- `c/include/` – C headers
- `c/src/` – C source files
- `c/tools/` – C-based helper tools and utilities
- `c/tests/` – C test code
- `cpp/include/` – C++ headers
- `cpp/src/` – C++ source files
- `cpp/tools/` – C++ helper tools and utilities
- `cpp/tests/` – C++ test code

### Build

Build tooling and commands will be added later once the initial design and module layout are finalized.

### Status

A week-by-week build plan will be drafted in `spec/` as the next step for this project.
