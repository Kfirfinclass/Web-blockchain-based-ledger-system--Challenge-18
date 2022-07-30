# Challenge 18

This Challenge showed a simple to use, web app for a blockchain-based ledger system. This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.

---

## Installation Guide

run pip install -r requirements.txt

---

## Technologies

import streamlit as st
from dataclasses import dataclass
from typing import Any, List
import datetime as datetime
import pandas as pd
import hashlib

---

## Usage

Run the following command: streamlit run pychain.py

The Streamlit application will run locally in your browser and should launch automatically.
<img width="947" alt="Screenshot 2022-07-28 170755" src="https://user-images.githubusercontent.com/98926901/181934745-19be9473-bea3-4519-8bf1-876b52660a89.png">

Enter details into the Sender ID, Receiver ID, Amount and click the 'Add Block' button. This will add a block to the ledger. This can be validated in two ways: the new block will appear as a new row in the PyChain ledger dataframe and secondly, will appear under the Block Inspector dropdown.
<img width="839" alt="Screenshot 2022-07-28 180203" src="https://user-images.githubusercontent.com/98926901/181934749-21aeb423-0608-43d0-b6d7-b84e3c5b87a4.png">

---

## Validationn

Once additional blocks have been addeed to the chain, clicking the 'Validate Chain' button will produce a True statement indicating the validity of the entire ledger.

---

## Contributors

Kfir Bar
kfirfinclass@gmail.com

---

## License

This code is exclusive to those who are provided a direct access. A user-key feature can be added later.
#Challenge-18
