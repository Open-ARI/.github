<p align="center">
  <a href="https://openari.org"><img src="https://raw.githubusercontent.com/open-ari/.github/main/assets/openari-logo.png" alt="OpenARI mosaic logo" width="128" height="128"></a>
</p>

<h1 align="center">OpenARI</h1>

<p align="center">
  Independent open-source tools for Apple Reference Image verification and camera capture signing.
</p>

<p align="center">
  <a href="https://openari.org/status"><img src="https://img.shields.io/badge/status-in%20development-orange" alt="In development"></a>
  <a href="https://github.com/open-ari/.github/blob/main/LICENSE"><img src="https://img.shields.io/github/license/open-ari/.github" alt="Apache 2.0 license"></a>
  <a href="https://openari.org"><img src="https://img.shields.io/badge/docs-openari.org-007D79" alt="OpenARI documentation"></a>
  <a href="https://github.com/sponsors/shoon"><img src="https://img.shields.io/badge/Sponsor-shoon-EA4AAA?logo=githubsponsors&amp;logoColor=white" alt="Sponsor shoon on GitHub"></a>
</p>

We are building an Apple Reference Image verification engine, the openari CLI,
and language SDKs for applications that accept images. OpenARI Capture is a
separate SDK research track for signing and verifying capture evidence from
independent cameras, starting with a Raspberry Pi prototype and a path for
manufacturer integration.

The two projects use separate profiles and trust models. Independent capture
signatures are not Apple attestations. Security, explicit version support, and
predictable resource use guide both projects.

**Current status:** planning and development scaffold. No Apple ARI format
revision is supported yet. OpenARI cannot authenticate uploads today.
The capture SDK is an architecture-only scaffold; capture signing and verification
are not implemented yet.

- [Core, CLI, and architecture](https://github.com/open-ari/open-ari-core)
- [Independent capture SDK research](https://github.com/open-ari/openari-capture)
- [Documentation source](https://github.com/open-ari/website)
- [OpenARI.org](https://openari.org)
- [Implementation roadmap](https://github.com/open-ari/open-ari-core/blob/main/docs/roadmap.md)
- [Sponsor Shaun Murphy](https://github.com/sponsors/shoon)

OpenARI is not affiliated with or endorsed by Apple.
