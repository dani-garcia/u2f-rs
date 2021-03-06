[![Build Status](https://travis-ci.org/wisespace-io/u2f-rs.png?branch=master)](https://travis-ci.org/wisespace-io/u2f-rs)
[![Crates.io](https://img.shields.io/crates/v/u2f.svg)](https://crates.io/crates/u2f)

# u2f-rs

Rust [FIDO U2F](https://fidoalliance.org/specifications/download/) library is a simple server side implementation to register and check signatures provided by U2F clients/devices. See [U2F Technical Overview](https://developers.yubico.com/U2F/Protocol_details/Overview.html)

# Usage

Add this to your Cargo.toml

```toml
[dependencies]
u2f = "0.1"
```

Make sure that you have read [Using a U2F library](https://developers.yubico.com/U2F/Libraries/Using_a_library.html) before continuing.

See provided [example](https://github.com/wisespace-io/u2f-rs/tree/master/example)



## License

Licensed under either of

* MIT license (see [LICENSE](LICENSE) or <http://opensource.org/licenses/MIT>)
* Apache License, Version 2.0 (see [LICENSE](LICENSE) or <http://www.apache.org/licenses/LICENSE-2.0>)