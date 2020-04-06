# naive_dns_relay
naive DNS relay implemented in Rust

## how to use

Since the DNS relay required listening port 53, you should use `sudo` or something like to run `cargo run`.

Plus, make sure you have redirected your default DNS server to the IP which this DNS relay combined. You can set related configuration in `const_value.rs`.

You can use `nslookup` to check if it works or not.

## warning

The current version could only accept resource record of A kind.
