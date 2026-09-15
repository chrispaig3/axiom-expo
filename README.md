# Axiom-Expo

> `axiom-expo` is a reverse engineering effort to bring back a tool I accidentally deleted from GitHub (the irony lol).
> ***Luckily, I retained a local copy of expo because it is a tool I reach for frequently.***
> This is a rewrite in my own programming language called Axiom.

## Motivation for Expo

- Expo was initially written in Rust. The name was inspired by the markers and dry erasers.

> **Description**: Expo is a tool for managing the accessability of GitHub repositories at scale.

## Building

1. Install Axiom latest

- Prequisites: Make sure you have Rust, and LLVM installed. `llc` needs to be in path.
- clone `https://github.com/chrispaig3/Axiom`
- run `./scripts/bootstrap-from-seed.sh --install .axiom-bin` and then add it to path
- install `just` `cargo install just`
- run `just` 
