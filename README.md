# ⚠️ DEPRECATED
**This project has been merged into my core systems library.**
**Active development continues here:** [lib-systems](https://github.com/juangmerlhe/lib-systems)

# memory-arena
a simple, high-performance linear memory allocator (arena) written in c.

## features
- **o(1) allocation**: extremely fast, constant-time memory allocation.
- **alignment**: supports 8-byte memory alignment for modern cpu architectures.
- **no fragmentation**: eliminates the "swiss cheese" memory problem of standard malloc.
- **pure c**: no external dependencies other than standard library headers.

## usage
compile the test file to see it in action:
`gcc arena.c test.c -o arena_test && ./arena_test`
