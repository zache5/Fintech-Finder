# Fintech-Finder
This code is designed to provide a cryptocurrency wallet for Fintech Finder customers. The code performs several tasks:

Generates a new Ethereum account instance using the customer's mnemonic seed phrase,
Fetches and displays the account balance associated with the Ethereum account address,
Calculates the total value of an Ethereum transaction, including the gas estimate,
Digitally signs a transaction and sends it to the Ganache blockchain, and 
Reviews the transaction hash code associated with the validated blockchain transaction

## Imports
The code uses the following import statements:
import streamlit as st, 
from dataclasses import dataclass, 
from typing import Any, List, 
from web3 import Web3, and 
w3 = Web3(Web3.HTTPProvider('HTTP://127.0.0.1:7545'))

## Usage
The code creates a Fintech Finder customer interface and includes wallet operations. The customer's Ethereum wallet and account information is provided to the application. The following steps outline how to use the code: Create a variable named account and set it equal to a call on the generate_account function. This function will create the customer's HD wallet and Ethereum account. In the Streamlit sidebar section of the code, define a st.sidebar.write function to display the balance of the customer's account. Inside this function, call the get_balance function and pass it the customer's Ethereum account.address.

## Setting up the Environment
In order to set up the environment, you'll need to:

Review the code in the crypto_wallet.py script file. This file contains Ethereum transaction functions that have been incorporated into Python functions for easy automation. Then Add your mnemonic seed phrase (provided by Ganache) to the SAMPLE.env file and rename it to .env. Then Import the following functions from the crypto_wallet.py file: generate_account, get_balance, and send_transaction.

## Contributors
I am the main contributor for this code.
