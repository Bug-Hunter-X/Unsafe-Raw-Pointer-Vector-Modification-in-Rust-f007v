# Rust Raw Pointer Vector Modification Bug

This repository demonstrates a common memory safety issue in Rust when using raw pointers with vectors.  The `bug.rs` file contains code that directly manipulates a vector's memory using `as_mut_ptr()`, which can lead to undefined behavior if the vector's capacity changes.

The `bugSolution.rs` file provides a safer solution using standard Rust vector methods.  This example highlights the importance of using safe Rust methods to avoid memory corruption and maintain program stability.