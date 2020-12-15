# CISC881FinalProject
The final code submitted in association with my CISC 881 final project.
The whole codebase has been compressed down to 2 jupyter files:

1. **CentralLine_VesselUNet**
This file contains the code that preprocesses data for, builds, trains and tests the U-Net.

2. **CentralLine_PoseClassifier**
This file contains the code that preprocesses data for, builds, trains and tests the classifier.

Note that, for both notebooks, outputs have been conserved to show the function and performance of each section.

## Running Code
To run this code, you must first clone [SlicerIGT/aigt repo](https://github.com/SlicerIGT/aigt).

The following path variables must be changed:
 - **preprocessing_input_dir**: change to SampleData folder path.
 - **preprocessing_output_dir**: change to empty folder to store preprocessed data.
 - **data_input_dir**: change to match **preprocessing_output_dir**.
 - **aigt_repo_path**: change to location of aigt repo clone. 

Also note that other variables like **test_idx** must be altered to run the code on the small sample (ie change to test on only one participant), and that running the full classifier requires having a fully trained U-Net saved from *CentralLine_PoseClassifier*.


