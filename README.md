# SigmaOS bar_widgets

A Rust status-bar widget state model. The crate exposes widget positions and interaction metadata, widget configuration and visibility state, and a manager for organizing widgets in left, center, and right groups.

This library does not draw a panel or connect to a compositor or desktop event loop. The similarly named `SigmaOS-bar-widgets` repository is a separate package; check both manifests and their integrations before choosing one.

## Build

The manifest uses the sibling [`SigmaOS-kernel`](../SigmaOS-kernel) path dependency. From the SigmaOS checkout:

```sh
cargo check --manifest-path SigmaOS-bar_widgets/Cargo.toml --lib
```

## License

GPL-3.0-or-later. See [`Cargo.toml`](Cargo.toml).
