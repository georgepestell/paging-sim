# Paging Simulator

Simulator for a paging system for an imaginary architecture. Models physical memory, and defines how virtual addresses are mapped to physical addresses. Written in C.

## Architecture Definition

- 16-bit
- single-level paging support
- two protection bits: `read-only`, and `exectuable`
- page/frame size of 128-bytes

# Compilation

A makefile is provided in the `src` directory for compilation. Run:

```bash
cd src
make all
```

This generates a `test` executable.

# Running

Tests are provided which demonstrate the simulation's capabilities. Run these with the generated executable in the `src` directory:

```bash
./test
```
