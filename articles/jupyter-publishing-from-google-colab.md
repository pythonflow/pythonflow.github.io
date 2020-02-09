
# Header


```
%matplotlib inline
from matplotlib import pyplot as plt
import pandas as pd

s = pd.Series([1,2,3], index=['a','b','c'])

s.plot.bar(figsize=(10,5))
plt.xlabel('Foo')
plt.ylabel('Bar')
plt.title("Hello World");
```


![png](jupyter-publishing-from-google-colab_files/jupyter-publishing-from-google-colab_1_0.png)

