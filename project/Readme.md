Hi Kaustab/Dr.Kaeli,

Our whole project was compiled, trained and tested using Jupyter Notebook using Anaconda Navigator for the local machine which has 1 NVIDIA GPU.

For multi-GPU, we used Google Cloud Platform by creating the instance in the Oregon -USA location which is the only location has GPU's. For this project, we used NVIDIA T100 for our notebook to train and test.

So, I'm writing the instructions for you test this project in your local or GCP environment.

Firstly, each workloads and datasets are uploaded to my github link : bit.ly/bit.ly/hpcproject5640goutham 

The dataset is about 10.5GB. After downloading it inton your local machine, kindly install all the neccesary libraries for this project and they are:

conda install -c conda-forge keras
pip install git+https://github.com/qubvel/efficientnet
pip install git+https://github.com/qubvel/classification_models.git
pip install git+https://github.com/qubvel/segmentation_models
pip install git+https://github.com/albu/albumentations
pip install tta-wrapper

After successfully installing all the above mentioned extra and required libraries, run the .ipynb files in the suitble environment.

Run time : tf_road.ipynb << pytorch.ipynb for single GPU as well as Multi-GPU.

Hope, we have executed our proposal work as what we have promised, and successfully made the performance differentiation between the GPU's used as mentioned for A grade.

Most importantly we learnt a lot about GPU and its uses by doing this project.
Thank You!

