# Setting Up a Graph for Generative Design

## Inputs

To set up a Dynamo graph for Generative Design, please do the following:

1. Right-click on each node used to drive the graph and ensure that the 'Is Input' option is ticked. 

Renaming the node with a standard approach such as _`IN_description`_ will help to distinguish these inputs in Generative Design.

_Note: Currently all inputs must be 'Number' slider nodes._

![](../.gitbook/assets/setting1.png)

## Outputs

To define outputs in Generative Design, please do the following:

1. Right-click on the watch nodes and select the 'Is Output' option. 

Renaming the node with a standard approach such as _`OUT_description`_ will help to distinguish these outputs in Generative Design.

_Note: Currently all outputs must be watch nodes with a 'Number' data type._

![](../.gitbook/assets/setting2.png)

## Export to Generative Design

Once both inputs and outputs are set up correctly and your graph is saved, you can create an export to use with Generative Design. 

To create an export to use with Generative Design, please do the following:

1. In Dynamo, navigate to the toolbar and select Generative Design &gt; Export for Generative Design. Generative Design will then create a copy of your graph which will be available to launch.

![](../.gitbook/assets/setting21.png)

_Note: Graphs with the same name will be overwritten._

![](../.gitbook/assets/setting22.png)

## Launch Generative Design

To launch Generative Design, please do the following:

1. In Dynamo, navigate to the toolbar and select Generative Design &gt; Create Study.

![](../.gitbook/assets/setting23.png)

2. Once Generative Design has launched, select a saved study.

![](../.gitbook/assets/setting3.png)

