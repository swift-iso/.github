# Swift ISO

Swift implementations of ISO (International Organization for Standardization) specifications — a per-authority organization of [swift-standards](https://github.com/swift-standards), Layer 3 of the [Swift Institute](https://github.com/swift-institute) ecosystem.

## What this is

One package per specification, named `swift-iso-<number>`. Each package implements its source document as literally as possible — parsing, validation, and formatting enforced by Swift's type system — and defines its own namespace (`ISO_8601`). Where several specifications govern one subject, the unifying `swift-*-standard` package lives in [swift-standards](https://github.com/swift-standards).

> Swift ISO is an independent open-source project. It is not affiliated with, endorsed by, or sponsored by the International Organization for Standardization.

## Start here

| Package | Specification |
|---|---|
| [swift-iso-8601](https://github.com/swift-iso/swift-iso-8601) | Date and time format |
| [swift-iso-32000](https://github.com/swift-iso/swift-iso-32000) | Portable Document Format (PDF) |
| [swift-iso-3166](https://github.com/swift-iso/swift-iso-3166) | Country codes |
| [swift-iso-639](https://github.com/swift-iso/swift-iso-639) | Language codes |
| [swift-iso-9945](https://github.com/swift-iso/swift-iso-9945) | Portable Operating System Interface (POSIX) |
| [swift-iso-21320](https://github.com/swift-iso/swift-iso-21320) | Document Container File (ZIP) |

## Browse everything

The [repositories tab](https://github.com/orgs/swift-iso/repositories) lists every package with its full specification title — to check whether a specific standard is covered, search its number there.

## Status

Public alpha. Maintained by [Coen ten Thije Boonkkamp](https://github.com/coenttb) — contributions welcome via pull request.

## License

All packages use the Apache License 2.0.
