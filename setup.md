# Create a python 3 bases virtual env
python3 -m venv tensor-env
source tensor-env/bin/activate

# Download the source repo
git clone git@github.com:madhurnawandar/Object-Detection-and-Distance-Measurement.git
cd Object-Detection-and-Distance-Measurement/

# Download the model
Download the file yolov3.weights from 
 https://drive.google.com/drive/folders/1nN49gRqt5HvuMptfc0wRVcuLwiNmMD6u
and replace the he existing file in the folder

# Install python dependencies
pip install -r requirements.txt

# Run
python object_detection.py
