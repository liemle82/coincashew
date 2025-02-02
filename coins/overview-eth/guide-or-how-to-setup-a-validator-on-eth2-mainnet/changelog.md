# Changelog

## :page\_facing\_up: List of changes

* Added [MEV-boost guide.](../mev-boost/)
* Updated to be mainnet merge ready.
* Are you ready for the Merge? [**Ethereum Merge Upgrade Checklist for Home Stakers and Validators**](https://www.coincashew.com/coins/overview-eth/ethereum-merge-upgrade-checklist-for-home-stakers-and-validators)
* Updated to use staking-deposit-cli
* \#TestingTheMerge on Ropsten: New Automated Install Script for the [Most Diverse Client: Besu+Lodestar](https://github.com/coincashew/ethereum-scripts/blob/main/README.md)
* Guides for Ropsten and [Kiln "Merge Testnets"](https://www.coincashew.com/coins/overview-eth/guide-or-besu-+-lodestar-or-most-viable-diverse-client-or-staking-ethereum-on-kiln-testnet)
* \#TestingTheMerge Guide on [Pithos Testnet](https://www.coincashew.com/coins/overview-eth/guide-or-how-to-setup-a-validator-for-ethereum-staking-on-pithos-testnet-in-10-minutes-or-less)
* Migration Guide with the goal of increasing ClientDiversity: [**Operation Client Diversity: Migrate Prysm to Teku**](https://www.coincashew.com/coins/overview-eth/guide-or-operation-client-diversity-migrate-prysm-to-teku)
* Updated besu execution client to use BONSAI format
* Restructured guide for improved speed and readability
* Added how to check your [Validator's Sync Committee duties](part-ii-maintenance/checking-my-eth-validators-sync-committee-duties.md)
* Added new Formatting fixes and updated Teku initial state API.
* Updated with consensus layer (CL), the execution layer (EL), formerly known as eth2 and eth1.
* Added erigon build dependencies.
* Added Teku and Lodestar Checkpoint Sync feature, the quickest way to sync a Ethereum beacon chain client.
* geth + erigon pruning / Altair hard fork changes / nimbus eth1 fallback
* lighthouse + prysm doppelganger protection enabled. Doppelganger protection intentionally misses an epoch on startup and listens for attestations to make sure your keys are not still running on the old validator client.
* OpenEthereum will no longer be supported post London hard fork. Gnosis, maintainers of OpenEthereum, suggest users migrate to their new Erigon Ethererum client. Added setup instructions for **Erigon** under eth1 node section.
* Added [Mobile App Node Monitoring by beaconcha.in](part-i-installation/mobile-app-node-monitoring-by-beaconchain.md)
* Updated staking-deposit-cli and added section on eth1 withdrawal address
* Added generating mnemonic seeds on **Tails OS** by [punggolzenith](https://github.com/punggolzenith)
* Iancoleman.io BLS12-381 Key Generation Tool [how-to added](part-iii-tips/eip2333-key-generator-by-iancoleman-io.md)
* Testnet guide forked for [Prater testnet](../guide-or-how-to-setup-a-validator-on-eth2-testnet-prater.md) staking
* [Geth pruning guide](part-ii-maintenance/pruning-the-execution-client-to-free-up-disk-space.md) created
* Major changes to Lodestar guide
* Additional [Grafana Dashboards](part-i-installation/monitoring-your-validator-with-grafana-and-prometheus.md) for Prysm, Lighthouse and Nimbus
* [Validator Security Best Practices added](part-i-installation/guide-or-security-best-practices-for-a-eth2-validator-beaconchain-node.md)
* Translations now available for Japanese, Chinese and Spanish (access by changing site language)
* Generate keystore files on [Ledger Nano X, Nano S and Trezor Model T](part-i-installation/signing-up-to-be-a-validator-at-the-launchpad.md) with tool from [allnodes.com](https://twitter.com/Allnodes/status/1390020240541618177?s=20)
* [Batch deposit tool](part-i-installation/signing-up-to-be-a-validator-at-the-launchpad.md) by [abyss.finance](https://twitter.com/AbyssFinance/status/1379732382044069888) now added
