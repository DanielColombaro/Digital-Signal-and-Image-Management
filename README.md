# Digital-Signal-and-Image-Management

This folder contains the following documents:

* For the Image Classification task we developed four different Colab notebooks, each one for a different pre-trained Model:
  * Classification_MobileNet.ipynb
  * Classification_ResNet.ipynb
  * Classification_VGG.ipynb
  * Classification_FE.ipynb
* For the Image Retrieval task we developed a single Colab document: 
  * Image_Retrieval_MobileNet.ipynb
* For the Audio Classification task we create a folder with:
  * DSIM Audio Classification.ipynb the Colab document with the implementation of the neural network for the Audio Classification.
  * “labels_oversampled_train.pkl“containing the label, which is 1 if the audio data belongs to a native English speaker, and 0 if it doesn't belong to a native English speaker, for the entire train set after oversampling.
  * “labels.pkl”, a list of all the nationalities present.
  * “mfcc_oversampled_train.pkl” containing all the MFCC arrays of the train set with oversampling.
  * “mfcc_padded_test.pkl”  containing all the MFCC arrays of the test set with oversampling.
  * “mfcc_padded_train.pkl” similar to d., containing all the MFCC arrays of the training set but without oversampling.
  * “temp_audio_file_original” and “temp_audio_file.wav ” are the audio files temporarily created by the Demo and based on user selection.
  * “cnn_model_final”  the saved convolutional neural network model.

* For the DEMO we create a single file:
  * DEMO.ipynb containing the three different demo for each task. Interactive Snippets referred to specific task should be executed immediately after the corresponding preparation functions to avoid conflicts between different demos during execution.
* Three subfolders:
  * “MSRA-CFW” which contains the dataset used for image retrieval. The dataset is extracted from the thumbnails_features_deduped_publish.zip.
  * “test” used during the classification task demo. Inside, there are three folders: defocused_blurred, motion_blurred, and sharp, containing the images to test the performance of the best model. 
  * “vip_drive” which contains a subset of the original dataset used for Image_Retrieval Task.

* Files for extracted features in the Image Retrieval task:
  * cropped_images.npz contains the cropped images.
  * features_mobilenet_crop.npz contains the folders where the extracted features for Retrieval with Cropping are saved
  * features_mobilenet.npz contains the folders where the extracted features are saved (for Retrieval without Cropping)
* Classification models trained:
  * MobileNet.h5
  * resnet.h5
* Presentation of the project in PDF






