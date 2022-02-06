# custom-object-detection-helmet

Step 1: Clone yolov5 repository using git clone method.

Step 2: Training is done using google colab with tesla k80 gpu using the train.py file associated with yolov5

Step 3: Best weight from trained model is downloaded and used in jupyter notebooks for detecting helmets

We use Pytorch for training and detecting the model.

The model isn't fully developed, it doesn't have accuracy, any suggestions and improvements towards the model are welcomed.

Dataset Collection:

Images are collected from google and kaggle and are annotated using Roboflow
The model is downloaded and trained using the api key, the same model is uploaded as 2 zipped files here in the document to view the dataset.
This is my first custom trained dataset using yolo model.
