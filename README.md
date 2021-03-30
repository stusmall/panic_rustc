This reproduces a crash with rustc 1.53.0-nightly (07e0e2ec2 2021-03-24)

To trigger it build with RUST_BACKTRACE=1 RUSTFLAGS="-Z sanitizer=address" cargo build



