# react-codemod - Agent Guide

This is the agent-facing guide for working in this repository.

## Project Context
- React codemod scripts

## Setup
See [`agents.yaml`](./agents.yaml) for prerequisites, commands, and ports.

### Setup Hints
- `nvm` may not be loaded in your shell. If `nvm: command not found`, source it first.

## Running the App
- Clone the repo
- Install: `npm install`
- This is a codemod library - no dev server available

## Architecture
- React codemod scripts using jscodeshift
- Entry point: `transforms/index.js`

## Working Agreement
- Write modular code
- Keep testable
- Incremental validation
- Commit meaningful checkpoints
- Write tests
- Validate before handoff
