# dog-breeds-image-classifier

This project demonstrates the usage of existing pre-trained image classifier to determine whether a given image is a dog and if it is, to correctly identify its' breeds.

We are using deep learning model called Convolutional Neural Network (CNN) and we have compared three different architectures (AlexNet, VGG, and ResNet) in this project.

## Running the project

To run the project, simply run the following command:
```
./run_models_batch.sh
```
What the command does is that it will run three existing pre-trained image classifiers against images in `pet_images` folder and it will output the results in three files (alexnet_pet-images.txt, resnet_pet-images.txt, vgg_pet-images.txt) for comparison.
