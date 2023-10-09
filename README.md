# cms-rs

[![sanity checks](https://github.com/syncom/cms-rs-clone/actions/workflows/sanity.yml/badge.svg)](https://github.com/syncom/cms-rs-clone/actions/workflows/sanity.yml)

At a high level CMS defines a way to digitally sign and authenticate arbitrary
content.

`cms-rs` is a fork of `cryptographic-message-syntax`, a pure Rust implementation
of Cryptographic Message Syntax (CMS) as defined by RFC 5652, which was first
developed as part of the
[PyOxidizer](https://github.com/indygreg/PyOxidizer.git) project.

Because the original `cryptographic-message-syntax` crate has been removed from
later versions of the `PyOxidizer` project, and it's not obvious how the source
code is being maintained, I "forked" the 0.18.0 version of it by importing the
source directly from
<https://crates.io/api/v1/crates/cryptographic-message-syntax/0.18.0/download>,
and adding subsequent modifications on top of this base version, in this
repository.
