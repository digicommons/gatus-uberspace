# gatus-uberspace

Unofficial, statically-linked builds of [TwiN/gatus](https://github.com/TwiN/gatus), packaged for [Uberspace](https://uberspace.de).

Currently, [TwiN/gatus](https://github.com/TwiN/gatus) doesn't provide precompiled binaries (see [open issue](https://github.com/TwiN/gatus/issues/831)) and instead [suggests](https://github.com/TwiN/gatus/commit/807599c05e37fb9a0b83d36650086b0638c20d70) to `go install` the app. Unfortunately, this may consume too many resources on a shared hosting setup - hence the pre-built binaries.

Each release is built from the unmodified upstream source at the matching tag with `CGO_ENABLED=0 go build`.

> [!IMPORTANT]
> This project is not affiliated with, sponsored by, or endorsed by the Gatus project or its author. "Gatus" is used only to describe what these binaries are.

Licensed under Apache-2.0. Also see the LICENSE bundled in each release artifact for the license of the upstream project.