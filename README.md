# Object-Detection-using-ImageAI

To perform object detection using ImageAI, all you need to do is
Install Python on your computer system
Install ImageAI and its dependencies
3. Download the Object Detection model file
4. Run the sample codes (which is as few as 10 lines)
Now let’s get started.
1) Download and install Python 3 from official Python Language website
https://python.org
2) Install the following dependencies via pip:
i. Tensorflow
pip install tensorflow
ii. Numpy
pip install numpy
iii. SciPy
pip install scipy
iv. OpenCV
pip install opencv-python
v. Pillow
pip install pillow
vi. Matplotlib
pip install matplotlib
vii. H5py
pip install h5py
viii. Keras
pip install keras
ix. ImageAI
pip3 install imageai --upgrade
3) Download the RetinaNet model file that will be used for object detection via this link (https://github.com/OlafenwaMoses/ImageAI/releases/download/1.0/resnet50_coco_best_v2.0.1.h5).
Great. Now that you have installed the dependencies, you are ready to write your first object detection code. Create a Python file and give it a name (For example, FirstDetection.py), and then write the code below into it. Copy the RetinaNet model file and the image you want to detect to the folder that contains the python file.
FirstDetection.py

Then run the code and wait while the results prints in the console. Once the result is printed to the console, go to the folder in which your FirstDetection.py is and you will find a new image saved. Take a look at a 2 image samples below and the new images saved after detection.
