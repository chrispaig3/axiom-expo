# Axiom-Expo

> `axiom-expo` is a reverse engineering effort to bring back a tool I accidentally deleted from GitHub (the irony lol).
> ***Luckily, I retained a local copy of an expo binary because it is a tool I reach for frequently.***
> This is a rewrite in my own programming language called Axiom.

## Motivation for Expo

- Expo was initially written in Rust. The name was inspired by the marker and dry eraser brand.

> **Description**: Expo is a tool for managing the accessibility of GitHub repositories at scale.

## Building

0. Install Axiom latest

- Prequisites: Make sure you have Rust, and LLVM installed. `llc` needs to be in PATH.
  - You also need the GitHub CLI; that is is how authentication is handled.
- clone `https://github.com/chrispaig3/Axiom`
- run `./scripts/bootstrap-from-seed.sh --install .axiom-bin` and then add it to path
1. install the build tool `cargo install just`
2. run `just`
3. add it to PATH
> The binary size of Expo is only 74.5 kb

## Basic Usage

- `expo delete owner/repo`
- `expo help`
