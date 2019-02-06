

```python
##  importing the data frame with pandas
##  CSV file of interest MUST be in the file you are working with to import data
##  (can use tab key to auto-complete name of file)
##  Saving the dataframe as "df" for easy access later

import pandas as pd
df = pd.read_csv("LIF Ashland Nit 12-13-18.csv")
df
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
      <th>Sample Name</th>
      <th>410 nm   [A]</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1_1</td>
      <td>0.004</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1_2</td>
      <td>0.003</td>
    </tr>
    <tr>
      <th>2</th>
      <td>2_1</td>
      <td>0.001</td>
    </tr>
    <tr>
      <th>3</th>
      <td>2_2</td>
      <td>0.003</td>
    </tr>
    <tr>
      <th>4</th>
      <td>0.00</td>
      <td>0.006</td>
    </tr>
    <tr>
      <th>5</th>
      <td>0.00</td>
      <td>0.006</td>
    </tr>
    <tr>
      <th>6</th>
      <td>0.00</td>
      <td>0.006</td>
    </tr>
    <tr>
      <th>7</th>
      <td>1500.0</td>
      <td>0.166</td>
    </tr>
    <tr>
      <th>8</th>
      <td>1500.0</td>
      <td>0.171</td>
    </tr>
    <tr>
      <th>9</th>
      <td>1500.0</td>
      <td>0.166</td>
    </tr>
    <tr>
      <th>10</th>
      <td>3000.0</td>
      <td>0.302</td>
    </tr>
    <tr>
      <th>11</th>
      <td>3000.0</td>
      <td>0.300</td>
    </tr>
    <tr>
      <th>12</th>
      <td>3000.0</td>
      <td>0.299</td>
    </tr>
    <tr>
      <th>13</th>
      <td>4500.0</td>
      <td>0.437</td>
    </tr>
    <tr>
      <th>14</th>
      <td>4500.0</td>
      <td>0.448</td>
    </tr>
    <tr>
      <th>15</th>
      <td>4500.0</td>
      <td>0.545</td>
    </tr>
    <tr>
      <th>16</th>
      <td>LIF-241</td>
      <td>1.181</td>
    </tr>
    <tr>
      <th>17</th>
      <td>LIF-241</td>
      <td>1.193</td>
    </tr>
    <tr>
      <th>18</th>
      <td>LIF-242</td>
      <td>1.101</td>
    </tr>
    <tr>
      <th>19</th>
      <td>LIF-242</td>
      <td>1.143</td>
    </tr>
    <tr>
      <th>20</th>
      <td>LIF-243</td>
      <td>1.414</td>
    </tr>
    <tr>
      <th>21</th>
      <td>LIF-243</td>
      <td>1.367</td>
    </tr>
    <tr>
      <th>22</th>
      <td>LIF-244</td>
      <td>1.185</td>
    </tr>
    <tr>
      <th>23</th>
      <td>LIF-244</td>
      <td>1.229</td>
    </tr>
    <tr>
      <th>24</th>
      <td>LIF-245</td>
      <td>1.074</td>
    </tr>
    <tr>
      <th>25</th>
      <td>LIF-245</td>
      <td>1.077</td>
    </tr>
    <tr>
      <th>26</th>
      <td>LIF-246</td>
      <td>1.466</td>
    </tr>
    <tr>
      <th>27</th>
      <td>LIF-246</td>
      <td>1.604</td>
    </tr>
    <tr>
      <th>28</th>
      <td>LIF-247</td>
      <td>1.438</td>
    </tr>
    <tr>
      <th>29</th>
      <td>LIF-247</td>
      <td>1.401</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>42</th>
      <td>LIF-254</td>
      <td>1.114</td>
    </tr>
    <tr>
      <th>43</th>
      <td>LIF-254</td>
      <td>1.125</td>
    </tr>
    <tr>
      <th>44</th>
      <td>LIF-255</td>
      <td>1.092</td>
    </tr>
    <tr>
      <th>45</th>
      <td>LIF-255</td>
      <td>1.059</td>
    </tr>
    <tr>
      <th>46</th>
      <td>LIF-256</td>
      <td>1.124</td>
    </tr>
    <tr>
      <th>47</th>
      <td>LIF-256</td>
      <td>1.102</td>
    </tr>
    <tr>
      <th>48</th>
      <td>LIF-257</td>
      <td>1.208</td>
    </tr>
    <tr>
      <th>49</th>
      <td>LIF-257</td>
      <td>1.279</td>
    </tr>
    <tr>
      <th>50</th>
      <td>LIF-258</td>
      <td>0.674</td>
    </tr>
    <tr>
      <th>51</th>
      <td>LIF-258</td>
      <td>0.681</td>
    </tr>
    <tr>
      <th>52</th>
      <td>LIF-259</td>
      <td>0.663</td>
    </tr>
    <tr>
      <th>53</th>
      <td>LIF-259</td>
      <td>0.672</td>
    </tr>
    <tr>
      <th>54</th>
      <td>LIF-260</td>
      <td>0.824</td>
    </tr>
    <tr>
      <th>55</th>
      <td>LIF-260</td>
      <td>0.794</td>
    </tr>
    <tr>
      <th>56</th>
      <td>LIF-261</td>
      <td>0.648</td>
    </tr>
    <tr>
      <th>57</th>
      <td>LIF-261</td>
      <td>0.675</td>
    </tr>
    <tr>
      <th>58</th>
      <td>LIF-262</td>
      <td>0.759</td>
    </tr>
    <tr>
      <th>59</th>
      <td>LIF-262</td>
      <td>0.792</td>
    </tr>
    <tr>
      <th>60</th>
      <td>LIF-263</td>
      <td>0.562</td>
    </tr>
    <tr>
      <th>61</th>
      <td>LIF-263</td>
      <td>1.099</td>
    </tr>
    <tr>
      <th>62</th>
      <td>LIF-264</td>
      <td>0.871</td>
    </tr>
    <tr>
      <th>63</th>
      <td>LIF-264</td>
      <td>0.847</td>
    </tr>
    <tr>
      <th>64</th>
      <td>LIF-265</td>
      <td>0.944</td>
    </tr>
    <tr>
      <th>65</th>
      <td>LIF-265</td>
      <td>0.951</td>
    </tr>
    <tr>
      <th>66</th>
      <td>LIF-266</td>
      <td>0.785</td>
    </tr>
    <tr>
      <th>67</th>
      <td>LIF-266</td>
      <td>0.780</td>
    </tr>
    <tr>
      <th>68</th>
      <td>LIF-267</td>
      <td>0.665</td>
    </tr>
    <tr>
      <th>69</th>
      <td>LIF-267</td>
      <td>0.659</td>
    </tr>
    <tr>
      <th>70</th>
      <td>LIF-268</td>
      <td>0.968</td>
    </tr>
    <tr>
      <th>71</th>
      <td>LIF-268</td>
      <td>0.969</td>
    </tr>
  </tbody>
</table>
<p>72 rows × 2 columns</p>
</div>




```python
## Create groups based on "key" ... in this case, I want everything
## grouped by the column "Sample Name"

