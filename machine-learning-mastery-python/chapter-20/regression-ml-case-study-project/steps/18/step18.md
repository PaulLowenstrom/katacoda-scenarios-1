Take a look at the distribution of scores across all cross-validation folds by algorithm

# Compare Algorithms
`fig = pyplot.figure()
fig.suptitle('Algorithm Comparison')
ax = fig.add_subplot(111)
pyplot.boxplot(results)
ax.set_xticklabels(names)
pyplot.show()`