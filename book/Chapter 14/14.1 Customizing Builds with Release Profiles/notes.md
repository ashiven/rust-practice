-  you can specify various options for `release profiles`
-  `cargo build` uses the `release profile` `dev`, while `cargo build --release` uses the `release profile` `release`
-  `release profiles` can be modified in `Cargo.toml`.
-  for example, the number of optimizations applied at compilation with the `dev` profile: `[profile.dev]\n opt-level = 1`
