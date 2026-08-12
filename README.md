# k9s for Debian

[k9s](https://github.com/derailed/k9s) — Kubernetes CLI to manage your clusters in style — packaged for
Debian as part of [latest-debs](https://github.com/latest-debs).

## Install

Via the latest-debs apt repository:

```sh
sudo extrepo enable latest-debs
sudo apt update
sudo apt install k9s
```

Or download a `.deb` from the [Releases](https://github.com/latest-debs/k9s-debian/releases) page:

```sh
sudo dpkg -i k9s_*.deb
```

## Supported distributions & architectures

- Debian Bookworm (12), Trixie (13), Forky (14/testing), Sid (unstable)
- amd64, arm64, armhf, i386 (bookworm/trixie) — actual per-release availability depends on what upstream publishes

## Building

Run the [Build k9s for Debian](../../actions) workflow on GitHub with the
desired upstream version. Packaging is driven by
[debian-multiarch-builder](https://github.com/ranjithrajv/debian-multiarch-builder).

## Disclaimer

Unofficial packaging only. For issues with k9s itself, see
[derailed/k9s](https://github.com/derailed/k9s).
