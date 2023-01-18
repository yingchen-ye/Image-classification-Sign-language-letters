# Image-classification-Sign-language-letters-
Course: Machine Learning
The dataset is Sign Language MNIST (https://www.kaggle.com/datasets/datamunge/sign-language-mnist).
The original MNIST image dataset of handwritten digits is a popular benchmark for image-based machine learning methods but researchers have renewed efforts to update it and develop drop-in replacements that are more challenging for computer vision and original for real-world applications.
The dataset format is patterned to match closely with the classic MNIST. Each training and test case represents a label (0-25) as a one-to-one map for each alphabetic letter A-Z (and no cases for 9=J or 25=Z because of gesture motions). The training data (27,455 cases) and test data (7172 cases) are approximately half the size of the standard MNIST but otherwise similar with a header row of label, pixel1,pixel2….pixel784 which represent a single 28x28 pixel image with grayscale values between 0-255. 
# Tasks
## Task 1: The first task is to train two models to recognize sign language letters and compare their performances.
- Logistic regression and CNN were trained.

## Task 2: use the classifiers trained in the first task to identify a series of n sign language letters in an image of size 28 × 200. $n$ can take values in the range [1, 5] randomly.
