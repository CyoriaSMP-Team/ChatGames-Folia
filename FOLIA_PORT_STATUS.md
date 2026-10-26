# ChatGames Folia 1.4.6 — upstream Folia build

This repository is a fork of [RareHyperIonYT/ChatGames](https://github.com/RareHyperIonYT/ChatGames).
ChatGames **already contains an upstream `folia` module** (with `folia-supported`
in its plugin descriptor). The binary here is a tested packaging of that
upstream Folia module, **not a claim that Cyoria authored its Folia support**.

- Original license: MIT (`LICENSE`); all upstream credit retained.
- Target: Minecraft 1.21.11 / Folia 1.21.11.
- Verified: plugin loaded in isolated and CyoriaSMP production startup smoke.
- Unverified: real-player mini-game rounds, multi-region chat concurrency and
  permission interactions; please test before production use.

Use the original author's builds/releases where possible; this is provided for
reproducibility of CyoriaSMP testing. It is not an official upstream release.
