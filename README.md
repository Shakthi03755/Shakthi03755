from pandas import read_csv
from matplotlib import pyplot
series=read_csv(r'C:\Users\shakthi\Downloads\shampoo.csv')

print(series.head())
series.plot()
pyplot.show()
![1000051549](https://github.com/user-attachments/assets/a018183e-1e19-4d59-bdb3-3762f6cbb4be)
series.plot(style='-.')
pyplot.show()
![1000051539](https://github.com/user-attachments/assets/ab5a51a8-5742-4b3c-9bae-abc05d75ca45)
series.hist()
pyplot.show()
![1000051541](https://github.com/user-attachments/assets/0614c06d-a310-4537-9df7-9bb7c8f060f8)
series.plot(kind='kde')
pyplot.show()![1000051543](https://github.com/user-attachments/assets/0fc05345-ae47-4581-9956-611b13e6d082)
