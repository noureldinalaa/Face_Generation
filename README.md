[//]: # (Image References)

[image1]: ./assets/processed_face_data.png "Processed CelebA face data"
# Face_Generation
Generate images of new and realistic human faces using CelebA dataset (This Project is part from Udacity's deep learning nanodegree).

## Project Overview
In this project, we will define and train a DCGAN(Deep Convolutional Generative Adversarial Networks) on a dataset of faces. our goal is to get a generator network to generate new images of faces that look as realistic as possible!


![Processed CelebA face data][image1]

## Project Instructions

### Instructions

1. Clone the repository and navigate to the downloaded folder.
	
	```	
		git clone https://github.com/noureldinalaa/Face_Generation.git
		cd Face_generation   
	```
2. Download the [CelebFaces Attributes Dataset (CelebA)](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html).Unzip the folder and place it in the repo.

3. Install packages like pytorch and torch vision and some pip packages in requirements text file :
	```
		conda install pytorch torchvision -c pytorch
            pip install -r requirements.txt
	```
4. Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.
	
	```
		jupyter notebook dlnd_face_generation.ipynb
	```

