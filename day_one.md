```python
!pip install pandas numpy
import pandas as pd
import numpy as np
```

    Collecting pandas
      Downloading pandas-2.2.2-cp312-cp312-win_amd64.whl.metadata (19 kB)
    Collecting numpy
      Downloading numpy-1.26.4-cp312-cp312-win_amd64.whl.metadata (61 kB)
         ---------------------------------------- 0.0/61.0 kB ? eta -:--:--
         --------------------------------- ------ 51.2/61.0 kB 2.6 MB/s eta 0:00:01
         ---------------------------------------- 61.0/61.0 kB 1.6 MB/s eta 0:00:00
    Requirement already satisfied: python-dateutil>=2.8.2 in c:\users\felhasználó\appdata\local\programs\python\python312\lib\site-packages (from pandas) (2.9.0.post0)
    Collecting pytz>=2020.1 (from pandas)
      Downloading pytz-2024.1-py2.py3-none-any.whl.metadata (22 kB)
    Collecting tzdata>=2022.7 (from pandas)
      Downloading tzdata-2024.1-py2.py3-none-any.whl.metadata (1.4 kB)
    Requirement already satisfied: six>=1.5 in c:\users\felhasználó\appdata\local\programs\python\python312\lib\site-packages (from python-dateutil>=2.8.2->pandas) (1.16.0)
    Downloading pandas-2.2.2-cp312-cp312-win_amd64.whl (11.5 MB)
       ---------------------------------------- 0.0/11.5 MB ? eta -:--:--
        --------------------------------------- 0.2/11.5 MB 5.9 MB/s eta 0:00:02
       - -------------------------------------- 0.4/11.5 MB 5.5 MB/s eta 0:00:03
       -- ------------------------------------- 0.7/11.5 MB 5.4 MB/s eta 0:00:02
       -- ------------------------------------- 0.9/11.5 MB 5.0 MB/s eta 0:00:03
       ---- ----------------------------------- 1.2/11.5 MB 5.4 MB/s eta 0:00:02
       ---- ----------------------------------- 1.4/11.5 MB 5.5 MB/s eta 0:00:02
       ----- ---------------------------------- 1.7/11.5 MB 5.4 MB/s eta 0:00:02
       ------ --------------------------------- 2.0/11.5 MB 5.7 MB/s eta 0:00:02
       ------- -------------------------------- 2.3/11.5 MB 5.5 MB/s eta 0:00:02
       -------- ------------------------------- 2.5/11.5 MB 5.8 MB/s eta 0:00:02
       --------- ------------------------------ 2.8/11.5 MB 5.6 MB/s eta 0:00:02
       ---------- ----------------------------- 3.0/11.5 MB 5.6 MB/s eta 0:00:02
       ----------- ---------------------------- 3.3/11.5 MB 5.5 MB/s eta 0:00:02
       ------------ --------------------------- 3.6/11.5 MB 5.7 MB/s eta 0:00:02
       ------------- -------------------------- 3.8/11.5 MB 5.6 MB/s eta 0:00:02
       -------------- ------------------------- 4.1/11.5 MB 5.6 MB/s eta 0:00:02
       -------------- ------------------------- 4.3/11.5 MB 5.6 MB/s eta 0:00:02
       --------------- ------------------------ 4.6/11.5 MB 5.6 MB/s eta 0:00:02
       ---------------- ----------------------- 4.9/11.5 MB 5.7 MB/s eta 0:00:02
       ----------------- ---------------------- 5.2/11.5 MB 5.7 MB/s eta 0:00:02
       ------------------ --------------------- 5.4/11.5 MB 5.6 MB/s eta 0:00:02
       ------------------- -------------------- 5.6/11.5 MB 5.5 MB/s eta 0:00:02
       ------------------- -------------------- 5.7/11.5 MB 5.6 MB/s eta 0:00:02
       -------------------- ------------------- 5.8/11.5 MB 5.4 MB/s eta 0:00:02
       --------------------- ------------------ 6.1/11.5 MB 5.5 MB/s eta 0:00:01
       --------------------- ------------------ 6.2/11.5 MB 5.3 MB/s eta 0:00:01
       ---------------------- ----------------- 6.4/11.5 MB 5.3 MB/s eta 0:00:01
       ----------------------- ---------------- 6.7/11.5 MB 5.4 MB/s eta 0:00:01
       ------------------------ --------------- 7.0/11.5 MB 5.4 MB/s eta 0:00:01
       ------------------------- -------------- 7.3/11.5 MB 5.4 MB/s eta 0:00:01
       -------------------------- ------------- 7.5/11.5 MB 5.4 MB/s eta 0:00:01
       --------------------------- ------------ 7.8/11.5 MB 5.5 MB/s eta 0:00:01
       ---------------------------- ----------- 8.1/11.5 MB 5.4 MB/s eta 0:00:01
       ---------------------------- ----------- 8.3/11.5 MB 5.5 MB/s eta 0:00:01
       ----------------------------- ---------- 8.6/11.5 MB 5.5 MB/s eta 0:00:01
       ------------------------------ --------- 8.8/11.5 MB 5.5 MB/s eta 0:00:01
       ------------------------------- -------- 9.1/11.5 MB 5.5 MB/s eta 0:00:01
       -------------------------------- ------- 9.3/11.5 MB 5.5 MB/s eta 0:00:01
       --------------------------------- ------ 9.6/11.5 MB 5.5 MB/s eta 0:00:01
       ---------------------------------- ----- 9.8/11.5 MB 5.5 MB/s eta 0:00:01
       ----------------------------------- ---- 10.1/11.5 MB 5.5 MB/s eta 0:00:01
       ----------------------------------- ---- 10.3/11.5 MB 5.5 MB/s eta 0:00:01
       ------------------------------------ --- 10.5/11.5 MB 5.5 MB/s eta 0:00:01
       ------------------------------------- -- 10.8/11.5 MB 5.5 MB/s eta 0:00:01
       -------------------------------------- - 11.0/11.5 MB 5.5 MB/s eta 0:00:01
       ---------------------------------------  11.3/11.5 MB 5.6 MB/s eta 0:00:01
       ---------------------------------------  11.5/11.5 MB 5.5 MB/s eta 0:00:01
       ---------------------------------------- 11.5/11.5 MB 5.5 MB/s eta 0:00:00
    Downloading numpy-1.26.4-cp312-cp312-win_amd64.whl (15.5 MB)
       ---------------------------------------- 0.0/15.5 MB ? eta -:--:--
        --------------------------------------- 0.3/15.5 MB 5.9 MB/s eta 0:00:03
       - -------------------------------------- 0.6/15.5 MB 5.8 MB/s eta 0:00:03
       - -------------------------------------- 0.8/15.5 MB 6.1 MB/s eta 0:00:03
       -- ------------------------------------- 1.0/15.5 MB 5.7 MB/s eta 0:00:03
       --- ------------------------------------ 1.3/15.5 MB 5.8 MB/s eta 0:00:03
       --- ------------------------------------ 1.5/15.5 MB 5.6 MB/s eta 0:00:03
       ---- ----------------------------------- 1.8/15.5 MB 5.7 MB/s eta 0:00:03
       ----- ---------------------------------- 2.0/15.5 MB 5.6 MB/s eta 0:00:03
       ----- ---------------------------------- 2.3/15.5 MB 5.6 MB/s eta 0:00:03
       ------ --------------------------------- 2.6/15.5 MB 5.7 MB/s eta 0:00:03
       ------- -------------------------------- 2.8/15.5 MB 5.7 MB/s eta 0:00:03
       ------- -------------------------------- 3.1/15.5 MB 5.6 MB/s eta 0:00:03
       -------- ------------------------------- 3.3/15.5 MB 5.6 MB/s eta 0:00:03
       --------- ------------------------------ 3.6/15.5 MB 5.7 MB/s eta 0:00:03
       --------- ------------------------------ 3.8/15.5 MB 5.5 MB/s eta 0:00:03
       ---------- ----------------------------- 4.1/15.5 MB 5.5 MB/s eta 0:00:03
       ----------- ---------------------------- 4.4/15.5 MB 5.6 MB/s eta 0:00:02
       ------------ --------------------------- 4.7/15.5 MB 5.6 MB/s eta 0:00:02
       ------------ --------------------------- 4.9/15.5 MB 5.6 MB/s eta 0:00:02
       ------------- -------------------------- 5.2/15.5 MB 5.6 MB/s eta 0:00:02
       -------------- ------------------------- 5.5/15.5 MB 5.6 MB/s eta 0:00:02
       -------------- ------------------------- 5.7/15.5 MB 5.6 MB/s eta 0:00:02
       --------------- ------------------------ 6.0/15.5 MB 5.7 MB/s eta 0:00:02
       ---------------- ----------------------- 6.3/15.5 MB 5.7 MB/s eta 0:00:02
       ---------------- ----------------------- 6.6/15.5 MB 5.7 MB/s eta 0:00:02
       ----------------- ---------------------- 6.8/15.5 MB 5.6 MB/s eta 0:00:02
       ------------------ --------------------- 7.1/15.5 MB 5.6 MB/s eta 0:00:02
       ------------------ --------------------- 7.3/15.5 MB 5.6 MB/s eta 0:00:02
       ------------------- -------------------- 7.6/15.5 MB 5.6 MB/s eta 0:00:02
       -------------------- ------------------- 7.9/15.5 MB 5.7 MB/s eta 0:00:02
       --------------------- ------------------ 8.2/15.5 MB 5.7 MB/s eta 0:00:02
       --------------------- ------------------ 8.4/15.5 MB 5.7 MB/s eta 0:00:02
       ---------------------- ----------------- 8.7/15.5 MB 5.7 MB/s eta 0:00:02
       ----------------------- ---------------- 9.0/15.5 MB 5.7 MB/s eta 0:00:02
       ----------------------- ---------------- 9.2/15.5 MB 5.7 MB/s eta 0:00:02
       ------------------------ --------------- 9.5/15.5 MB 5.7 MB/s eta 0:00:02
       ------------------------- -------------- 9.8/15.5 MB 5.7 MB/s eta 0:00:02
       ------------------------- -------------- 10.0/15.5 MB 5.7 MB/s eta 0:00:01
       -------------------------- ------------- 10.3/15.5 MB 5.6 MB/s eta 0:00:01
       --------------------------- ------------ 10.5/15.5 MB 5.6 MB/s eta 0:00:01
       --------------------------- ------------ 10.8/15.5 MB 5.6 MB/s eta 0:00:01
       ---------------------------- ----------- 11.0/15.5 MB 5.6 MB/s eta 0:00:01
       ---------------------------- ----------- 11.2/15.5 MB 5.6 MB/s eta 0:00:01
       ---------------------------- ----------- 11.2/15.5 MB 5.6 MB/s eta 0:00:01
       ---------------------------- ----------- 11.2/15.5 MB 5.6 MB/s eta 0:00:01
       ---------------------------- ----------- 11.2/15.5 MB 5.6 MB/s eta 0:00:01
       ---------------------------- ----------- 11.2/15.5 MB 5.6 MB/s eta 0:00:01
       ---------------------------- ----------- 11.2/15.5 MB 5.6 MB/s eta 0:00:01
       ---------------------------- ----------- 11.2/15.5 MB 5.6 MB/s eta 0:00:01
       ---------------------------- ----------- 11.2/15.5 MB 5.6 MB/s eta 0:00:01
       ---------------------------------- ----- 13.3/15.5 MB 5.6 MB/s eta 0:00:01
       ----------------------------------- ---- 13.6/15.5 MB 5.6 MB/s eta 0:00:01
       ----------------------------------- ---- 13.9/15.5 MB 5.7 MB/s eta 0:00:01
       ------------------------------------ --- 14.1/15.5 MB 5.7 MB/s eta 0:00:01
       ------------------------------------ --- 14.3/15.5 MB 5.6 MB/s eta 0:00:01
       ------------------------------------- -- 14.6/15.5 MB 5.7 MB/s eta 0:00:01
       -------------------------------------- - 14.8/15.5 MB 5.7 MB/s eta 0:00:01
       -------------------------------------- - 15.1/15.5 MB 5.7 MB/s eta 0:00:01
       ---------------------------------------  15.3/15.5 MB 5.7 MB/s eta 0:00:01
       ---------------------------------------  15.5/15.5 MB 5.6 MB/s eta 0:00:01
       ---------------------------------------- 15.5/15.5 MB 5.5 MB/s eta 0:00:00
    Downloading pytz-2024.1-py2.py3-none-any.whl (505 kB)
       ---------------------------------------- 0.0/505.5 kB ? eta -:--:--
       ------------------ --------------------- 235.5/505.5 kB 7.3 MB/s eta 0:00:01
       ---------------------------------------- 505.5/505.5 kB 6.3 MB/s eta 0:00:00
    Downloading tzdata-2024.1-py2.py3-none-any.whl (345 kB)
       ---------------------------------------- 0.0/345.4 kB ? eta -:--:--
       ---------------------- ----------------- 194.6/345.4 kB 5.8 MB/s eta 0:00:01
       ---------------------------------------  337.9/345.4 kB 5.2 MB/s eta 0:00:01
       ---------------------------------------  337.9/345.4 kB 5.2 MB/s eta 0:00:01
       ---------------------------------------  337.9/345.4 kB 5.2 MB/s eta 0:00:01
       ---------------------------------------- 345.4/345.4 kB 1.8 MB/s eta 0:00:00
    Installing collected packages: pytz, tzdata, numpy, pandas
    Successfully installed numpy-1.26.4 pandas-2.2.2 pytz-2024.1 tzdata-2024.1
    


