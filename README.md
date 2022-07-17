# Stock Pile Peer

Stock Pile Peer is a simple flask application that uses Machine Learning to predict the stock price of a given company


![Screenshot 2022-07-17 193249](https://user-images.githubusercontent.com/52581527/179405623-86b59131-342d-4a83-b961-6c929587e4f9.jpg)![Screenshot 2022-07-17 193451](https://user-images.githubusercontent.com/52581527/179405630-007039dd-f21f-4569-8322-f9efb3d43127.jpg)

![Screenshot 2022-07-17 193408](https://user-images.githubusercontent.com/52581527/179405625-909a09b9-bf91-464e-8d87-21cc699f1bd3.jpg)

## Installation & Usage in local Machine

1. Download the repository in your local machine.
2. Check your system for the following libraries:
```python
#Libraries
from flask import Flask,render_template,request
import math
from datetime import date
import datetime
import pandas_datareader as web
import numpy as np
import pandas as pd
from sklearn.preprocessing import MinMaxScaler
from keras.models import Sequential
from keras.layers import Dense, LSTM
import matplotlib.pyplot as plt
import re
plt.style.use('fivethirtyeight') 
```
3. After successful installation of all the necessary libraries, open terminal in the app directory and run the following command:
```python
$python3 app.py
```
4. You'll receive a similar output:
```
/usr/local/lib/python3.8/dist-packages/pandas_datareader/compat/__init__.py:7: 
FutureWarning: pandas.util.testing is deprecated. Use the functions in the public API at pandas.testing instead.
  from pandas.util.testing import assert_frame_equal
 * Serving Flask app "app" (lazy loading)
 * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
 * Debug mode: off
 * Running on http://127.0.0.1:5000/

```
5. Open your preferred browser and past the link [http://127.0.0.1:5000/](http://127.0.0.1:5000/)



