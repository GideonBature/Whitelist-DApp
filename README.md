# Whitelist-DApp
This is the repository where I will be posting all the dApps I will be creating, especially as I learn from LearnWeb3.io

## Whitelist-DApp

The "Whitelist-DApp" project consists of two contracts: `Whitelist` and `Lock`.

### Whitelist Contract

The `Whitelist` contract allows for the whitelisting of addresses. It includes the following functions and state variables:

- `maxWhitelistedAddresses`: The maximum number of whitelisted addresses allowed.
- `whitelistedAddresses`: A mapping to keep track of whitelisted addresses.
- `numAddressesWhitelisted`: The number of addresses that have been whitelisted.
- `addAddressToWhitelist()`: A function to add the address of the sender to the whitelist.

You can find the complete code for the `Whitelist` contract [here](https://github.com/GideonBature/Smart-Contract-Projects/blob/main/Whitelist.sol).

### Lock Contract

The `Lock` contract allows for time-based withdrawal of funds. It includes the following functions and state variables:

- `unlockTime`: The timestamp when the funds can be withdrawn.
- `owner`: The owner of the contract.
- `withdraw()`: A function to withdraw funds from the contract.

You can find the complete code for the `Lock` contract [here](https://github.com/GideonBature/Smart-Contract-Projects/blob/main/Lock.sol).

Feel free to explore the code and further understand the functionality of the "Whitelist-DApp" project.