```python
nfl_data = pd.read_csv ("C:/Users/Felhasználó/Desktop/python cpurse/1.nap/NFL Play by Play 2009-2017 (v4).csv")
```

    C:\Users\Felhasználó\AppData\Local\Temp\ipykernel_13732\1700912395.py:1: DtypeWarning: Columns (25,51) have mixed types. Specify dtype option on import or set low_memory=False.
      nfl_data = pd.read_csv ("C:/Users/Felhasználó/Desktop/python cpurse/1.nap/NFL Play by Play 2009-2017 (v4).csv")
    


```python
sf_permits = pd.read_csv ("C:/Users/Felhasználó/Desktop/python cpurse/1.nap/NFL Play by Play 2009-2016 (v3).csv")
```

    C:\Users\Felhasználó\AppData\Local\Temp\ipykernel_13732\3530080528.py:1: DtypeWarning: Columns (25,51) have mixed types. Specify dtype option on import or set low_memory=False.
      sf_permits = pd.read_csv ("C:/Users/Felhasználó/Desktop/python cpurse/1.nap/NFL Play by Play 2009-2016 (v3).csv")
    


```python
np.random.seed(0)
```


```python
#check the first 5 line
nfl_data.sample(5)
#there are some missing, which we have to deal with it
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Date</th>
      <th>GameID</th>
      <th>Drive</th>
      <th>qtr</th>
      <th>down</th>
      <th>time</th>
      <th>TimeUnder</th>
      <th>TimeSecs</th>
      <th>PlayTimeDiff</th>
      <th>SideofField</th>
      <th>...</th>
      <th>yacEPA</th>
      <th>Home_WP_pre</th>
      <th>Away_WP_pre</th>
      <th>Home_WP_post</th>
      <th>Away_WP_post</th>
      <th>Win_Prob</th>
      <th>WPA</th>
      <th>airWPA</th>
      <th>yacWPA</th>
      <th>Season</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>244485</th>
      <td>2014-10-26</td>
      <td>2014102607</td>
      <td>18</td>
      <td>3</td>
      <td>1.0</td>
      <td>00:39</td>
      <td>1</td>
      <td>939.0</td>
      <td>12.0</td>
      <td>TB</td>
      <td>...</td>
      <td>1.240299</td>
      <td>0.225647</td>
      <td>0.774353</td>
      <td>0.245582</td>
      <td>0.754418</td>
      <td>0.225647</td>
      <td>0.019935</td>
      <td>-0.018156</td>
      <td>0.038091</td>
      <td>2014</td>
    </tr>
    <tr>
      <th>115340</th>
      <td>2011-11-20</td>
      <td>2011112000</td>
      <td>22</td>
      <td>4</td>
      <td>1.0</td>
      <td>06:47</td>
      <td>7</td>
      <td>407.0</td>
      <td>44.0</td>
      <td>OAK</td>
      <td>...</td>
      <td>NaN</td>
      <td>0.056036</td>
      <td>0.943964</td>
      <td>0.042963</td>
      <td>0.957037</td>
      <td>0.943964</td>
      <td>0.013073</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2011</td>
    </tr>
    <tr>
      <th>68357</th>
      <td>2010-11-14</td>
      <td>2010111401</td>
      <td>8</td>
      <td>2</td>
      <td>NaN</td>
      <td>00:23</td>
      <td>1</td>
      <td>1823.0</td>
      <td>0.0</td>
      <td>CLE</td>
      <td>...</td>
      <td>NaN</td>
      <td>0.365307</td>
      <td>0.634693</td>
      <td>0.384697</td>
      <td>0.615303</td>
      <td>0.634693</td>
      <td>-0.019390</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2010</td>
    </tr>
    <tr>
      <th>368377</th>
      <td>2017-09-24</td>
      <td>2017092405</td>
      <td>24</td>
      <td>4</td>
      <td>1.0</td>
      <td>08:48</td>
      <td>9</td>
      <td>528.0</td>
      <td>8.0</td>
      <td>CLE</td>
      <td>...</td>
      <td>1.075660</td>
      <td>0.935995</td>
      <td>0.064005</td>
      <td>0.921231</td>
      <td>0.078769</td>
      <td>0.064005</td>
      <td>0.014764</td>
      <td>0.003866</td>
      <td>0.010899</td>
      <td>2017</td>
    </tr>
    <tr>
      <th>384684</th>
      <td>2017-11-05</td>
      <td>2017110505</td>
      <td>11</td>
      <td>2</td>
      <td>1.0</td>
      <td>09:15</td>
      <td>10</td>
      <td>2355.0</td>
      <td>0.0</td>
      <td>DEN</td>
      <td>...</td>
      <td>NaN</td>
      <td>0.928474</td>
      <td>0.071526</td>
      <td>0.934641</td>
      <td>0.065359</td>
      <td>0.071526</td>
      <td>-0.006166</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2017</td>
    </tr>
  </tbody>
</table>
<p>5 rows × 102 columns</p>
</div>




```python
#check te sf_permits datatable
sf_permits.sample(5)
#there are some missing
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Date</th>
      <th>GameID</th>
      <th>Drive</th>
      <th>qtr</th>
      <th>down</th>
      <th>time</th>
      <th>TimeUnder</th>
      <th>TimeSecs</th>
      <th>PlayTimeDiff</th>
      <th>SideofField</th>
      <th>...</th>
      <th>yacEPA</th>
      <th>Home_WP_pre</th>
      <th>Away_WP_pre</th>
      <th>Home_WP_post</th>
      <th>Away_WP_post</th>
      <th>Win_Prob</th>
      <th>WPA</th>
      <th>airWPA</th>
      <th>yacWPA</th>
      <th>Season</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>207855</th>
      <td>2013-11-17</td>
      <td>2013111712</td>
      <td>5</td>
      <td>1</td>
      <td>4.0</td>
      <td>01:05</td>
      <td>2</td>
      <td>2765.0</td>
      <td>30.0</td>
      <td>GB</td>
      <td>...</td>
      <td>NaN</td>
      <td>0.763613</td>
      <td>0.236387</td>
      <td>0.820702</td>
      <td>0.179298</td>
      <td>0.763613</td>
      <td>0.057089</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2013</td>
    </tr>
    <tr>
      <th>29298</th>
      <td>2009-11-29</td>
      <td>2009112905</td>
      <td>1</td>
      <td>1</td>
      <td>2.0</td>
      <td>11:07</td>
      <td>12</td>
      <td>3367.0</td>
      <td>4.0</td>
      <td>CAR</td>
      <td>...</td>
      <td>NaN</td>
      <td>0.456538</td>
      <td>0.543462</td>
      <td>0.470056</td>
      <td>0.529944</td>
      <td>0.543462</td>
      <td>-0.013518</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2009</td>
    </tr>
    <tr>
      <th>209054</th>
      <td>2013-11-24</td>
      <td>2013112403</td>
      <td>7</td>
      <td>2</td>
      <td>1.0</td>
      <td>09:33</td>
      <td>10</td>
      <td>2373.0</td>
      <td>10.0</td>
      <td>GB</td>
      <td>...</td>
      <td>0.001191</td>
      <td>0.702025</td>
      <td>0.297975</td>
      <td>0.682140</td>
      <td>0.317860</td>
      <td>0.702025</td>
      <td>-0.019885</td>
      <td>-0.01978</td>
      <td>-0.000105</td>
      <td>2013</td>
    </tr>
    <tr>
      <th>223200</th>
      <td>2013-12-29</td>
      <td>2013122904</td>
      <td>21</td>
      <td>4</td>
      <td>2.0</td>
      <td>02:20</td>
      <td>3</td>
      <td>140.0</td>
      <td>39.0</td>
      <td>IND</td>
      <td>...</td>
      <td>NaN</td>
      <td>0.999863</td>
      <td>0.000137</td>
      <td>0.999848</td>
      <td>0.000152</td>
      <td>0.999863</td>
      <td>-0.000015</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2013</td>
    </tr>
    <tr>
      <th>20213</th>
      <td>2009-11-08</td>
      <td>2009110800</td>
      <td>9</td>
      <td>2</td>
      <td>NaN</td>
      <td>03:36</td>
      <td>4</td>
      <td>2016.0</td>
      <td>0.0</td>
      <td>ATL</td>
      <td>...</td>
      <td>NaN</td>
      <td>0.919261</td>
      <td>0.080739</td>
      <td>0.913313</td>
      <td>0.086687</td>
      <td>0.080739</td>
      <td>0.005947</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2009</td>
    </tr>
  </tbody>
