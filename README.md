# DLworkflowWithPytorch

**Description**

Workflow for doing single/multi GPU deep learning with ability to track multiple hyperparameters, code checkpointing and save the best model definition.

**How to use it**

Python notebook has been commented appropriately and should be enought to guide throught the process.

**Features**
-	Choose number of GPUs to run your code on.
-	Define parameters and hyperparameters to track and test your model on.
-	Save the output in a .csv file for reproducability and later investigation.
**NOTE:** Run and epoch durations are in seconds.

![csvoutput](https://github.com/ghltshubh/DLworkflowWithPytorch/blob/master/csv_output.png?raw=true)

-	Create checkpoint at epoch level to resume the training later.
-	Choose and automatically save the best model.
