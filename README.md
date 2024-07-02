# q1
code for question one
!pip install yfinance==0.1.70
!mamba install bs4==4.10.0 -y
!pip install nbformat==4.2.0

import yfinance as yf
import pandas as pd
import requests
from bs4 import BeautifulSoup
import plotly.graph_objects as go
from plotly.subplots import make_subplots

import Warnings
warnings.filterwarnings("ignore", Category=FutureWarning)

TSLA = yf.ticker['TSLA']
