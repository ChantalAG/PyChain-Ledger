# PyChain-Ledger
## Blockchain Homework Assignment
![image](https://user-images.githubusercontent.com/99493522/176976713-e48173f6-63be-42d7-b310-08b0e6ed4df4.png)

## Background
In this assignment, working as a fintech engineer at one of the five largest banks in the world. The task was to build a blockchain-based ledger system, complete with a user-friendly web interface. This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.
The following updates were made to the provided [Python file](https://github.com/ChantalAG/PyChain-Ledger/blob/main/pychain.py) for this assignment, which already contains the basic PyChain ledger structure that was created throughout the module:


1. Create a new data class named Record. This class will serve as the blueprint for the financial transaction records that the blocks of the ledger will store.


2. Modify the existing Block data class to store Record data.


3. Add Relevant User Inputs to the Streamlit interface.


4. Test the PyChain Ledger by Storing Records.


## Imports Required

    import streamlit as st
    from dataclasses import dataclass
    from typing import Any, List
    import datetime as datetime
    import pandas as pd
    import hashlib

## Testing the PyChain Ledger


Verify the block contents and hashes in the Streamlit dropdown menu. Take a screenshot of the Streamlit application page, which should detail a blockchain that consists of multiple blocks. 

Test the blockchain validation process by using the web interface. Take a screenshot of the Streamlit application page, which should indicate the validity of the blockchain.
![image](https://user-images.githubusercontent.com/99493522/176977446-2e8409cf-ce82-4636-be00-0e24e708a339.png)

## Contributors
Chantal Garnett
