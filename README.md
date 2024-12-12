# Rust Undefined Behavior Example

This repository demonstrates a common source of undefined behavior in Rust: modifying a vector's contents via a raw pointer without properly managing its capacity.  The `bug.rs` file contains the erroneous code, while `bugSolution.rs` offers a safe and correct alternative.