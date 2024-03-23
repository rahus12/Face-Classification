# Face Classification

## Methodology
The notebook performs 4 steps:
1. Data preprocessing: which involves data augmentation and data filtering using a face detector
2. Feature extraction: We use PCA along with LDA as a way to extract features and reduce dimensions in the data
3. Model training: The pipline model consisting of PCA, LDA and SVM are trained and fitted on the data

## Folder directory used
root:
- raw_training_data
- raw_testing_data
- Augmented_images

## Execution steps:
1. Change the values of directories as per your own location
2. Run all the code blocks in the notebooks

## Data
Can be of either form:
1. The data can either be seperated and present in different folder with folder name being the Label for all images in that folder
2. One folder containing all images, and a text file containing the filemapping to these which has image_name  label (space seperated)

If using the first version of data structuring, then Keep the value of Keras = Flase, else True

