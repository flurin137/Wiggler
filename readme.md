# Wiggler

## Dependencies
- [Embassy](https://embassy.dev)

Currently building on top of commit `20fd03a14f1261e7b2264dcbca8e164393e66b94`

## Build
Make sure to place next to the cloned embassy repository:

```
- <someRoot>
   |- embassy
   ┕- wiggler << This Repository
```


Build with 
```
cargo build
```

The repo is set up to deploy to a device using `probe-rs` and a RPi Debug Probe. 
If you want to use a different approach configure it accordingly in `.cargo/config.toml`