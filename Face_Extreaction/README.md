
### Ground truth Image Annotaed by VoTT

download link: https://drive.google.com/file/d/1QordJygcmukgVC7rGl1nhFI1IK1Yfj_V/view?usp=sharing

In order for our detector to learn to detect objects in images, such as cat faces in pictures for our case, YOLO needs to be fed with labeled training data. Therefore, we need to manually label cat faces for 100 selected images from our training images without replacement as ground truth images.

To label images, we used Microsoft’s Visual Object Tagging Tool (VoTT). On VoTT, we drew bounding boxes around cat face objects. Once we have labeled all selected images and export them, we will have a folder including a CSV file called Annotations-export.csv, which contains file names and bounding box coordinates of the cat face objects. This is how we generate our ground truth data, which will be used for later image inference and evaluation.

### code of face extraction using YOLOv3 has been shown in file: FaceExtraction&Evaluation.ipynb

### outputs of the code are saved in /outputs folder.
