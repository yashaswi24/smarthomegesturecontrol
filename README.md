SmartHome Gesture Control Application PART-2
A python application classifying Smart Home gestures using CNN model.


Steps:

1. Creating training and testing folders with videos and are imported to main.py file.
2. Using FrameExtractor Method, to extract middle frame from all videos and store them as train and test frames
3. Creating Penultimate layer which are feature vectors used to define a frame and are used in further evaluation.
4. Using cosine similarity, we calculate similar gesture for each test data and gesture number is stored in Results file.

