## Pending

### Breaking changes
- Requires all crates from `arkworks-rs/algebra` to have version `v0.2.0` or greater.

### Features
- #3 Add constraints for 
        `ark-bls12-377`,
        `ark-ed-on-bls12-377`,
        `ark-ed-on-bls12-381`,
        `ark-ed-on-bn254`,
        `ark-ed-on-cp6-782`,
        `ark-ed-on-bw6-761`,
        `ark-ed-on-mnt4-298`,
        `ark-ed-on-mnt4-753`,
        `ark-mnt4-298`,
        `ark-mnt6-298`,
        `ark-mnt4-753`,
        `ark-mnt6-753`
- #7 Add benchmarks for Edwards curves
- #19 Change field constants to be provided as normal strings, instead of in montgomery form.

### Bug fixes
- #28 fix broken documentation links
- #38 Compile with `panic='abort'` in release mode, for safety of the library across FFI boundaries.

## v0.1.0

Initial Release
