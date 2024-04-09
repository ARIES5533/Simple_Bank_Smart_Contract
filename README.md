# Simple_Bank_Smart_Contract

This Solidity smart contract named `ARIES_SimpleBank` simulates a simple bank account system. It allows the owner of the contract to deposit and withdraw funds. The contract is compiled using Solidity version 0.8.17 and can be deployed and interacted with using Remix IDE.

## Features

- Deposit funds: Only the owner of the bank account can deposit funds into the contract.
- Withdraw funds: Only the owner of the bank account can withdraw funds from the contract.

## Deployment and Interaction on Remix

1. Open Remix IDE ([https://remix.ethereum.org/](https://remix.ethereum.org/)).
2. Create a new Solidity file and paste the contract code into the editor.
3. Compile the contract by selecting the appropriate Solidity compiler version (0.8.17).
4. Deploy the contract by selecting the correct environment (e.g., JavaScript VM, Injected Web3).
5. Once deployed, interact with the contract by calling its functions from the Remix IDE.

### Deposit Funds

1. In the "Deployed Contracts" section, locate the deployed `ARIES_SimpleBank` contract.
2. Click on the contract instance to expand its functions.
3. Enter a value greater than zero in the "value" field.
4. Click on the "deposit" function to deposit funds into the contract.

### Withdraw Funds

1. In the "Deployed Contracts" section, locate the deployed `ARIES_SimpleBank` contract.
2. Click on the contract instance to expand its functions.
3. Enter the amount to withdraw in the "Value" field of the "withdraw" function.
4. Click on the "withdraw" function to withdraw funds from the contract.

## Example Interaction

1. Deploy the contract on Remix.
2. Deposit some funds into the contract using the "deposit" function.
3. Verify that the funds have been deposited successfully by checking the contract balance.
4. Withdraw some funds from the contract using the "withdraw" function.
5. Verify that the withdrawn amount has been transferred to the owner's account.

_Happy Learning!_

