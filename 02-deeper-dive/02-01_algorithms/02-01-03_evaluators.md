# Evaluators

An evaluator \(also known as a discriminator\), is fed potential solutions from the generator and evaluates how good or bad these solutions are. Evaluators are a natural analogue of the objective and fitness functions outlined in [section 04-08](https://github.com/martinstacey/RefineryPrimer/tree/496f204f835e39d17e57c89b84d64d051c2398ae/04-optimization/04-08_the-evaluation-phase.md). In a generative building design, an evaluator may be a function that describes the average amount of sunlight a façade will be exposed to over a year.

In design, evaluators must be specified mathematically, they must output a number that can be used to discriminate between solutions.

![](https://github.com/martinstacey/RefineryPrimer/tree/f565c2e5d3b423678fe7a90e35b5b52984bbd6fd/.gitbook/assets/evaluators1.png)

Again, in the simple Dynamo example below, the nodes that are highlighted demonstrate evaluators. They are nodes that query a particular property of the design option, in this case the volume and surface area of the cuboid. These evaluators allow the user or programme to critique each design option to help pick the best one based on our predefined rules - maximum volume, minimum surface area etc.

![](https://github.com/martinstacey/RefineryPrimer/tree/f565c2e5d3b423678fe7a90e35b5b52984bbd6fd/.gitbook/assets/evaluators2.png)

