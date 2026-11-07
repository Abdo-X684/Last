# BugfixedHL — Opposing Force port workspace

This repository tracks the two upstream codebases required for the Opposing Force port.

- BugfixedHL-Rebased: `upstream/BugfixedHL-Rebased`
- Updated Opposing Force SDK: `upstream/halflife-op4-updated`

## Status

**Workspace bootstrap only — the Opposing Force port is not implemented yet.**

The upstream projects are separate codebases with different build systems and source layouts. The port still requires a source-level integration of the OP4 client/game DLL code into BugfixedHL's CMake/Linux build, followed by a 32-bit Linux build and runtime testing. This repository must not be treated as a finished or tested build.

## Checkout

```sh
git clone --recurse-submodules https://github.com/Abdo-X684/Last.git
cd Last
```

Upstreams:
- https://github.com/tmp64/BugfixedHL-Rebased
- https://github.com/twhl-community/halflife-op4-updated
