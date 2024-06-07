# RTlogD

# Setup and dependencies

Dependencies：

- rdkit
- python >=3.10
- pytorch 1.13.0
- dgl 0.8.1
- numpy
- pandas
- tqdm
- dgllife 0.2.9

```
conda install pytorch==1.13.1 cpuonly -c pytorch
conda install dglteam::dgl==0.8.1
pip install dgllife==0.2.9
mamba install 'mkl<=2024.0'
```

# Using

# Test

#### **Reproducing results in the paper**

```python
python test_T_data.py 
```

Run the above script to get the results of RTlogD on T-data.

#### For predicting new molecules

1. Put the data into example.csv

2. ```
    python test.py 
   ```

3.  The predicted results will be shown in the results folder.

# Author

s20-wangyitian@simm.ac.cn
