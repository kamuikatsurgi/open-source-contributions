# My Open Source Journey

## Major Contributions

**[Foundry](https://github.com/foundry-rs/foundry)** - _Ethereum Development Toolkit_

**10 Merged PRs**

<details>
<summary>View contributions</summary>

- [#7767](https://github.com/foundry-rs/foundry/pull/7767) UintToHex cheatcode
- [#7731](https://github.com/foundry-rs/foundry/pull/7731) Return cast logs in all cases
- [#7725](https://github.com/foundry-rs/foundry/pull/7725) Fix typos in forge clone
- [#7600](https://github.com/foundry-rs/foundry/pull/7600) Prompt address and uint cheatcodes
- [#7598](https://github.com/foundry-rs/foundry/pull/7598) Blobbasefee cheatcode
- [#7588](https://github.com/foundry-rs/foundry/pull/7588) kB to B in forge build --sizes
- [#7539](https://github.com/foundry-rs/foundry/pull/7539) Index cheatcode for strings
- [#7526](https://github.com/foundry-rs/foundry/pull/7526) Print IPC path in anvil
- [#7389](https://github.com/foundry-rs/foundry/pull/7389) Socket address as --rpc-url input in anvil
- [#7369](https://github.com/foundry-rs/foundry/pull/7369) Compile contracts before generating docs

</details>

---

**[Reth](https://github.com/paradigmxyz/reth)** - _Ethereum Execution Client_

**10 Merged PRs**

<details>
<summary>View contributions</summary>

- [#17008](https://github.com/paradigmxyz/reth/pull/17008) Add size field in the new_header_stream method
- [#16888](https://github.com/paradigmxyz/reth/pull/16888) Use max_blobs_per_tx in validating eip4844 txs
- [#16879](https://github.com/paradigmxyz/reth/pull/16879) Fix eth_getBlockReceipts err for genesis block in op-reth
- [#12537](https://github.com/paradigmxyz/reth/pull/12537) Implement Compact for OpTxType
- [#9301](https://github.com/paradigmxyz/reth/pull/9301) Resolve trusted peers
- [#8914](https://github.com/paradigmxyz/reth/pull/8914) Move calculate_intrinsic_gas_after_merge to tx pool
- [#8877](https://github.com/paradigmxyz/reth/pull/8877) Support no_std for ethereum-forks
- [#8718](https://github.com/paradigmxyz/reth/pull/8718) Add append_receipts function
- [#8698](https://github.com/paradigmxyz/reth/pull/8698) Remove Bandwidthmeter type
- [#7314](https://github.com/paradigmxyz/reth/pull/7314) Returns an error if multiplex message is empty

</details>

---

**[rust-libp2p](https://github.com/libp2p/rust-libp2p)** - _Rust P2P Networking Library_

**13 Merged PRs**

<details>
<summary>View contributions</summary>

- [#6045](https://github.com/libp2p/rust-libp2p/pull/6045) Use tokio instead of async_std in libp2p-mplex
- [#6037](https://github.com/libp2p/rust-libp2p/pull/6037) Use tokio instead of async_std in swarm
- [#6031](https://github.com/libp2p/rust-libp2p/pull/6031) Use tokio instead of async_std in libp2p-uds tests
- [#6028](https://github.com/libp2p/rust-libp2p/pull/6028) Use tokio instead of async-std in libp2p-websocket
- [#6023](https://github.com/libp2p/rust-libp2p/pull/6023) Use tokio instead of async-std in rw-stream-sink tests
- [#5953](https://github.com/libp2p/rust-libp2p/pull/5953) Fix ipfs-kad example usage
- [#5828](https://github.com/libp2p/rust-libp2p/pull/5828) Use tokio instead of async-std
- [#5725](https://github.com/libp2p/rust-libp2p/pull/5725) Introduce libp2p-test-utils
- [#5671](https://github.com/libp2p/rust-libp2p/pull/5671) Replace async-std with tokio in autonat tests
- [#5663](https://github.com/libp2p/rust-libp2p/pull/5663) Make identify::Config fields private
- [#5662](https://github.com/libp2p/rust-libp2p/pull/5662) Refactor dcutr and gossipsub tests to use tokio
- [#5655](https://github.com/libp2p/rust-libp2p/pull/5655) Refactor ping tests
- [#5652](https://github.com/libp2p/rust-libp2p/pull/5652) Refactor distributed-key-value-store example

</details>

---

## Filecoin Ecosystem

**12 Merged PRs**

<details>
<summary><strong>Lotus</strong></summary>

| PR                                                             | Description                                                    |
| :------------------------------------------------------------- | :------------------------------------------------------------- |
| [#13118](https://github.com/filecoin-project/lotus/pull/13118) | Only markdown action to skip some CI workflows                 |
| [#12962](https://github.com/filecoin-project/lotus/pull/12962) | Upgrade golang.org/x packages and go-pubsub to latest versions |
| [#12707](https://github.com/filecoin-project/lotus/pull/12707) | nv25 network skeleton                                          |
| [#12631](https://github.com/filecoin-project/lotus/pull/12631) | Update network skeleton docs                                   |

</details>

<details>
<summary><strong>Builtin Actors</strong></summary>

| PR                                                                    | Description                                                              |
| :-------------------------------------------------------------------- | :----------------------------------------------------------------------- |
| [#1586](https://github.com/filecoin-project/builtin-actors/pull/1586) | Remove PRE_COMMIT_SECTOR_BATCH_MAX_SIZE and other gas-limited parameters |
| [#1570](https://github.com/filecoin-project/builtin-actors/pull/1570) | Remove Option around SectorPreCommitInfoInner.unsealed_cid               |

</details>

<details>
<summary><strong>Go State Types</strong></summary>

| PR                                                                  | Description               |
| :------------------------------------------------------------------ | :------------------------ |
| [#304](https://github.com/filecoin-project/go-state-types/pull/304) | Add simple nv24 migration |
| [#299](https://github.com/filecoin-project/go-state-types/pull/299) | Add nv24 skeleton         |

</details>

<details>
<summary><strong>Reference FVM</strong></summary>

| PR                                                             | Description       |
| :------------------------------------------------------------- | :---------------- |
| [#2030](https://github.com/filecoin-project/ref-fvm/pull/2030) | Release 4.3.2     |
| [#2029](https://github.com/filecoin-project/ref-fvm/pull/2029) | Add nv24-skeleton |

</details>

<details>
<summary><strong>Filecoin FFI</strong></summary>

| PR                                                                | Description        |
| :---------------------------------------------------------------- | :----------------- |
| [#479](https://github.com/filecoin-project/filecoin-ffi/pull/479) | Add nv-24 skeleton |

</details>

<details>
<summary><strong>Rust FIL Proofs</strong></summary>

| PR                                                                     | Description                                |
| :--------------------------------------------------------------------- | :----------------------------------------- |
| [#1760](https://github.com/filecoin-project/rust-fil-proofs/pull/1760) | Use workspace inheritance for dependencies |

</details>

---

## Additional Ethereum Ecosystem Contributions

**Lighthouse** — Ethereum Consensus Client

- [#5318](https://github.com/sigp/lighthouse/pull/5318) Doesn't post if attestations is empty

**Foundry Compilers**

- [#100](https://github.com/foundry-rs/compilers/pull/100) Add simpleCounterForLoopUncheckedIncrement optimization field

**CoW Protocol**

- [#154](https://github.com/cowprotocol/contracts/pull/154) StorageReadable unit tests
- [#156](https://github.com/cowprotocol/contracts/pull/156) StorageAccessible unit tests

**Chainlink CCIP**

- [#12](https://github.com/smartcontractkit/ccip-starter-kit-foundry/pull/12) Removed Base Goerli & Optimism Goerli and added Wemix & Kroma Sepolia networks

**Ethereum.org**

- [#11908](https://github.com/ethereum/ethereum-org-website/pull/11908) Open meetup links in new tabs

**Polygon Storage Delta**

- [#14](https://github.com/0xPolygon/storage-delta/pull/14) Fix dirty and undefined labels and added @ symbol

---
