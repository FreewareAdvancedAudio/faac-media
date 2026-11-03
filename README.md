# FAAC Media

Media assets, audio test vectors, and reference bitstreams for the FAAC project.

## Layout

```
audio/songs/<slug>/     Songs, one directory per work (e.g. pipeline-tighter: website demo)
LICENSES/               License texts, named by SPDX identifier
REUSE.toml              Per-path license declarations
```

Planned: `audio/vectors/` (test vectors) and `bitstreams/` (reference bitstreams).

## Licensing

This repository holds material under multiple licenses; there is no single
repository-wide license. Each asset's license is declared in `REUSE.toml`
following the [REUSE specification](https://reuse.software/spec/), with full
texts in `LICENSES/`. Check the entry for a path before reusing it.

When adding an asset, add an `[[annotations]]` block for it in `REUSE.toml`.
