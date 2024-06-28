# nerfstudio-pro

### Installation

* https://docs.nerf.studio/quickstart/installation.html

```bash
conda create --name nerfstudio -y python=3.8 pip jupyter
conda activate nerfstudio
python -m pip install --upgrade pip
```

* Remove the following packages if they are installed

```
pip uninstall torch torchvision functorch tinycudann
```

* Find CUDA version with `!nvidia-smi`  


```
pip install torch==2.1.2+cu118 torchvision==0.16.2+cu118 --extra-index-url https://download.pytorch.org/whl/cu118
```