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

## 4 Code 

### 4.1 Create a Record Data Class
![image](https://user-images.githubusercontent.com/101449950/179438505-cb528708-78b4-479a-a259-d287381ab396.png)

### 4.2 Modify the Existing Block Data Class to Store Record Data
![image](https://user-images.githubusercontent.com/101449950/179438383-048e9963-fabc-409c-b33e-6a2ee163e3dd.png)

### 4.3 Add Relevant User Inputs to the Streamlit Interface
![image](https://user-images.githubusercontent.com/101449950/179438455-d5d6c883-0cdc-4e5c-9f91-745dba7845e5.png)


## Testing with StreamLit

Picture 1:  See the ledger with a few transactions
<img width="1512" alt="Screen Shot 2022-07-17 at 9 32 20 PM" src="https://user-images.githubusercontent.com/101449950/179440059-8ffa5ebf-c902-4afe-84be-c3dc7d424ad7.png">

Picture 2: See the side bar
<img width="1512" alt="Screen Shot 2022-07-17 at 9 32 48 PM" src="https://user-images.githubusercontent.com/101449950/179440010-8d3ad82a-df05-492e-b93b-8f60ab10b47e.png">

Picture 3: BlockChain Validated
<img width="1512" alt="Screen Shot 2022-07-17 at 11 15 19 PM" src="https://user-images.githubusercontent.com/101449950/179440406-0f70fcfb-9272-4754-afc4-f502dc192c1d.png">

picture 4: Perspective from Command line
<img width="615" alt="Screen Shot 2022-07-17 at 11 26 20 PM" src="https://user-images.githubusercontent.com/101449950/179441190-9ea61e33-e4eb-4404-94b7-ec0343944d5c.png">

