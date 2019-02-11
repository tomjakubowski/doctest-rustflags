# What is this?

Small test repo for a cargo bug.

It has a `.cargo/config` which specifies a canary `RUSTFLAGS`, and a doctest.  When
you run `cargo test --verbose`, you'll see that the canary is present when
building all targets except for the doctest runner.
