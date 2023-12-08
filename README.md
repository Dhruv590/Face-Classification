# Face-Classification
COEN 240 - Machine Learning Final Project 

How to Run ALL the files - 

1 - First run Data_Modification.ipynb to augment the data.

    -> give your rispective file path in the last block of the notebook that look like this-
    
    input_directory = "/content/drive/MyDrive/COEN 240/Release-2"
    output_directory = "/content/drive/MyDrive/COEN 240/train"
    # Call the main function 
    main(input_directory, output_directory)

2 - Now to run the Facenet and VGG model files in collab do the following - 

    -> give your augmented data and test data path in below code as well path for saving the model 

        TRAIN_DIR = "/content/drive/MyDrive/COEN 240/train"
        TEST_DIR = "/content/drive/MyDrive/COEN 240/test"
        Labels_txt = "/content/drive/MyDrive/COEN 240/test/labels.txt"
        MODEL_DIR = '/content/drive/MyDrive/COEN 240/Models'






