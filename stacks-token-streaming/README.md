# Token Streaming

A token streaming DeFi protocol built using Clarity for Stacks. Inspired by Superfluid.

This project was done as part of the "Introduction to Stacks" course for the "Stacks Developer Degree" on LearnWeb3.   

## Installation

### Install on macOS (Homebrew)

To install Clarinet on macOS, run the following command:

```bash
brew install clarinet
```   

### Install from source using Cargo

If you would like to install Clarinet from source using Cargo, there are some specific steps you will need to follow, which are described below.

#### Prerequisites

You must first [Install Rust](https://www.rust-lang.org/tools/install) to use the Rust package manager Cargo.

If you are using Debian and Ubuntu-based distributions, make sure to run the following command to install required packages before building Clarinet.

```bash
sudo apt install build-essential pkg-config libssl-dev curl
```   

```shell
gitpod /workspace/Lw3-Stacks-Token-Streaming/stacks-token-streaming (main) $ npm run test

> stacks-token-streaming-tests@1.0.0 test
> vitest run


 RUN  v1.5.2 /workspace/Lw3-Stacks-Token-Streaming/stacks-token-streaming

stdout | module.exports.__wbg_log_5bb5f88f245d7762 (/workspace/Lw3-Stacks-Token-Streaming/stacks-token-streaming/node_modules/@hirosystems/clarinet-sdk-wasm/clarinet_sdk.js:1163:13)
generated a new deployment plan

 ✓ tests/stream.test.ts (8) 2372ms
   ✓ test token streaming contract (8) 2372ms
     ✓ ensures contract is initialized properly and stream is created 821ms
     ✓ ensures stream can be refueled
     ✓ ensures stream cannot be refueled by random address
     ✓ ensures recipient can withdraw tokens over time
     ✓ ensures non-recipient cannot withdraw tokens from stream
     ✓ ensures sender can withdraw excess tokens
     ✓ signature verification can be done on stream hashes
     ✓ ensures timeframe and payment per block can be modified with consent of both parties

 Test Files  1 passed (1)
      Tests  8 passed (8)
   Start at  15:15:01
   Duration  4.44s (transform 139ms, setup 86ms, collect 66ms, tests 2.37s, environment 1.54s, prepare 237ms)
   ```   