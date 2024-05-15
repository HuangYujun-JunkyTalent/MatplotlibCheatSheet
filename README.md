# MatplotlibCheatSheet
Some tricks and techniques for matplotlib

## We can put the legend anywhere
Using the `bbox_to_anchor`, we can put the legend anywhere: https://stackoverflow.com/questions/4700614/how-to-put-the-legend-outside-the-plot

Remember to use the `bbox_inches = "tight"` when saving the fig to get the figure complete.

## We can plot axlines and lines outside the axis
by `ax.get_xlim()` and `ax.set_xlim()` we can set and rest the limits.
by `clip_on=False` to allow plots and texts lay outside the ax.
