# Swift ISO

Swift implementations of ISO (International Organization for Standardization) specifications — a per-authority organization of [swift-standards](https://github.com/swift-standards), Layer 2 of the [Swift Institute](https://github.com/swift-institute) ecosystem.

## What this is

One package per specification, named `swift-iso-<number>`. Each package implements its source document as literally as possible — parsing, validation, and formatting enforced by Swift's type system — and defines its own namespace (`ISO_8601`). Where several specifications govern one subject, the unifying `swift-*-standard` package lives in [swift-standards](https://github.com/swift-standards).

## Coverage

| Package | Specification |
|---|---|
| [swift-iso-8601](https://github.com/swift-iso/swift-iso-8601) | Date and time format |
| [swift-iso-3166](https://github.com/swift-iso/swift-iso-3166) | Country codes |
| [swift-iso-639](https://github.com/swift-iso/swift-iso-639) | Language codes |
| [swift-iso-15924](https://github.com/swift-iso/swift-iso-15924) | Script codes |
| [swift-iso-32000](https://github.com/swift-iso/swift-iso-32000) | Document management — Portable Document Format (PDF) |
| [swift-iso-21320](https://github.com/swift-iso/swift-iso-21320) | Document Container File (ZIP) |
| [swift-iso-14496-22](https://github.com/swift-iso/swift-iso-14496-22) | Open Font Format |
| [swift-iso-80000-1](https://github.com/swift-iso/swift-iso-80000-1) | Quantities and units — Part 1: General (SI decimal prefixes) |
| [swift-iso-9899](https://github.com/swift-iso/swift-iso-9899) | Programming languages — C |
| [swift-iso-9945](https://github.com/swift-iso/swift-iso-9945) | Portable Operating System Interface (POSIX) |

Every repository description carries the specification's full title; the [repositories tab](https://github.com/orgs/swift-iso/repositories) lists them all.

## Status

Public alpha. Maintained by [Coen ten Thije Boonkkamp](https://github.com/coenttb) — contributions welcome via pull request.

## License

All packages use the Apache License 2.0.
