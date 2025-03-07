# Changelog

All notable changes to this project will be documented in this file.

*Unreleased*

*Released*

## [v0.1.2] - 2021-03-29

### Bug Fixes
- Fix transaction failures on Ledger custom index wallet creations
- Remove MacOS zip binary from release builds which was not being signed

### Additions
- Show detailed error messages on all transaction failure types
- Present up to 8 decimals places for extra-small numbers amounts in transaction views
- Add a physical refresh button for loading and syncing the latest transactions and balance states

## [v0.1.1] - 2021-03-25

### Bug Fixes
- Fix blank screens issues on older databases
- Fetch a new validator set to the store on wallet change event


## [v0.1.0] - 2021-03-24

### Additions
- First release with mainnet configuration support
- Added capability to customize gas limit and network fee on transactions
- Introduced a capability to specify address index for Ledger wallet creations
- Added support for re-delegation in the wallet

## [v0.0.25] - 2021-03-12

### Bug Fixes
- Updated dependency vulnerability issue on react-dev-util

### Additions
- More integration tests

## [v0.0.24] - 2021-03-04

### Bug Fixes

- Fixed an issue that could block wallet creation with Ledger devices

## [v0.0.23] - 2021-03-01

### Bug Fixes

- Fixed an issue that could cause the application crashed on Mac OS

## [v0.0.22] - 2021-02-17

### Added Features

- Added support for Ledger based wallet on creation
- Introduced initial support for undelegation transactions, for both normal wallets and Ledger wallets

## [v0.0.21] - 2021-02-10

### Added Features

- Provide staking validators option for users when trying to delegate funds

## [v0.0.20] - 2021-02-08

### Added Features

- Good handling of maximum transfer or staking transactions
- Show user the fee that is being deducted on the transaction
- Present UI/UX tag of the transaction status in the transfer transaction listing

### Security Fixes & Improvements

- Replace previous pre-encryption disk persistence by temporary memory state that's flushed later on


## [v0.0.13] - 2021-01-07

### Added Features

- The capability to modify current wallet node configurations were added (NodeURL and ChainID)
- Make address validation checks stricter on transfer, prevent input of wrong validator address

### Changed Behaviours
- Hiding devtools tab on production builds and only show it on dev mode

### Known Limitation

- This wallet is only testnet-ready, do not use in mainnet.
- Do not transfer any ERC20 tokens to addresses generated by this sample code as it can cause loss of funds.
- Crypto.com is not liable for any potential damage, loss of data/files arising from the use of the wallet.
