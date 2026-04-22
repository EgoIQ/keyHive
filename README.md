# keyHive

OpenBao-based secret/key management for the egoHive platform. Deployed per trust boundary.

This repo is under active development as part of the egoHive Google-dependency removal refactor (Track 2). See [`egoHive/doc/plans/2026-04-22-google-dependency-removal-design.md`](https://github.com/egoiq/egoHive/blob/master/doc/plans/2026-04-22-google-dependency-removal-design.md) for the design spec.

## Components (to be implemented in Track 2)

- `keyhive` CLI (`pip install keyhive-cli`)
- Docker Compose module for deploying OpenBao + standardised policies
- Reference `SecretsProvider` client for egoHive

## License

MIT
