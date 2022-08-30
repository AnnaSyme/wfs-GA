## **Using and customising workflows in Galaxy Australia**

Anna Syme


## Learn about workflows

Galaxy Training Network materials:
* [Creating, Editing and Importing Galaxy Workflows](https://training.galaxyproject.org/training-material/topics/galaxy-interface/tutorials/workflow-editor/tutorial.html)
* [Extracting Workflows from Histories](https://training.galaxyproject.org/training-material/topics/galaxy-interface/tutorials/history-to-workflow/tutorial.html)
* [Using Workflow Parameters](https://training.galaxyproject.org/training-material/topics/galaxy-interface/tutorials/workflow-parameters/tutorial.html)
* [Workflow Reports](https://training.galaxyproject.org/training-material/topics/galaxy-interface/tutorials/workflow-reports/tutorial.html)
* [Automating Galaxy workflows using the command line](https://training.galaxyproject.org/training-material/topics/galaxy-interface/tutorials/workflow-automation/tutorial.html)

## Get a workflow

* Make one using the workflow canvas
* Create one from an existing Galaxy history
* Import one from a GTN tutorial or from **Shared Data: Workflows**
* If you are using an imported and/or old workflow, some of the tools may not be the most recent version. In the workflow canvas, click on the cog wheel, then click "Upgrade workflow". This will set all the tools to the most recent version. However - you may lose particular settings. It may be better to upgrade each tool one by one, checking that all your settings are correct in the new version. 

## Test it with a small data set

* The smaller, the better! 
* Subsample large data sets if possible. 

## View outputs

* The outputs appear in your history - but they populate according to when the jobs are scheduled, rather than the end points of the workflow. 
* To see a more natural order of the outputs, go to **User: Workflow Invocations** to see the list of workflows you have run. 
* Click on the workflow of interest to expand. 
* Click on "Steps" to expand.
* In each step, click on "Output datasets", and view with the eye icon. 

## Label outputs

* In the workflow canvas, click on a tool and see the information in the right-hand panel. 
* Add text to the Label. 
* This will become the label for the particular "step" in the workflow. It will then be visible in the output steps, if you are viewing the Workflow Invocation. 

## Tag outputs

* In the workflow canvas, click on a tool and see the parameters in the right-hand panel. 
* Click on "Configure output". You can re-name the output file, and/or add tags. 
* For example, to easily find an output assembly, you could tag it with #final-assembly. 