</table>
<p>5 rows × 102 columns</p>
</div>




```python
#check the number of missings nfl_data
missing_values_count = nfl_data.isnull().sum() #count it
missing_values_count [0:10]
#you can see, how many missings are in one column
```




    Date                0
    GameID              0
    Drive               0
    qtr                 0
    down            61154
    time              224
    TimeUnder           0
    TimeSecs          224
    PlayTimeDiff      444
    SideofField       528
    dtype: int64




```python
#it would be helpful, to check that how many percentages the missing values
total_cells = np.product (nfl_data.shape)
total_missing = missing_values_count.sum()

(total_missing/total_cells) * 100
```




    27.66722370547874




```python
#check the number of missing sf_permit
missing_values_count = sf_permits.isnull().sum()
missing_values_count [0:10]
```




    Date                0
    GameID              0
    Drive               0
    qtr                 0
    down            54218
    time              188
    TimeUnder           0
    TimeSecs          188
    PlayTimeDiff      374
    SideofField       450
    dtype: int64




```python
#check the percentages of sf_permits
total_cells = np.product (sf_permits.shape)
total_missing = missing_values_count.sum()

(total_missing / total_cells)*100
```




    27.652267428200588




```python
#remove the missing values nfl_data
nfl_data.dropna()
#unfortunately it dropeed all the rows, because every line has one missing values
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Date</th>
      <th>GameID</th>
      <th>Drive</th>
      <th>qtr</th>
      <th>down</th>
      <th>time</th>
      <th>TimeUnder</th>
      <th>TimeSecs</th>
      <th>PlayTimeDiff</th>
      <th>SideofField</th>
      <th>...</th>
      <th>yacEPA</th>
      <th>Home_WP_pre</th>
      <th>Away_WP_pre</th>
      <th>Home_WP_post</th>
      <th>Away_WP_post</th>
      <th>Win_Prob</th>
      <th>WPA</th>
      <th>airWPA</th>
      <th>yacWPA</th>
      <th>Season</th>
    </tr>
  </thead>
  <tbody>
  </tbody>
</table>
<p>0 rows × 102 columns</p>
</div>




```python
columns_with_na_dropped = nfl_data.dropna(axis=1)
columns_with_na_dropped.head()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Date</th>
      <th>GameID</th>
      <th>Drive</th>
      <th>qtr</th>
      <th>TimeUnder</th>
      <th>ydstogo</th>
      <th>ydsnet</th>
      <th>PlayAttempted</th>
      <th>Yards.Gained</th>
      <th>sp</th>
      <th>...</th>
      <th>AwayTeam</th>
      <th>Timeout_Indicator</th>
      <th>posteam_timeouts_pre</th>
      <th>HomeTimeouts_Remaining_Pre</th>
      <th>AwayTimeouts_Remaining_Pre</th>
      <th>HomeTimeouts_Remaining_Post</th>
      <th>AwayTimeouts_Remaining_Post</th>
      <th>ExPoint_Prob</th>
      <th>TwoPoint_Prob</th>
      <th>Season</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>2009-09-10</td>
      <td>2009091000</td>
      <td>1</td>
      <td>1</td>
      <td>15</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>39</td>
      <td>0</td>
      <td>...</td>
      <td>TEN</td>
      <td>0</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2009</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2009-09-10</td>
      <td>2009091000</td>
      <td>1</td>
      <td>1</td>
      <td>15</td>
      <td>10</td>
      <td>5</td>
      <td>1</td>
      <td>5</td>
      <td>0</td>
      <td>...</td>
      <td>TEN</td>
      <td>0</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2009</td>
    </tr>
    <tr>
      <th>2</th>
      <td>2009-09-10</td>
      <td>2009091000</td>
      <td>1</td>
      <td>1</td>
      <td>15</td>
      <td>5</td>
      <td>2</td>
      <td>1</td>
      <td>-3</td>
      <td>0</td>
      <td>...</td>
      <td>TEN</td>
      <td>0</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2009</td>
    </tr>
    <tr>
      <th>3</th>
      <td>2009-09-10</td>
      <td>2009091000</td>
      <td>1</td>
      <td>1</td>
      <td>14</td>
      <td>8</td>
      <td>2</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>TEN</td>
      <td>0</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2009</td>
    </tr>
    <tr>
      <th>4</th>
      <td>2009-09-10</td>
      <td>2009091000</td>
      <td>1</td>
      <td>1</td>
      <td>14</td>
      <td>8</td>
      <td>2</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>TEN</td>
      <td>0</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2009</td>
    </tr>
  </tbody>
