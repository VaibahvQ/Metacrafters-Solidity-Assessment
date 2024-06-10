# Token.sol

This repository contains the source code for a simple ERC20 token contract implemented in Solidity. The contract allows for minting and burning of tokens, with basic access control mechanisms.

## Contract Details

- **Name**: VAIBHAV Token
- **Symbol**: GUPTA
- **Total Supply**: Variable (initialized to 0)

## Contract Functions

- `mint(address _to, uint256 _value)`: Allows a designated minter to create new tokens and assign them to a specified address.
- `burn(address _from, uint256 _value)`: Allows a designated burner to destroy existing tokens from a specified address.

## Access Control

The contract uses role-based access control for minting and burning operations:
- `MINTER_ROLE`: Assigned to addresses allowed to mint new tokens.
- `BURNER_ROLE`: Assigned to addresses allowed to burn existing tokens.

## Usage

1. Deploy the contract on an Ethereum-compatible network.
2. Assign the minter and burner roles to designated addresses.
3. Mint tokens using the `mint` function.
4. Burn tokens using the `burn` function.


## License

This project is licensed under the [MIT License](LICENSE).
