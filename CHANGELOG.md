# Changelog

All notable user-visible changes to the etherpad TOS application package.

## 3.1.0-2 — 2026-11-12

### Changed
- Icon: replaced the letter monogram with a functional vector mark that describes what the app does (the upstream project does not publish a compliant SVG).

## 3.1.0-1 — 2026-11-11

### Added
- First release. etherpad (`etherpad/etherpad:3.1.0`, Docker Hub official image, unmodified)
  packaged as a TOS 7 Docker application, published on port 8058 and running
  as a non-root user (5001:5001).
- Persistent data is kept under `/Volume1/DockerAppData/etherpaddocker/`.
