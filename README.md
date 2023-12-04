# Face-Classification
COEN 240 - Machine Learning Final Project 

How to Run ALL the files - 

1 - First run Data_Modification.ipynb to augment the data.

    give your rispective file path in the last block of the notebook that look like this-
    input_directory = "yourpath"
    output_directory = "yourpath"
    # Call the main function 
    main(input_directory, output_directory)

2 - Now to run the Facenet and VGG model files in collab do the following - 

    1 - give your augmented data and test data path in below code as well path for saving the model 

        TRAIN_DIR = "/content/drive/MyDrive/DATA/Outputt/face"
        TEST_DIR = "/content/drive/MyDrive/DATA/Test_dataset/final"
        MODEL_DIR = '/content/drive/MyDrive/DATA/Models'

    2 - give label.txt file path in this below code in notebook when loading the data 

    # Load data
    print("LOADING DATA ...")
    train_data, train_labels = load_data_from_dir(TRAIN_DIR)
    test_data, test_labels = load_test(TEST_DIR,'your labels.txt path')
    print("Completed")






