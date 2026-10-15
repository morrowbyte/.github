# morrowbyte

NixOS configurations and Nix packaging.

## Projects

- [WeaselOS](https://github.com/morrowbyte/weasel-os) — Modular NixOS configuration with shared system and Home Manager profiles, Niri and Dank Material Shell.
- [T3 Code](https://github.com/morrowbyte/t3code) — Fork of [pingdotgg/t3code](https://github.com/pingdotgg/t3code) for installation with Nix.

Setup instructions and project-specific notes live in each repository.

## CI infrastructure

Current Morrowbyte projects use Blacksmith runners for GitHub Actions CI, builds and deployment workflows. Runner acceptance covers Linux x64/ARM64, Windows x64 and macOS in [Blacksmith runner acceptance](https://github.com/morrowbyte/.github/actions/workflows/blacksmith-runner-smoke.yml). Native Windows ARM64 remains on GitHub because Blacksmith currently provides Windows x64 only. Historical Jarvis provenance fixtures retain their original contracts and are not dispatched as current CI.
