# Ip port sniffer CLI.

Usage:
`cargo run` to run the app
`cargo build` to build an executable file

Example:
```bash
$ cargo run -- -j 1000 192.168.1.1
    Finished dev [unoptimized + debuginfo] target(s) in 0.02s
    Running `target/debug/ip_sniffer -j 1000 192.168.1.1`
....
23 is open
53 is open
80 is open
60061 is open
```
