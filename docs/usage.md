# Using mouser-engine-abi

Stable C ABI (v2) for Mouser custom rendering engines.

- API reference: [docs.rs/mouser-engine-abi](https://docs.rs/mouser-engine-abi).
- The ABI, the `export_engine!` macro and the C header (`mouser_engine.h`): see the crate docs and Mouser's [engines guide](https://github.com/WeirdBrains/mouser/blob/main/docs/engines.md).
- Versioning: the crate follows semver; the ABI number (`abi` in engine.toml) is separate and changes only when the wire breaks.
