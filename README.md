# Awesome Flake Parts with stars

A curated list of awesome [flake-parts](https://flake.parts/) resources, modules, and examples. Flake-parts is a framework for writing Nix Flakes that provides a modular approach to flake configuration.

## Contents

* [Official Resources](#official-resources)
* [Tutorials](#tutorials)
* [Blog Posts](#blog-posts)
* [Flake Modules](#flake-modules)
* [Example Projects](#example-projects)
* [Community](#community)

## Official Resources

* [flake-parts Website](https://flake.parts/) - Official documentation and guides.
* [flake-parts Repository](https://github.com/hercules-ci/flake-parts) ⭐ 1,448 | 🐛 78 | 🌐 Nix | 📅 2026-08-01 - Source code and issue tracker.
* [API Reference](https://flake.parts/options.html) - Comprehensive options reference.

## Tutorials

* [flake-parts to set up nodejs devshell](https://blog.eigenvalue.net/2024-flake-parts-nodejs-devshell/) - Tutorial about using flake-parts to set up a nodejs devshell.
* [Flake-parts: writing custom flake modules](https://vtimofeenko.com/posts/flake-parts-writing-custom-flake-modules/) - Primer on writing flake-parts reusable flake modules.
* [Dendritc Design with the Flake Parts Framework](https://github.com/Doc-Steve/dendritic-design-with-flake-parts) ⭐ 433 | 🐛 0 | 🌐 Nix | 📅 2026-01-28 - A guide on how to structure your Nix code with Flake Parts using the Dendritic Pattern.

## Blog Posts

* [Refactoring My Infrastructure As Code Configurations](https://not-a-number.io/2025/refactoring-my-infrastructure-as-code-configurations/) - About a migration from host-centric to feature centric nixos configuration.
* [Evaluating Den](https://not-a-number.io/2026/evaluating-den-a-dendritic-configuration-framework/) - blog about Den, A Dendritic Configuration Framework.

## Flake Modules

### Official Modules

* [flake-parts/modules](https://github.com/hercules-ci/flake-parts/tree/master/modules) ⭐ 1,448 | 🐛 78 | 🌐 Nix | 📅 2026-08-01 - Built-in modules.

### Community Modules

* [devshell](https://github.com/numtide/devshell) ⭐ 1,547 | 🐛 97 | 🌐 Nix | 📅 2026-06-18 - Improved developer shells.
* [nix-gaming](https://github.com/fufexan/nix-gaming) ⭐ 943 | 🐛 22 | 🌐 Nix | 📅 2026-08-22 - Gaming tools and configurations.
* [pre-commit-hooks-nix](https://github.com/cachix/pre-commit-hooks.nix) ⭐ 854 | 🐛 92 | 🌐 Nix | 📅 2026-08-11 - Git pre-commit hooks integration.
* [services flake](https://github.com/juspay/services-flake) ⭐ 763 | 🐛 56 | 🌐 Nix | 📅 2026-08-18 -  NixOS-like services for Nix as flake modules.
* [treefmt-nix](https://github.com/numtide/treefmt-nix) ⭐ 639 | 🐛 94 | 🌐 Nix | 📅 2026-08-16 - Declarative formatter configuration.
* [nixos-flake](https://github.com/srid/nixos-flake) ⭐ 371 | 🐛 22 | 🌐 Nix | 📅 2026-04-23 - Opinionated NixOS configuration with flake-parts.
* [nixos-unified](https://github.com/srid/nixos-unified) ⭐ 371 | 🐛 22 | 🌐 Nix | 📅 2026-04-23 - Flake-parts module to unify NixOS + nix-darwin + home-manager configuration in a single flake.
* [flake-root](https://github.com/srid/flake-root) ⭐ 64 | 🐛 0 | 🌐 Nix | 📅 2024-08-14 - Discover project root directory.
* [hercules-ci-effects](https://github.com/hercules-ci/hercules-ci-effects) ⭐ 34 | 🐛 39 | 🌐 Nix | 📅 2026-08-15 - CI/CD integration for flake-parts.
* [community.flake.parts](https://github.com/flake-parts/community.flake.parts) ⭐ 31 | 🐛 6 | 🌐 Nix | 📅 2026-08-19 - A Community website with links to several flake-module projects.
* [VTimofeenko/flake-modules](https://github.com/VTimofeenko/flake-modules) ⭐ 2 | 🐛 1 | 🌐 Nix | 📅 2025-10-22 - A collection of reusable flake modules, incl. a nice inputs bumber.

## Related Patterns, Frameworks, Utilities and Libraries

* [The Dendritic Pattern](https://github.com/mightyiam/dendritic) ⭐ 604 | 🐛 1 | 📅 2026-07-31 - Nix flake-parts usage pattern in which every Nix file is a flake-parts module.
* [import-tree](https://github.com/vic/import-tree) ⭐ 322 | 🐛 1 | 🌐 Nix | 📅 2026-07-17 - Import all nix files in a directory tree.
* [flake-file](https://github.com/vic/flake-file) ⭐ 144 | 🐛 13 | 🌐 Nix | 📅 2026-07-28 - Dynamically generate your flake.nix from flake-parts modules.
* [Dendritic Nix](https://github.com/vic/dennix) ⭐ 136 | 🐛 1 | 🌐 Nix | 📅 2026-01-27 - Community-driven Nix distribution based on the Dendritic pattern.
* [Flake-parts Builder](https://github.com/tsandrini/flake-parts-builder) ⭐ 48 | 🐛 14 | 🌐 Rust | 📅 2025-11-24 - Nix flakes interactive template builder based on flake-parts written in Rust.
* [Flake-Parts-Graph (fpg)](https://github.com/giomf/flake-parts-graph) ⭐ 35 | 🐛 1 | 🌐 Python | 📅 2026-07-24 - Visualize flake-parts module dependency graphs.
* [Unify](https://codeberg.org/quasigod/unify/) - Framework for unifying multiple types of Nix configurations.

## Personal Dotfiles & Infra repo's using flake-parts

* [srid/nixos-config](https://github.com/srid/nixos-config) ⭐ 586 | 🐛 4 | 🌐 Nix | 📅 2026-08-21 - NixOS configuration with flake-parts.
* [mightyiam/infra](https://github.com/mightyiam/infra) ⭐ 200 | 🐛 14 | 🌐 Nix | 📅 2026-08-21 - Shahar "Dawn" Or (mightyiam)'s personal Nix-powered IT infrastructure repository.
* [dropol/infra](https://github.com/drupol/infra) ⭐ 149 | 🐛 1 | 🌐 Nix | 📅 2026-08-19 - Pol Dellaiera's configuration of all his home computers.
* [vic/vix](https://github.com/vic/vix) ⭐ 95 | 🐛 25 | 🌐 Nix | 📅 2026-04-28 - Vic's \*Nix config with flake-parts and [import-tree](https://github.com/vic/import-tree) ⭐ 322 | 🐛 1 | 🌐 Nix | 📅 2026-07-17.
* [VTimofeenko/monorepo-machine-config](https://github.com/VTimofeenko/monorepo-machine-config) ⭐ 28 | 🐛 0 | 🌐 Nix | 📅 2026-07-31 - Monorepo containing dotfiles and machine configurations.
* [dtomvan/puntbestanden](https://github.com/dtomvan/puntbestanden) ⭐ 15 | 🐛 1 | 🌐 Nix | 📅 2026-08-22 - Tom van Dijk's monolithic, interconnected NixOS/HomeManager/Nixvim configs.
* [quasigod/nixconfig](https://codeberg.org/quasigod/nixconfig) - NixOS and Home Manager configurations with flake-parts and [unify](https://codeberg.org/quasigod/unify/).

## Community

* [GitHub Discussions](https://github.com/hercules-ci/flake-parts/discussions) ⭐ 1,448 | 🐛 78 | 🌐 Nix | 📅 2026-08-01 - Q\&A and discussions.

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, the authors have waived all copyright and related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-22._
