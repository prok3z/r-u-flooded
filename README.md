# r-u-flooded
🦀 r(ust)-u(dp)-flooded is a UDP-based DoS (Denial of Service) stress testing and Denial of Service tool made in Rust.


## Build

```bash
git clone https://github.com/celsec/r-u-flooded
cd r-u-flooded
apt-get install cargo
cargo build
./target/debug/r-u-flooded
```

## Usage

```bash
./r-u-flooded <ip address> <number of threads> <time (0 for infinite)>
```
