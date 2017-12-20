Author : Sumedh Vilas Datar
------

Language Used : Python 3.5
-------------

Dependent Libraries : OpenCV, Tensorflow, Point Cloud Library, Numpy , Scipy, Pointlet
--------------------

A. Data Acquisation
------------------

1. Input either a pair of images or a video.
2. Break down the video into frames.
3. Pass the frame through a method called generate_3d_points
4. Get 3d points in a file which is of format .ply.
5. If required visualize the 3d points using meshlab software.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

B. Training
   --------
Used the train.py file provided by pointnet.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------

C. Prediction
   ----------

1. Read the 3d points from .ply file.
2. Convert the 3d points to poitcloud data using pc_utils which converts 3d points to pointcloud numpy array.
3. Create a tensorflow session as already shown in the pointnet python code.
4. Give the point cloud points as input to the network and get the predicted output from the network 

----------------------------------------------------------------------------------------------------------------------------------------------------------------------