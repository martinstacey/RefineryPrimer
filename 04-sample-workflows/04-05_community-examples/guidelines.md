# Guidelines

## Submitting Changes on the Primer

If you have any suggestions for the primer, we will gladly review them. To do so, please follow the guidelines in the following link:

[https://github.com/DynamoDS/RefineryPrimer/blob/master/CONTRIBUTING.md](https://github.com/DynamoDS/RefineryPrimer/blob/master/CONTRIBUTING.md)

## Submitting Examples

If you have an example please create a Pull Request in GitHub containing your workflow. Follow these steps: 

#### **1. Upload files:** 

* Place all related files in a zip folder and upload it as a release. 
  * Visit the following website for more information into how to upload a release: [https://help.github.com/en/github/administering-a-repository/managing-releases-in-a-repository](https://help.github.com/en/github/administering-a-repository/managing-releases-in-a-repository)
* The zip file should be named using the following format: 04-06\_ + last name first three initials + short descriptive name. Example: `04-06_RAH_FloorsFromSolarAnalysis.zip`
* All files should be named using the same format. Example:  `RAH_FloorsFromSolarAnalysis.dyn`.
* Make sure your file runs on last version of Refinery and Revit. 
* You should include: 
  * Dynamo file
  * Revit file in last available version.
  * Video tutorial \(optional\)
  * In-depth description in PDF format \(optional\)

#### 2. Create Description

* Write your workflow description in the following folder location: `04-sample-worflows/04-06_Community-Examples/04-06-00_List_Of_Examples.md`
* The example description should include: 
  * Tittle of workflow
  * Author of script
  * Required dynamo packages to run script
  * Brief description of how the workflow works and why it is useful.
  * Descriptive Image of workflow \(Optional\)
  * Links to files uploaded in the `Example_Files` folder.
* Check the first workflow example \(High Performance Building Design Based on Daylight Analysis\) as a reference on how to upload files. 

## Dynamo Files Basic Guidelines

To ensure that all sample files presented in this page are easy to understand, we recommend you follow these general guidelines:

### Create a Title Block

This title block will help the user identify all the requirements needed to run the workflow \(Revit version, required dynamo packages, etc.\). The title block will also display observations that help explain what the workflow does, and how is it useful.  

> You can copy a panel from an existing document and change the information in it so it suits your workflow

![](../../.gitbook/assets/community2.png)

### Organize Nodes Into Groups

Organizing nodes into groups will help the user understand how the workflow is structured. Groups should have comments that indicate the general purpose of the group of nodes.

![](../../.gitbook/assets/community3.png)

### Follow Color Guidelines

We use a consistent color pallet through out our workflows. Don't forget to follow this color pallet in your workflow:

####  Inputs - Pink

![](../../.gitbook/assets/comunity4.png)

#### Generators - Green

![](../../.gitbook/assets/comunity5.png)

#### Display - Blue

![](../../.gitbook/assets/comunity6.png)

#### Metrics - Orange

![](../../.gitbook/assets/comunity7.png)

#### Remember/Gate - Purple 

![](../../.gitbook/assets/comunity8.png)