</table>
<p>5 rows × 37 columns</p>
</div>




```python
#check how much data did we lost
print("columns in original dataset: %d \n" % nfl_data.shape[1])
print("column swith na's dropped: %d" % columns_with_na_dropped.shape[1])
```

    columns in original dataset: 102 
    
    column swith na's dropped: 37
    


```python
#remove the missing values sf_permits
sf_permits.dropna()
columns_with_na_dropped = sf_permits.dropna(axis=1)
columns_with_na_dropped.head()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Date</th>
      <th>GameID</th>
      <th>Drive</th>
      <th>qtr</th>
      <th>TimeUnder</th>
      <th>ydstogo</th>
      <th>ydsnet</th>
      <th>PlayAttempted</th>
      <th>Yards.Gained</th>
      <th>sp</th>
      <th>...</th>
      <th>AwayTeam</th>
      <th>Timeout_Indicator</th>
      <th>posteam_timeouts_pre</th>
      <th>HomeTimeouts_Remaining_Pre</th>
      <th>AwayTimeouts_Remaining_Pre</th>
      <th>HomeTimeouts_Remaining_Post</th>
      <th>AwayTimeouts_Remaining_Post</th>
      <th>ExPoint_Prob</th>
      <th>TwoPoint_Prob</th>
      <th>Season</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>2009-09-10</td>
      <td>2009091000</td>
      <td>1</td>
      <td>1</td>
      <td>15</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>39</td>
      <td>0</td>
      <td>...</td>
      <td>TEN</td>
      <td>0</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2009</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2009-09-10</td>
      <td>2009091000</td>
      <td>1</td>
      <td>1</td>
      <td>15</td>
      <td>10</td>
      <td>5</td>
      <td>1</td>
      <td>5</td>
      <td>0</td>
      <td>...</td>
      <td>TEN</td>
      <td>0</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2009</td>
    </tr>
    <tr>
      <th>2</th>
      <td>2009-09-10</td>
      <td>2009091000</td>
      <td>1</td>
      <td>1</td>
      <td>15</td>
      <td>5</td>
      <td>2</td>
      <td>1</td>
      <td>-3</td>
      <td>0</td>
      <td>...</td>
      <td>TEN</td>
      <td>0</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2009</td>
    </tr>
    <tr>
      <th>3</th>
      <td>2009-09-10</td>
      <td>2009091000</td>
      <td>1</td>
      <td>1</td>
      <td>14</td>
      <td>8</td>
      <td>2</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>TEN</td>
      <td>0</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2009</td>
    </tr>
    <tr>
      <th>4</th>
      <td>2009-09-10</td>
      <td>2009091000</td>
      <td>1</td>
      <td>1</td>
      <td>14</td>
      <td>8</td>
      <td>2</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>TEN</td>
      <td>0</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2009</td>
    </tr>
  </tbody>
</table>
<p>5 rows × 37 columns</p>
</div>




```python
#check how much data did we lost
print("columns in original dataset: %d \n" % sf_permits.shape[1])
print("column swith na's dropped: %d" % columns_with_na_dropped.shape[1])
```

    columns in original dataset: 102 
    
    column swith na's dropped: 37
    


```python
subset_nfl_data = nfl_data.loc [:,'EPA':'Season'].head()
subset_nfl_data
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>EPA</th>
      <th>airEPA</th>
      <th>yacEPA</th>
      <th>Home_WP_pre</th>
      <th>Away_WP_pre</th>
      <th>Home_WP_post</th>
      <th>Away_WP_post</th>
      <th>Win_Prob</th>
      <th>WPA</th>
      <th>airWPA</th>
      <th>yacWPA</th>
      <th>Season</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>2.014474</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>0.485675</td>
      <td>0.514325</td>
      <td>0.546433</td>
      <td>0.453567</td>
      <td>0.485675</td>
      <td>0.060758</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2009</td>
    </tr>
    <tr>
      <th>1</th>
      <td>0.077907</td>
      <td>-1.068169</td>
      <td>1.146076</td>
      <td>0.546433</td>
      <td>0.453567</td>
      <td>0.551088</td>
      <td>0.448912</td>
      <td>0.546433</td>
      <td>0.004655</td>
      <td>-0.032244</td>
      <td>0.036899</td>
      <td>2009</td>
    </tr>
    <tr>
      <th>2</th>
      <td>-1.402760</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>0.551088</td>
      <td>0.448912</td>
      <td>0.510793</td>
      <td>0.489207</td>
      <td>0.551088</td>
      <td>-0.040295</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2009</td>
    </tr>
    <tr>
      <th>3</th>
      <td>-1.712583</td>
      <td>3.318841</td>
      <td>-5.031425</td>
      <td>0.510793</td>
      <td>0.489207</td>
      <td>0.461217</td>
      <td>0.538783</td>
      <td>0.510793</td>
      <td>-0.049576</td>
      <td>0.106663</td>
      <td>-0.156239</td>
      <td>2009</td>
    </tr>
    <tr>
      <th>4</th>
      <td>2.097796</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>0.461217</td>
      <td>0.538783</td>
      <td>0.558929</td>
      <td>0.441071</td>
      <td>0.461217</td>
      <td>0.097712</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2009</td>
    </tr>
  </tbody>
