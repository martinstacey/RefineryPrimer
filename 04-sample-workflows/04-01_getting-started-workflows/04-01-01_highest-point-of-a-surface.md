# Highest Point of a Surface

The _`01-01_EvaluateSurface.dyn`_ graph in the Refinery examples, uses a single objective optimization approach to find the highest Z point on a sinuous surface. The objective of the graph is to get the orange sphere to the highest peak of the surface. [get files](https://github.com/martinstacey/RefineryPrimer/tree/ContentBranch/04-sample-workflows/04-00_sample_files/04-00-01_gettingstarted)

![](https://github.com/martinstacey/RefineryPrimer/tree/f565c2e5d3b423678fe7a90e35b5b52984bbd6fd/.gitbook/assets/applychanges1.png)

U and V values are used to move the sphere across the surface. Since these values are the driving inputs, they need to be marked as _`IsInput`_ for Refinery to pick them up.

![](https://github.com/martinstacey/RefineryPrimer/tree/f565c2e5d3b423678fe7a90e35b5b52984bbd6fd/.gitbook/assets/applychanges2.png)

In order to know when the sphere is at the highest peak, a measure of the Z-value is made every time the sphere moves, this represents the _`fitness value`_.

When running this graph in Refinery:

* Use the _`Optimize`_ generation method
* Under Inputs make sure that all inputs are checked
* Under Outputs set the _`Point Z value (Height)`_ to _`Maximize`_ \(if you want the lowest point, set it to Minimize\).  
* Under settings set Population Size and number of Generations  
* Under Issues resolve any items
* Click Generate to run the optimization process.

![](https://github.com/martinstacey/RefineryPrimer/tree/f565c2e5d3b423678fe7a90e35b5b52984bbd6fd/.gitbook/assets/applychanges3.png)

As this is a Single Optimization problem, Refinery returns only one result which is the global optimum or in this case the highest peak on the surface.

