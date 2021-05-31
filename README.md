$ nix-shell --run checkPhase -A mozilla-rust-overlay # checks rustfmt and clippy
$ nix-shell --run checkPhase # runs the test suite
$ nix-build -A ofborg.rs # build ofborg
Currently there is no easy way to set up a test instance of ofborg. If cargo check and cargo test both succeed, feel free to Pull Request your changes. Make sure to format your code with cargo fmt and check for additional warnings with cargo clippy. If you added, removed, or updated the dependencies, also be sure to update Cargo.nix by running ./nix/update-crates.sh.
To disable warnings as errors, run your command with an empty RUSTFLAGS. For example:

$ RUSTFLAGS= cargo clippy
