<pre class="file" data-target="clipboard">
# Hint: You can copy Solution to ClipBoard from Solution Tab
# multiplicative decompose time series
from pandas import read_csv
from matplotlib import pyplot
from statsmodels.tsa.seasonal import seasonal_decompose
series = read_csv('global-travelers.csv', header=0, index_col=0, parse_dates=True, squeeze=True)
result = seasonal_decompose(series, model='multiplicative')
result.plot()
pyplot.show()
</pre>

