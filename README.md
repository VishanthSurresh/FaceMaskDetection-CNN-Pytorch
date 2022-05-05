# Face Mask Detection using CNN [Pytorch]

![FaskMaskDetection](https://user-images.githubusercontent.com/35566310/166952220-d32aaf0b-edd1-4ea6-8074-c567912ac256.png)

Governments and global health officials alike are entering unchartered territory when it comes to setting guidelines and regulations on how to slow the spread of COVID-19, while also mitigating future potential virus outbreaks. There has been much uncertainty surrounding COVID-19 and how quickly or slowly our lives will return to normalcy. While healthcare professionals and scientists are learning more every day, we know for a fact that the proper use of face masks has proven to
be an effective measure in keeping infection rates from rising again, especially as cities and countries come out of lockdown. Thus Face Mask Detection technique helps to identify, whether people wearing mask or not. This in turn helps government to take necessary actions.

![mask-detection-sample](https://user-images.githubusercontent.com/35566310/166942413-24742dc1-f573-4dd7-a10e-08010a8c525e.jpg)

## 1. Directory Structure and Description

### Dataset Description

	-> Dataset [Directory consisting of training images for training]

		-> No Mask
		-> N95 Mask
		-> N95 with Valve Mask
		-> Surgical Mask
		-> Cloth Mask 
		-> dataset.pickel [Consists of Key value pair]

	-> Testing Dataset [Directory consisting of sample images for predictions]

		-> Random



	-> Applied_AI_Project.ipynb 		- Jupyter Notebook which contains entire code for the project

	-> AI Project Report 			- Detailed report about the project 

	-> Expectations-of-Originality 		- Originality form Signed by all the team members

	-> Final_model_trained.pt 		- Trained Model File 

## 2. Running / Development

The project was developed using Jupyter Notebook. Visit http://localhost:8888/tree in any web browser using Anaconda3. 

## 3. Steps to run the notebook:

The code consists of multiple cells. Functions and classes are declared in Top and training_model is called at very last. Each cell can be executed using Shift + enter and corresponding outputs are shown at the bottom of the cell. We can also run all the code at once using Restart and Run all in Jupyter notebook and Run all option in Google colab. The code we created is executed using RTX 3050 processor which is much faster than Google Colab. 

Note : There might be overfitting if we didnt restart the notebook. So it is highly recommended to restart the kernel when training the data everytime.

## 4. References

We used open source datasets in this project. In addition to that we used MaskTheFace computer vision based script to generate Augmented Images - https://github.com/aqeelanwar/MaskTheFace

![MaskTheFace](https://user-images.githubusercontent.com/35566310/166953093-c50a3d33-df97-4b0d-93b8-ccb7564a640f.png) ![MaskTheFace - Steps](https://user-images.githubusercontent.com/35566310/166953132-8d0db5e5-ecb3-4a8a-bbb4-c5366517fa87.png)


