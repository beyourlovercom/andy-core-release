# Andy Core Release Channel

Public signed distribution repository for Andy Core WordPress updates.

This repository intentionally does **not** contain the Andy Core source tree, development branches, pull requests, tests, or private implementation history. Canonical source development remains in the private `beyourlovercom/YBY-Core` repository.

Stable GitHub Releases published here contain the signed WordPress update package and verification evidence. Installed Andy Core sites read this repository anonymously and require no GitHub token, SSH access, or `wp-config.php` update credential.

Release assets are expected to include:

- `andy-core-vX.Y.Z.zip`
- `SHA256.txt`
- `update-metadata.json`
- `update-metadata.sig`
- `BUILD_INFO.md`
- release notes, upgrade guide, and rollback guide

Update acceptance remains protected by SHA-256, pinned Ed25519 signatures, strict ZIP validation, database compatibility checks, bounded code backup, post-install health validation, and rollback.
