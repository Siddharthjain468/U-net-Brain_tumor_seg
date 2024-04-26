**Dataset used** - [Brats_2020](https://www.kaggle.com/datasets/awsaf49/brats20-dataset-training-validation) <br/>
**Model** - U-net

The below folder will contain output files, you will have to configure inout file path yourself according to download names
before compilation fo code make sure you make the following folders:-<br/>

Folder guide:<br/>

..
BraTS2020_TrainingData<br/>
├── input_data_128          # Store sliced and splitted data (70%, 20%, 10%)<br/>
└── input_data_3channels    # Store loaded data<br/>
&nbsp;    ├── masks               # Folder for masks<br/>
&nbsp;    └── images              # Folder for images<br/>
