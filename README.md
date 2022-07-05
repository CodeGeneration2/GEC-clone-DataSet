# ECG–clone DataSet
  Since efficient code generation is a new branch that is opened for code generation, we curate a new dataset of efficient code generation programming problems called ECG for fine-tuning and evaluation. Accordingly, our model is fine-tuned on the ECG dataset. 
  
  The ECG draws on the APPS dataset (Hendrycks et al., 2021) and the CodeContests dataset (Li et al., 2022). We describe the dataset creation process and creative ideas in detail in Readme for DataSet folder.

  Although we developed the ECG dataset to perform efficient code generation, the ECG dataset is an exhaustive dataset that can be applied to different tasks. Therefore, we derived three datasets from this feature of the ECG dataset that can be applied to different specific code processing tasks to fill the gap of other code processing-oriented datasets.
  
Among the ECG datasets our model uses for efficient code generation, we derive three datasets from them: ECG-CG, ECG-mini, and [ECG-clone](https://github.com/CodeGeneration2/ECG-clone-DataSet). 
The specific description of [the ECG-clone dataset](https://github.com/CodeGeneration2/ECG-clone-DataSet) below.


## ECG–clone DataSet
Although this paper is not a study of code cloning, many of our datasets have different codes that implement the same functionality. 
Therefore, we can derive a semantic clone dataset from ECG. Each data in ECG-clone has two different implementations of the code.












