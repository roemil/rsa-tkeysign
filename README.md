[![ci](https://github.com/tillitis/tkeysign/actions/workflows/ci.yaml/badge.svg?branch=main&event=push)](https://github.com/tillitis/tkeysign/actions/workflows/ci.yaml) [![Go Reference](https://pkg.go.dev/badge/github.com/tillitis/tkeysign.svg)](https://pkg.go.dev/github.com/tillitis/tkeysign)

# Tillitis TKey Sign package

A Go package for communicating with the [`signer` device
app](https://github.com/tillitis/tkey-device-signer) on a
[Tillitis](https://tillitis.se/) TKey to get cryptographic signatures
over a message.

See the [Go doc](https://pkg.go.dev/github.com/tillitis/tkeysign)
for `tkeysign` for details on how to call the functions.

See [tkey-ssh-agent](https://github.com/tillitis/tkey-ssh-agent) and
[tkey-sign-cli](https://github.com/tillitis/tkey-sign-cli) for client
applications using this go package.

Release notes in [RELEASE.md](RELEASE.md).

## Licenses and SPDX tags

Unless otherwise noted, the project sources are licensed under the
terms and conditions of the "GNU General Public License v2.0 only":

> Copyright Tillitis AB.
>
> These programs are free software: you can redistribute it and/or
> modify it under the terms of the GNU General Public License as
> published by the Free Software Foundation, version 2 only.
>
> These programs are distributed in the hope that it will be useful,
> but WITHOUT ANY WARRANTY; without even the implied warranty of
> MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU
> General Public License for more details.

> You should have received a copy of the GNU General Public License
> along with this program. If not, see:
>
> https://www.gnu.org/licenses

See [LICENSE](LICENSE) for the full GPLv2-only license text.

External source code we have imported are isolated in their own
directories. They may be released under other licenses. This is noted
with a similar `LICENSE` file in every directory containing imported
sources.

The project uses single-line references to Unique License Identifiers
as defined by the Linux Foundation's [SPDX project](https://spdx.org/)
on its own source files, but not necessarily imported files. The line
in each individual source file identifies the license applicable to
that file.

The current set of valid, predefined SPDX identifiers can be found on
the SPDX License List at:

https://spdx.org/licenses/
