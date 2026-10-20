# DustifyAIO — releases (no source)

Public download + update feed for **Discord members**. Source lives in a separate **private** repo.

## For members

1. Join the Dustify Discord and get the member role
2. Download the latest EXE from [Releases](https://github.com/m4xmax/DustifyAIO-releases/releases)
3. Sign in with Discord inside the app (role-gated)

Do **not** redistribute the EXE outside the server.

## Update feed

`latest.json` on `main` is what the app checks on splash:

https://raw.githubusercontent.com/m4xmax/DustifyAIO-releases/main/latest.json

## Maintainers

1. Build EXE locally from private source
2. Upload as a GitHub Release asset (tag `vX.Y.Z`)
3. Update `latest.json` → version + asset URL + notes
4. Members see the update prompt on next launch

This repo must never contain Python/TS source — only binaries, `latest.json`, and this README.
