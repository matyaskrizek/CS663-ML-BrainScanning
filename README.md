# CS663-ML-BrainScanning
ML project for cs663, scans images of brain tumors and classifies them as having a MGMT promoter (a specific gene that responds well to chemotherapy) or not.


![image](https://user-images.githubusercontent.com/54570008/160933329-742a6655-893b-4174-97d8-057aa9e8522e.png)


The Preprocessing notebook contains all the code to pre-process the images, gray scale, crop, and remove images with no data, and stores them into two csv files, test and train images.

The Modeling notebook takes the given data, reformats it into 3d images, but only of size 50px x 50 px x 20 images, which is not a whole scan of a brain, but just a smaller subsection, and feeds it int a 3d CNN for modeling.
