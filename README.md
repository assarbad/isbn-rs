# isbn3

[![Build Status](https://github.com/assarbad/isbn-rs/workflows/Rust/badge.svg)](https://github.com/assarbad/isbn-rs/)
[![Crate](https://img.shields.io/crates/v/isbn3.svg)](https://crates.io/crates/isbn3)
[![docs.rs](https://docs.rs/isbn3/badge.svg)](https://docs.rs/isbn3)

A library for handling [International Standard Book Number], or ISBNs.

[International Standard Book Number]: https://www.isbn-international.org/

This library is an extension of [limeburst/isbn-rs](https://github.com/limeburst/isbn-rs) (aka [`isbn`](https://crates.io/crates/isbn)).

Originally it also contained patches supplied by [philippeitis/isbn-rs](https://github.com/philippeitis/isbn-rs) (aka [`isbn2`](https://crates.io/crates/isbn2)) and was topped up with a patch from [CodingAnarchy/isbn-rs](https://github.com/CodingAnarchy/isbn-rs) which set MSRV to 1.60 (which I had to bump further to 1.63 on account of `indexmap`). Additionally I introduced the `ranges` feature which isn't enabled by default, because I saw no value in the original feature for my use case.
