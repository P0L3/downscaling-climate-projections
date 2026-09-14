``` shell
conda create -n m2_dcp python=3.11

conda activate m2_dcp

pip install -r requirements.txt

conda install -n m2_dcp ipykernel --update-deps --force-reinstall -y

# pip install --ignore-installed torch==2.14.0 --index-url https://download.pytorch.org/whl/cu126 # For GPU poor (works on GTX 1050 Ti)
```