</table>
</div>




```python
subset_nfl_data.fillna(0)
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>EPA</th>
      <th>airEPA</th>
      <th>yacEPA</th>
      <th>Home_WP_pre</th>
      <th>Away_WP_pre</th>
      <th>Home_WP_post</th>
      <th>Away_WP_post</th>
      <th>Win_Prob</th>
      <th>WPA</th>
      <th>airWPA</th>
      <th>yacWPA</th>
      <th>Season</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>2.014474</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.485675</td>
      <td>0.514325</td>
      <td>0.546433</td>
      <td>0.453567</td>
      <td>0.485675</td>
      <td>0.060758</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>2009</td>
    </tr>
    <tr>
      <th>1</th>
      <td>0.077907</td>
      <td>-1.068169</td>
      <td>1.146076</td>
      <td>0.546433</td>
      <td>0.453567</td>
      <td>0.551088</td>
      <td>0.448912</td>
      <td>0.546433</td>
      <td>0.004655</td>
      <td>-0.032244</td>
      <td>0.036899</td>
      <td>2009</td>
    </tr>
    <tr>
      <th>2</th>
      <td>-1.402760</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.551088</td>
      <td>0.448912</td>
      <td>0.510793</td>
      <td>0.489207</td>
      <td>0.551088</td>
      <td>-0.040295</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>2009</td>
    </tr>
    <tr>
      <th>3</th>
      <td>-1.712583</td>
      <td>3.318841</td>
      <td>-5.031425</td>
      <td>0.510793</td>
      <td>0.489207</td>
      <td>0.461217</td>
      <td>0.538783</td>
      <td>0.510793</td>
      <td>-0.049576</td>
      <td>0.106663</td>
      <td>-0.156239</td>
      <td>2009</td>
    </tr>
    <tr>
      <th>4</th>
      <td>2.097796</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.461217</td>
      <td>0.538783</td>
      <td>0.558929</td>
      <td>0.441071</td>
      <td>0.461217</td>
      <td>0.097712</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>2009</td>
    </tr>
  </tbody>
</table>
</div>


