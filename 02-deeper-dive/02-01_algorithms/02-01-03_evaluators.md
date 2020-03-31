# Evaluators

An evaluator (also known as a discriminator), is fed potential solutions from the generator and evaluates how good or bad these solutions are. Evaluators are a natural analogue of the objective and fitness functions outlined in [section 02-03-02](..\02-03_optimization\02-03-02_objective-function.md). In a generative building design, an evaluator may be a function that describes the average amount of sunlight a façade will be exposed to over a year. 

In design, evaluators must be specified mathematically, they must output a number that can be used to discriminate between solutions.

![](../../.gitbook/assets/evaluators1.png)

Again, in the simple Dynamo example below, the nodes that are highlighted demonstrate evaluators. They are nodes that query a particular property of the design option, in this case the volume and surface area of the cuboid. These evaluators allow the user or programme to critique each design option to help pick the best one based on our predefined rules - maximum volume, minimum surface area etc.

![](../../.gitbook/assets/evaluators2.png)

<img src="../../assets/deeper/evaluators2.png" style="width:200px;"/>

