## Data-Structures in Pandas

**Data alignment is intrinsic.** The link between labels and data will not be broken unless done so explicitly by us.

### Series

Series is a one-dimensional labeled array capable of holding any data type (integers, strings, floating point numbers, Python objects, etc.). The axis labels are collectively referred to as the index. The basic method to create a Series is to call:

''' >>> s = pd.Series(data, index=index) '''

