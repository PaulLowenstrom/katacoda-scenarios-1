<pre class="file" data-target="clipboard">
# Hint: You can copy Solution to ClipBoard from Solution Tab
# load and plot a time series
from pandas import read_csv
from matplotlib import pyplot
series = read_csv('global-travelers.csv', header=0, index_col=0, parse_dates=True, squeeze=True)
pyplot.figure(1)
# line plot
pyplot.subplot(211)
pyplot.plot(series)
# histogram
pyplot.subplot(212)
pyplot.hist(series)
pyplot.show()
</pre>