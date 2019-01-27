## Face generator project

This is a project about generating human faces which was done while completing nanodegree program on deep learning at Udacity.
The method uses small convolutional network to generate faces.

__To see the results just download and open the dlnd_face_generation.html file.__

To run the Jupyter notebook do the following
1) Clone the repository
2) Install install [`miniconda`](http://conda.pydata.org/miniconda.html) on your computer.
3) Create a new `conda` [environment](http://conda.pydata.org/docs/using/envs.html), for example face-generator
	- __Linux__ or __Mac__: 
	```
	conda create -n face-generator python=3.6
	source activate dog breed
	```
	- __Windows__: 
	```
	conda create --name face-generator python=3.6
	activate face-generator
4) Install PyTorch and torchvision; this should install the latest version of PyTorch.
	
	- __Linux__ or __Mac__: 
	```
	conda install pytorch torchvision -c pytorch 
	```
	- __Windows__: 
	```
	conda install pytorch -c pytorch
	pip install torchvision

5) Install a few required pip packages, which are specified in the requirements text file (including OpenCV).
```
pip install -r requirements.txt
```

6) Run jupyter notebook from command line in face-generator-detection folder.

Please let me know if there are problems with the installation!

