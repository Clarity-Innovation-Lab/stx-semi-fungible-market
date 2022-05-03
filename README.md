# STX Semi-Fungible Market

Example implementation of the semi-fungible token standard for decentralised marketplaces o Stacks Blockchain. It also includes the [Trait for minting NFT's with any FT and STX using unified interface](https://github.com/stacksgov/sips/issues/60) - enabling minting, listing and buying in any FT (including STX) in same function calls.

The marketplace for Semi-fungible tokens connects to a SIP 013 contract for transfer of SFTs between user accounts.

## Post Conditions

Post conditions follow the [standard](https://github.com/Clarity-Innovation-Lab/stx-semi-fungible-token) and the Clarinet tests in this example contain helper functions to help test the burn/mint event pairs emitted when transferring SFTs.