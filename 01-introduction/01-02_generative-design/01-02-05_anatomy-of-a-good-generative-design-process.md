# Anatomy of a Good Generative Design Process

A helpful general rule for developing good generative design workflows could be:

> Ask & answer as many questions about the activities & aspects involved in each of the [stages of generative design](https://github.com/martinstacey/RefineryPrimer/tree/496f204f835e39d17e57c89b84d64d051c2398ae/01-introduction/01-introduction/01-04_what-goes-into-a-generative-design-process.md) \(Generate, Evaluate, Evolve, Explore, Integrate\) as you can think about.

To guide you through this process, you'll find below a helpful framework, with notes, questions and pointers. This is by no means an exhaustive list, so please feel free to make it your own - and maybe even contribute to this primer!

![](https://github.com/martinstacey/RefineryPrimer/tree/f565c2e5d3b423678fe7a90e35b5b52984bbd6fd/.gitbook/assets/good1.png)

## Step 1 : Define your problem

The first thing to do is to have a clear understanding of what you want to achieve, asking yourself:

* What do you want to design?
* What are the design parameters?
* What conditions must the design satisfy?
* What must not be present in a final design?
* What makes the design a success or a failure?
* What aspects would you like to maximize or minimize?

![](https://github.com/martinstacey/RefineryPrimer/tree/f565c2e5d3b423678fe7a90e35b5b52984bbd6fd/.gitbook/assets/good2.png)

Answering these questions not only clarifies the problem at hand in the designer’s mind, but also helps break the problem into smaller components that will be used in each stage of the generative design process. The more questions you formulate and the more precisely you can answer these questions, the more relevant the outputs of a generative process will be.

**Example**

> Imagine you’ve been engaged by a client to design a school. You’d want to nail down precisely the site restrictions, number of students, teaching profile, total budget, and any other mission-critical requirements as soon as possible.

As a designer, you wouldn't sign up to design the school without a sufficiently defined brief. This step is critically important, since a generative process cannot consider any goals that has not been instructed to consider.

## Step 2 : Sketch it Out

Now that you've written down a rough definition of the problem, it's time to look at potential solutions! Start with the end design in mind, remembering what you want to achieve and work backwards from there, letting each section guide the next one. Don't be afraid to draw, diagram, mind-map or use any other technique you prefer to help you document the below.

![](https://github.com/martinstacey/RefineryPrimer/tree/f565c2e5d3b423678fe7a90e35b5b52984bbd6fd/.gitbook/assets/good3.png)

For the **Generate** phase:

* Can you write down your design steps? Generally, if you can define the concrete steps used to design something, it is much easier to create a computational model.
* Specify constraints and anything else that will drive your design. Is it sizes, quantities, environmental or cost factors?
* Are you generating geometry and what are the driving parameters of the geometry? Is it one of the constraints or something else?
* Are there any dependencies or relationships between different elements in your design? For example, when designing a masterplan, does the height of one building affect the height of its neighboring buildings? If so, define how these relationships are expressed.

For the **Evaluation** phase:

* What do you need to measure or analyse? Make sure you're not defining any metrics that measure the same thing, just in different ways.
* How can these aspects be measured or quantified? Is there an existing methodology you can learn from?
* Evaluation will drive the optimization process, so it contributes significantly to the overall process. As such, poorly defined evaluation criteria will result in less than stellar solutions.

For the **Exploration** & **Evolution** phases:

* What key result do you want?  
* What kind of decision will you be trying to make? Is it choosing a single outcome \(a design solution maybe\), an approach \(comparing multiple classes of solutions\) or something altogether different?
* What influences that decision?

## Step 3 : Define Inputs & Outputs

For this step, try to think about the overall process and the constants & variables in your defined problem & solution?

![](https://github.com/martinstacey/RefineryPrimer/tree/f565c2e5d3b423678fe7a90e35b5b52984bbd6fd/.gitbook/assets/good4.png)

* Identify which inputs will change for each stage and what are their allowed value ranges
* Identify the inputs that will remain the same for all stages & across generated solutions
* Start with the minimal needed inputs and gradually add more if needed as you become more aware of what your design needs.
* What are you trying to accomplish during this step? Decide if/what you need to measure and if/how that output is communicated to subsequent steps.

## Step 4 : Measuring which Option is Best

Having precise rules for evaluation is critical for a Generative Design process to be successful. Without anything to evaluate, the generative process will produce a random and arbitrary set of designs which may not be of use to any designer.

![](https://github.com/martinstacey/RefineryPrimer/tree/f565c2e5d3b423678fe7a90e35b5b52984bbd6fd/.gitbook/assets/good5.png)

Adding evaluation criteria to a computational process makes it more complex, but also more realistic and relevant to the designer’s needs. Whilst adding evaluation conditions that say “make the largest table possible” and “use the fewest materials possible” make the model complex \(there is now an unavoidable tradeoff that must be considered\), they also directly target what the designer is most interested in \(a big table at minimum cost\). Algorithms perform best when these conditions are combined and a solution that balances them must be found.

## Step 5 : Results

To get the most out of your generative design process, remember that the final step isn't necessarily where the process ends, so ask yourself some of the following questions.

![](https://github.com/martinstacey/RefineryPrimer/tree/f565c2e5d3b423678fe7a90e35b5b52984bbd6fd/.gitbook/assets/good6.png)

* How do you want to review the results? Do you need 3D visuals, a data table, graphs or all of the above?
* Who is the target audience and what do you want them to decide on?
* How many options should you present to the target audience? Too many options to consider can get overwhelming and too few can make the process look shallow, make sure to find the best balance based on your measures.
* What do you want to do with the results? What is the next step?
* Does generative process happen only once or does it repeat? If it repeats, what changes between iterations and what can be learnt from previous ones?

