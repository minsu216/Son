# 새싹 시각화 프로젝트
sofifa Site에서 시각화 분석 프로젝트
## 프로젝트 소개
동아시아 국가 기준으로 fifa 카드 스탯을 통해
시각화 분석 프로젝트
## 개발 기간
- 2023.09. ~ 2023.10

## 개발환경
<img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">

<img src="https://img.shields.io/badge/pandas-3776AB?style=for-the-badge&logo=pandas&logoColor=red">


## 주요 기능


```python
from selenium import webdriver
from bs4 import BeautifulSoup
import pandas as pd
import re
import pandas as pd
import numpy as np
import folium
import plotly.express as px
from folium.plugins import HeatMap
import matplotlib.pyplot as plt
from PIL import Image
from wordcloud import WordCloud
from plotly.subplots import make_subplots
import plotly.graph_objects as go
```


## 시작 가이드

<span style="font-size:120%">요구사항</span> 
- folium 0.14.0
- numpy 1.24.3
- pandas 1.5.3
- plotly 5.9.0
- bs4 4.12.2
- webdriver 4.12.0
- word_cloud 1.9.2
- Image 9.4.0