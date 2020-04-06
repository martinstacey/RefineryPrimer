# Highest Point of a Surface

The _`01-01_EvaluateSurface.dyn`_ graph in the Generative Design examples uses a single objective optimization approach to find the highest Z point on a sinuous surface. 

The objective of the graph is to get the orange sphere to the highest peak of the surface.

[Download Dynamo file](https://github.com/DynamoDS/RefineryPrimer/releases/download/samples-v1/04-01-01_Highest-point-of-a-surface.dyn).

![](../../.gitbook/assets/applychanges1.png)

U and V Point values are used to move the sphere across the surface. Because these values are the driving inputs, they need to be marked as 'IsInput' for Generative Design to recognize them.

![](../../.gitbook/assets/applychanges2.png)

In order to know when the sphere is at the highest peak, a measure of the Z value is made every time the sphere moves - this represents the fitness value.

When running this graph in Generative Design, follow these steps:

1. Use the 'Optimize' generation method.
2. Under 'Inputs', make sure that all inputs are checked.
3. Under 'Outputs', set the 'Z Point Value' to 'Maximize' . If you want the lowest point, set it to 'Minimize' . 
4. Under 'Settings', input your 'Population Size' and the number of 'Generations' you want.  
5. Under 'Issues', resolve any items.
6. Click 'Generate' to run the optimization process.

![](../../.gitbook/assets/applychanges3.png)

As this is a single optimization problem, Generative Design will return only one, global optimum result - in this case, the highest peak on the surface.

