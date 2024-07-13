This project utilizes YOLO (You Only Look Once) for detecting defects in engine gaskets through image inspection.

Project Structure
├── data.yaml ├── index.py ├── model.pt ├── output.jpg ├── train_file.ipynb ├── test │ ├── images │ └── labels └── train ├── images └── labels

data.yaml: Configuration file for the YOLO model.
index.py: Python script for running defect detection using YOLO.
model.pt: Pre-trained YOLO model file.
output.jpg: Sample output image showing detected defects.
train_file.ipynb: Jupyter notebook for training the YOLO model.
test/: Directory containing test images and labels.
train/: Directory containing training images and labels.
Getting Started
Running the Program
Clone the repository:

git clone https://github.com/your_username/your_repository.git
cd your_repository
Install dependencies:

Ensure you have Python and pip installed. Install required packages:

pip install ultralytics opencv-python
Detect defects using pre-trained model:
Run the index.py script to perform defect detection using the pre-trained YOLO model:

python index.py
By default, the script uses the webcam (source="0"). Modify source parameter in index.py if using images or videos.

Training the YOLO model:
Use the train_file.ipynb notebook to train the YOLO model. Make sure to follow the instructions within the notebook to specify the correct paths and configurations.
