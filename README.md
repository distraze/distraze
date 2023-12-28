## Effects


- [] gain
- [] chorus
- [] vibrato
- [] reverb (delay?)
- [] output

## Building

After installing [Rust](https://rustup.rs/), you can compile Toybox C1200 as follows:

```shell
cargo xtask bundle toybox_c1200 --release
```

#### Debian/Ubuntu

Make sure that the required build tools are installed:

```sh
rustup target add x86_64-pc-windows-gnu
sudo apt install build-essential
```

Then finaly to build the plugin run:

```sh
cargo xtask bundle toybox_c1200 --target x86_64-pc-windows-gnu
```