g = df.groupby('Sample Name') ## title of column of interest
g
```




    <pandas.core.groupby.groupby.DataFrameGroupBy object at 0x000000000932EDA0>




```python
## Groups are stored internally
```


```python
## manipulating groups

g.mean()
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
      <th>410 nm   [A]</th>
    </tr>
    <tr>
      <th>Sample Name</th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0.00</th>
      <td>0.006000</td>
    </tr>
    <tr>
      <th>1500.0</th>
      <td>0.167667</td>
    </tr>
    <tr>
      <th>1_1</th>
      <td>0.004000</td>
    </tr>
    <tr>
      <th>1_2</th>
      <td>0.003000</td>
    </tr>
    <tr>
      <th>2_1</th>
      <td>0.001000</td>
    </tr>
    <tr>
      <th>2_2</th>
      <td>0.003000</td>
    </tr>
    <tr>
      <th>3000.0</th>
      <td>0.300333</td>
    </tr>
    <tr>
      <th>4500.0</th>
      <td>0.476667</td>
    </tr>
    <tr>
      <th>LIF-241</th>
      <td>1.187000</td>
    </tr>
    <tr>
      <th>LIF-242</th>
      <td>1.122000</td>
    </tr>
    <tr>
      <th>LIF-243</th>
      <td>1.390500</td>
    </tr>
    <tr>
      <th>LIF-244</th>
      <td>1.207000</td>
    </tr>
    <tr>
      <th>LIF-245</th>
      <td>1.075500</td>
    </tr>
    <tr>
      <th>LIF-246</th>
      <td>1.535000</td>
    </tr>
    <tr>
      <th>LIF-247</th>
      <td>1.419500</td>
    </tr>
    <tr>
      <th>LIF-248</th>
      <td>1.569500</td>
    </tr>
    <tr>
      <th>LIF-249</th>
      <td>1.292000</td>
    </tr>
    <tr>
      <th>LIF-250</th>
      <td>1.081500</td>
    </tr>
    <tr>
      <th>LIF-251</th>
      <td>1.177000</td>
    </tr>
    <tr>
      <th>LIF-252</th>
      <td>1.220000</td>
    </tr>
    <tr>
      <th>LIF-253</th>
      <td>1.398500</td>
    </tr>
    <tr>
      <th>LIF-254</th>
      <td>1.119500</td>
    </tr>
    <tr>
      <th>LIF-255</th>
      <td>1.075500</td>
    </tr>
    <tr>
      <th>LIF-256</th>
      <td>1.113000</td>
    </tr>
    <tr>
      <th>LIF-257</th>
      <td>1.243500</td>
    </tr>
    <tr>
      <th>LIF-258</th>
      <td>0.677500</td>
    </tr>
    <tr>
      <th>LIF-259</th>
      <td>0.667500</td>
    </tr>
    <tr>
      <th>LIF-260</th>
      <td>0.809000</td>
    </tr>
    <tr>
      <th>LIF-261</th>
      <td>0.661500</td>
    </tr>
    <tr>
      <th>LIF-262</th>
      <td>0.775500</td>
    </tr>
    <tr>
      <th>LIF-263</th>
      <td>0.830500</td>
    </tr>
    <tr>
      <th>LIF-264</th>
      <td>0.859000</td>
    </tr>
    <tr>
      <th>LIF-265</th>
      <td>0.947500</td>
    </tr>
    <tr>
      <th>LIF-266</th>
      <td>0.782500</td>
    </tr>
    <tr>
      <th>LIF-267</th>
      <td>0.662000</td>
    </tr>
    <tr>
      <th>LIF-268</th>
      <td>0.968500</td>
    </tr>
  </tbody>
</table>
</div>




```python
## THIS URL WAS A LIFESAVER
## https://jakevdp.github.io/PythonDataScienceHandbook/03.08-aggregation-and-grouping.html
```
