# STX Semi-Fungible Market

Example implementation of the semi-fungible token standard applied to decentralised marketplaces on Stacks Blockchain. This example also includes the [Trait for minting NFT's with any FT and STX using unified interface](https://github.com/stacksgov/sips/issues/60) - enabling minting, listing and buying in any FT (including STX) using the same function calls.

The marketplace for Semi-fungible tokens connects to a SIP 013 contract for transfer of SFTs between user accounts.

## Post Conditions

See the [SIP-013 Repo](https://github.com/Clarity-Innovation-Lab/stx-semi-fungible-token) for a description of the novel mechanism for post conditions for semi-fungibles. The Clarinet tests in this example contain helper functions for testing the burn/mint event pairs emitted when transferring SFT's.
