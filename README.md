# Metacrafers-ETH-AVAX-mod3-Assessment


## MyToken

`MyToken` is an ERC20 token contract that allows the contract owner to mint tokens to a provided address, and any user to burn and transfer tokens.

## Installation

To use the `MyToken` contract, follow these steps:

1. Install the required dependencies:
   - OpenZeppelin Contracts: `npm install @openzeppelin/contracts`
2. Import the `MyToken` contract into your Solidity project:
   ```
   import "./MyToken.sol";
   ```
3. Deploy the `MyToken` contract to your desired network.

## Usage

To use the `MyToken` contract, follow these steps:

1. Mint tokens to a provided address by calling the `mint` function and passing in the address and amount of tokens to mint. This function can only be called by the contract owner.
2. Burn tokens by calling the `burn` function and passing in the amount of tokens to burn. This function can be called by any user.
3. Transfer tokens to another address by calling the `transfer` function and passing in the recipient's address and the amount of tokens to transfer. This function can be called by any user.

## Contributing

To contribute to the `MyToken` contract, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Submit a pull request.

## License

`MyToken` is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

`MyToken` is based on the OpenZeppelin Contracts library.
