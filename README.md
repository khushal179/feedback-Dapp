# feedback-Dapp

# Smart Contract Interaction Application

This repository contains a simple web application that interacts with a smart contract deployed on the Ethereum blockchain. The application allows users to view and update data stored in the smart contract through a user-friendly interface.

## Functionality

The smart contract deployed on the Ethereum blockchain contains two functions:

1. `setData1(uint256 _value)`: Sets the value of data1 to the provided `_value`.
2. `setData2(uint256 _value)`: Sets the value of data2 to the provided `_value`.

The values of `data1` and `data2` are visible on the frontend of the application, enabling users to see the current state of the smart contract. Users can also input new values for `data1` and `data2` through input fields and update the values by clicking on corresponding buttons.

## How to Use

To use the application, follow these steps:

1. Ensure you have an Ethereum provider like MetaMask installed in your browser.
2. Deploy the smart contract to the Ethereum blockchain using a tool like Remix or Truffle, and note down the contract address and ABI.
3. Clone this repository to your local machine.
4. Open the `index.html` file in your preferred web browser.
5. Connect MetaMask to the appropriate Ethereum network.
6. Enter the contract address and ABI in the `app.js` file.
7. Interact with the application by viewing and updating the values of `data1` and `data2`.

## Technologies Used

- Solidity: Used to write the smart contract.
- HTML: Used to structure the web page.
- JavaScript: Used to handle interactions with the smart contract and update the frontend.
- Web3.js: JavaScript library used to interact with Ethereum smart contracts.
