# **Challenge18_Blockchain-based_Ledger**
![18-4-application-image](https://user-images.githubusercontent.com/101449950/179434997-f508a94b-39bd-49e7-85ed-6a796151993b.png)


## 1. INTRO 
The Business ask for this particular task is to build a blockchain-based ledger system, complete with a user-friendly web interface. This ledger should allow partner banks to transfer money between senders and receivers and to verify the integrity of the data in the ledger.


## 2. To - Do list

Update the `pychain.py` file. It already has the functionality to create blocks, perform the proof of work consensus protocol, and validate blocks in the chain. The steps for this Challenge are divided into the following sections:

1. Create a Record Data Class
2. Modify the Existing Block Data Class to Store Record Data
3. Add Relevant User Inputs to the Streamlit Interface
4. Test the PyChain Ledger by Storing Records

## 3. Prerequisites

### 3.1 Requirements Text File

I created a requirements file that has been included in this repo.
I used the following to create the requirements file

```bash
 pip freeze > requirements_CH18.txt

```

pip install for Requirements Text Files
```bash
python -m pip install -r requirements_10.txt
```

### 3.2 Libraries and Imports


```python
# Imports
import streamlit as st
from dataclasses import dataclass
from typing import Any, List
import datetime as datetime
import pandas as pd
import hashlib
```

### Documentation Links (Streamlit, Hashlib, Dataclasses)
1. https://docs.streamlit.io/
2. https://docs.python.org/3/library/hashlib.html
3. https://docs.python.org/3/library/dataclasses.html
