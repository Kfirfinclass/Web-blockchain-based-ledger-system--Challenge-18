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

Enter details into the Sender ID, Receiver ID, Amount and click the 'Add Block' button. This will add a block to the ledger. This can be validated in two ways: the new block will appear as a new row in the PyChain ledger dataframe and secondly, will appear under the Block Inspector dropdown.

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
