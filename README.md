**Dataset used** - [Brats_2020](https://www.kaggle.com/datasets/awsaf49/brats20-dataset-training-validation) <br/>
**Model** - U-net
before compilation fo code make sure you make the following folders:-
Folder guide:
BraTS2020_TrainingData/input_data_128/
under which you have to make 
.
BraTS2020_TrainingData/input_data_3channels/

BraTS2020_TrainingData/
├── input_data_128            # to store sliced-splitted data (70%, 20%, 10%) /
├── input_data_3channels      # to store loaded data /
│   ├── masks      /
│   ├── images      /       
