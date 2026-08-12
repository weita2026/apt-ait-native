# AIT Native apt repository

Exact RC route: `testing`; signing fingerprint:
`F3A43E51AB73AD580ADE43634D84B16BA88BC9BD`.

> [!WARNING]
> Do not install `1.0.0~rc.1` from this repository. Its frozen Debian data
> archives omit required parent-directory entries and fail during clean
> `dpkg` unpack. The signed repository is retained as immutable prerelease
> evidence; a corrected version will use new package bytes and a new version.

Current release status and supported evaluation routes are maintained in the
centralized
[`docs/distribution.md`](https://github.com/weita2026/ait-native/blob/main/docs/distribution.md)
product document.
