# bung

The bung library is a custom MessagePack based serialization implementation for SurrealDB, based originally on the [Rust MessagePack](https://crates.io/crates/rmp-serde) library. It enables enums and structs to be serialized using a number of different configurations, including named struct serialization, and either named or index-based compact enum serialization.

[![](https://img.shields.io/badge/status-stable-ff00bb.svg?style=flat-square)](https://github.com/surrealdb/bung) [![docs.rs](https://img.shields.io/docsrs/bung?style=flat-square)](https://docs.rs/bung/) [![Crates.io](https://img.shields.io/crates/v/bung?style=flat-square)](https://crates.io/crates/bung) [![](https://img.shields.io/badge/license-MIT-00bfff.svg?style=flat-square)](https://github.com/surrealdb/bung) 

#### Features

- Clear error handling
- Zero-copy value deserialization
- Simple serialization configuration
- Named struct serialization configuration
- Name or integer based compact enum serialization configuration

#### Original

This code is based on and forked originally from [rmp-serde](https://crates.io/crates/rmp-serde), licensed under the and [MIT](https://choosealicense.com/licenses/mit/) licenses.