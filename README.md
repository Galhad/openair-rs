# openair-rs

[![CircleCI][circle-ci-badge]][circle-ci]
[![Rust][rust-badge]][github]
[![Docs][docs-badge]][docs]

A Rust parser for airspace files in OpenAir format (used by flight instruments
like Skytraxx and others).

http://www.winpilot.com/UsersGuide/UserAirspace.asp (see also `FORMAT.txt`)

This library requires Rust 2018 (1.31+).

Docs: https://docs.rs/openair/


## Status

Supported features:

- [x] Parse airspace metadata
- [ ] Parse terrain metadata
- [x] Support polygon points
- [ ] Support arcs
- [x] Support circles


## Example

You can try the parser using the example program:

    $ cargo run --example parse_file example_data/Switzerland.txt


## License

Licensed under either of

 * Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or
   http://www.apache.org/licenses/LICENSE-2.0)
 * MIT license ([LICENSE-MIT](LICENSE-MIT) or
   http://opensource.org/licenses/MIT) at your option.

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall
be dual licensed as above, without any additional terms or conditions.


<!-- Badges -->
[circle-ci]: https://circleci.com/gh/dbrgn/openair-rs/tree/master
[circle-ci-badge]: https://circleci.com/gh/dbrgn/openair-rs/tree/master.svg?style=shield
[github]: https://github.com/dbrgn/openair-rs
[rust-badge]: https://img.shields.io/badge/rust-2018%2B-blue.svg?maxAge=3600
[docs]: https://docs.rs/openair/
[docs-badge]: https://img.shields.io/badge/docs-docs.rs-yellow.svg?maxAge=3600
