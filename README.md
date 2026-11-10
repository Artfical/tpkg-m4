# m4

GNU m4 1.4.19, the macro processor

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install m4
```

| | |
|---|---|
| Version | 1.4.19 |
| Licence | GPL-3.0-or-later |
| Upstream | - |
| Needs | none |
| Needs tOS build | 619 or newer |
| Size | 140432 bytes (264648 unpacked) |
| SHA-256 of the `.tpkg` | `af361ab30306eafe6f4247865c32cd24fe8d7ee8c1b097dd6a804502860f4c28` |

## Commands it adds

| Command | Runs |
|---|---|
| `m4` | `bin/m4` |

## Download

The package file (`m4-1.4.19.tpkg`) and the sources it was built from are the assets of the
[v1.4.19 release](https://github.com/Artfical/tpkg-m4/releases/tag/v1.4.19).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `m4-1.4.19.tar.xz`

Check a download: `sha256sum m4-1.4.19.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: GPL-3.0-or-later. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
