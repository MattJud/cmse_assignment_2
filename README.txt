Recommended Operating System: Ubuntu 16.04

1) Install anaconda  https://www.anaconda.com/distribution/#download-section
2) Open anaconda prompt
3) Execute the following commands:
	conda create -n bonus_points2
	conda activate bonus_points2
	conda install python=3.6
	conda install pytorch torchvision cudatoolkit=10.1 -c pytorch
	conda install -c conda-forge matplotlib
	conda install -c anaconda jupyter
	python -m pip install gym
	python -m pip install gym[all] (Windows user: you need swig to build all dependencies of OpenAI gym https://www.youtube.com/watch?v=HDD9QqLtAws , 
	                                Don't care about errors when building mujoco-py, you don't need this)
4) Activate your previously created environment:
	conda activate bonus_points2
3) Start Jupyter Notebook
4) Navigate to the exercises:
	Exercise1.ipynb
	Exercise1.ipynb
Have fun.

!!!Don't forget to save the jupyter notebooks before submitting!!!

Submission:

Deadline: 28.02.2020 11:59:59 pm

1) Compress the complete Assignment2 directory to a zip file.
2) Send your compressed directory to info2@ima-ifu.rwth-aachen.de



