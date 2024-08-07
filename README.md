# About
This project is a waste sorting project built with ResNet34 and YOLO v8.

# How to run the project
## Using your local machine
1. Clone this repository by using the command `https://github.com/haingo-raz/Computer-Vision-Waste-Sorting-System.git`.
1. Install the required libraries by running `pip install -r requirements.txt`.
1 Run the notebook file `Computer_Vision_Waste_Sorting_v3.ipynb` to download the dataset from Kaggle and create the ResNet34 model.
1. Run the notebook file `Live_Waste_Sorting_Label.ipynb` to test the system on a local video. The default video it uses to test is the `tet_sort2.mp4` in this repository.

## Using Google Colab
1. Upload the `inference-images` folder and the videos for testing, such as `test_sort2.mp4`.
1. Run the notebook file `Computer_Vision_Waste_Sorting_v3.ipynb` to download the dataset from Kaggle and create the ResNet34 model.
1. Run the notebook file `Live_Waste_Sorting_Label.ipynb` to test the waste sorting system on a local video. The default video it uses to test is the `test_sort2.mp4` in this repository.
