# inz
Image Recognition for Traffic Analysis

# Notes for me (will clean up this readme later)

## environment set-up

conda create --name inz python=3.10

conda install -c conda-forge cudatoolkit

pip3 install torch torchvision --index-url https://download.pytorch.org/whl/cu118

pip install notebook

pip install ipykernel

ipython kernel install --user --name=inz

pip install ultralytics

pip install supervision==0.7.0

conda install -c conda-forge lap
pip uninstall numpy
pip install numpy==1.24.1

pip install plotly
