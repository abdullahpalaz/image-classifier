## Image Classifier

This assignment is done for Introduction to Computer Vision class.
Aim of this assignment is to classify images with CNN and with Transfer Learning of VGG16.
You may find the instructions of this assignment in Assignment Instruction.pdf.

You may find the dataset in [this link](https://www.kaggle.com/datasets/itsahmad/indoor-scenes-cvpr-2019)

WARNING! - YOU MUST DELETE THE FOLLOWING FILES FROM DATASET - WARNING!
because cv2 imread does not read them.

REMOVED IMAGES:
	corridor\Corridor_gif.jpg
	corridor\down_corridor_frame_gif.jpg
	livingroom\salon28_gif.jpg

Note: You might use only the classes mentioned in report or all of the dataset. Results
wont change since code uses classes with at least 300 images.


Necessary file hierarcy:

+-- Image Classifier.ipynb  
+-- dataset  
|   +-- class-1  
|       +-- image-1  
|       +-- image-2  
|       +-- ...  
|       +-- image-(n-1)  
|       +-- image-n  
|   +-- class-2  
|       +-- image-1  
|       +-- image-2  
|       +-- ...  
|       +-- image-(n-1)  
|       +-- image-n  
|   +-- ...  
|       +-- image-1  
|       +-- image-2  
|       +-- ...  
|       +-- image-(n-1)  
|       +-- image-n  
|   +-- class-n  
|       +-- image-1  
|       +-- image-2  
|       +-- ...  
|       +-- image-(n-1)  
|       +-- image-n  
