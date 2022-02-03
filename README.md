# Rust_Unit_Testing

## cargo new Rust_Unit_Testing --lib 
## cargo test !

```
warning: function is never used: `sqrt`
 --> src/lib.rs:1:4
  |
1 | fn sqrt(number: f64) -> Result<f64, String> {
  |    ^^^^
  |
  = note: `#[warn(dead_code)]` on by default

warning: `adder` (lib) generated 1 warning
    Finished test [unoptimized + debuginfo] target(s) in 0.44s
     Running unittests (target/debug/deps/adder-c10e962e602cc487)

running 3 tests
test tests::test_divide ... ok
test tests::test_sqrt ... ok
test tests::test_any_panic - should panic ... ok

test result: ok. 3 passed; 0 failed; 0 ignored; 0 measured; 0 filtered out; finished in 0.00s

   Doc-tests adder

running 0 tests

test result: ok. 0 passed; 0 failed; 0 ignored; 0 measured; 0 filtered out; finished in 0.00s

```
