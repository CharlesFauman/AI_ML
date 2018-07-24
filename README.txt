
# packages to install:
# note: we install keras 2.1 because 2.1.5 and above have an error using softmax
# note: we install tensorflow 1.7 because 1.8 and above have an error using tensorboard with gpu

python -m pip install --upgrade pip
pip install tensorflow==1.7 keras==2.1 jupyter numpy scipy scikit-learn gym matplotlib h5py


# how to run:
> cd AI_ML
> jupyter notebook
> jupyter trust

# go to keras mnist and run the notebook
