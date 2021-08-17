---
layout: post
title: "Assignment 1"
subtitle: "This is just a test. Will remove later."
background: '/img/posts/test2-jup-note/bg-about.jpg'
---

## Assignment 1 testing ground

You can change what you want here, but we won't be evaluating it.  We will run the original version of this notebook plus any additional secret tests we deem fit.


```python
import a1
import matplotlib.pyplot as plt
```


```python
df = a1.part1_load("grain", "crude")
```


```python
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
      <th>0</th>
      <th>1</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>0.490152</td>
      <td>1.477474</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1.076585</td>
      <td>0.286503</td>
    </tr>
  </tbody>
</table>
</div>




```python
plot = a1.part2_vis(df)
```


![png](/img/posts/test2-jup-note/output_4_0.png)



```python
df2 = a1.part3_tfidf(df)
```


```python
plot2 = a1.part2_vis(df2)
```


![png](/img/posts/test2-jup-note/output_6_0.png)


You can do whatever else, including testing the bonus, here.


```python

```
