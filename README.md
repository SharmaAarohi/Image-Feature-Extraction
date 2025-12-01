# Image-Feature-Extraction
Load CIFAR-10 dataset of images. For each image file, extract: HOG, SIFT, color histogram, etc. For each image file, use pre-trained VGG16 architecture to obtain image features. Concatenate handcrafted and deep learning based features. Train a RandomForestClassifier and LogisticRegression on the features. Show results through visualization plots.
