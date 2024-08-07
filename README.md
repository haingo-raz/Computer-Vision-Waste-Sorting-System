# About
This project is a waste sorting project built with ResNet34 and YOLO v8.

# How to run the project
## Using your local machine
1. Clone this repository by using the command `https://github.com/haingo-raz/Computer-Vision-Waste-Sorting-System.git`.
2. Install the required libraries by running `pip install -r requirements.txt`.
3 Run the notebook file `Computer_Vision_Waste_Sorting_v3.ipynb` to download the dataset from Kaggle and create the ResNet34 model.
4. Run the notebook file `Live_Waste_Sorting_Label.ipynb` to test the system on a local video. The default video it uses to test is the `test_sort2.mp4` in this repository.
5. `Output_video.mp4` will be created to show the bounding box and the classification for the detected objects.

## Using Google Colab
1. Upload the `inference-images` folder and the videos for testing, such as `test_sort2.mp4`.
2. Run the notebook file `Computer_Vision_Waste_Sorting_v3.ipynb` to download the dataset from Kaggle and create the ResNet34 model.
3. Run the notebook file `Live_Waste_Sorting_Label.ipynb` to test the waste sorting system on a local video. The default video it uses to test is the `test_sort2.mp4` in this repository.
4. `Output_video.mp4` will be display on the bottom with the bounding boxes and classification label for detected objects.
