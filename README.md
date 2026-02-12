# vimOS

vimOS is an experimental modal-native operating system project.

## Overview

vimOS explores a system design where interaction is modeled as explicit intention rather than event dispatch. The core premise is that operating-system-level workflows can be structured using modal semantics, composable command units, and deterministic state transitions.

## Philosophy

- **Modal interaction first**: modes are first-class system primitives.
- **Semantic object control**: commands target named system objects, not incidental pointers.
- **Composable operations**: small operations compose into predictable workflows.
- **Determinism**: execution paths should be inspectable and reproducible.

## Scope

This is not a conventional GUI operating system. It is a keyboard-only interaction model research project that uses low-level implementation work to validate interface theory.

## Target Architecture

Current implementation work targets **RISC-V** as the primary architecture for early validation.

## Development Stage

Status: **early theory and prototype stage**.

The repository currently focuses on:

- Project philosophy and architecture framing
- Initial semantic command engine design direction
- Minimal post and documentation structure for project intent

## Roadmap (Short)

1. Define command grammar and modal state model.
2. Implement minimal semantic command dispatcher.
3. Prototype object model and deterministic command execution on RISC-V.
4. Validate end-to-end interaction loop in a minimal runtime.
5. Expand toward a usable modal-native shell environment.

## Domain

Primary project domain: **https://vimos.org**
