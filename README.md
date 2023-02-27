# L1IR Rust
AoT compilation to Rust for [L1IR](https://github.com/andrew-johnson-4/L1IR) code.

### Why LSTS and L1?

LSTS has a type system and syntax that innovates on logical structuring and destructuring of values vis-à-vis types.

Writing the equivalent code directly in Rust is bulky, inefficient, and error-prone.

So we find the happy medium: compile L1 to Rust, then use the exposed L1 functions as a Rust library.

Very little wagered. Much to gain. Everybody is happy: maybe.

### Specifically what does L1 do that Rust doesn't?

L1 implements a handful of features that we refer to as "type-directed compilation".

L1's model of type-directed compilation falls under the umbrella of logic-programming.
During compilation, an L1 program may be asked to solve a set of constraints or optimize an objective.
These problems may be quite arbitrary and not generally decidable.

You can read more about L1 [here in the e-book](https://andrew-johnson-4.github.io/lsts-tutorial/).
