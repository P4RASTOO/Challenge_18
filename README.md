<img width="597" alt="Screenshot 2023-09-18 at 4 56 26 PM" src="https://github.com/P4RASTOO/Challenge_18/assets/132952512/58099917-14c2-4a47-b319-9ec1c40b267d">

# Challenge_18 Report
## Overview of the Analysis:

The analysis involves the creation and testing of a blockchain ledger called "PyChain" using Python. This ledger is designed to store financial transaction records. The primary goal is to implement the following key steps:

1) Create a Record Data Class: Develop a data class called Record that defines the structure for financial transaction records, including sender, receiver, and amount.
2) Modify Block Data Class: Modify the existing Block data class to replace the generic data attribute with a record attribute of type Record. This update enables the storage of financial transaction data in the blockchain.
3) Streamlit Interface: Create a user-friendly Streamlit web application to interact with the blockchain. The interface allows users to input sender, receiver, and amount values for financial transactions.
4) Test the PyChain Ledger: Test the PyChain ledger by storing multiple blocks in the blockchain. Users can input transaction details through the web interface and visualize the blockchain's structure. Additionally, there is a validation feature to check the blockchain's integrity.

## Stages of the Process:
### Data Class Creation:
The first stage involves defining the Record data class with attributes for sender, receiver, and amount.
### Block Modification:
In this stage, the Block data class is modified to accommodate the Record data type, allowing it to store financial transaction data.
### Streamlit Interface Development:
The Streamlit web application is developed, providing an interactive interface for users to input financial transaction details.
### Blockchain Testing:
Users can test the PyChain ledger by entering transaction data through the web interface and adding multiple blocks to the blockchain.
### Validation:
Blockchain validation is performed to ensure the integrity of the ledger.

## Methods Used:
The analysis employs the following methods and technologies:

* Blockchain Principles: The analysis follows basic blockchain principles, including hashing with hashlib, proof-of-work for block mining, and chain validation.
* Data Classes: Python data classes are utilized to define the structure of financial transaction records and blocks.
* Streamlit: The Streamlit library is used to develop the web interface, making it easy for users to interact with the blockchain.

## Summary:
The analysis demonstrates the creation of a simple blockchain ledger called "PyChain" that can store financial transaction records. It leverages Python's data classes and hashlib for hashing. The integration with Streamlit allows users to input transaction details and visualize the blockchain's structure. Additionally, there is a validation mechanism to ensure the blockchain's integrity.

## Recommendation:
This analysis serves as a foundational example of blockchain development and interaction through a user-friendly interface. We can extend the analysis further by integrating real financial data sources or APIs to simulate real-world financial transactions. We can as well, implement more advanced security features, such as cryptographic signatures and private keys, to improve the security of financial transactions.
<img width="617" alt="Screenshot 2023-09-21 at 1 34 48 AM" src="https://github.com/P4RASTOO/Challenge_18/assets/132952512/951be21d-ebad-4846-83f2-f0c06800fcfa">



