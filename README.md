# SIN393_Introduction-to-computer-vision_2023


## Creating a conda environment for the course
---

* Windows - without GPU.
```
    $ conda create -n env-sin393-py39 python=3.9
    $ conda activate env-sin393-py39

    $ pip install notebook
    $ pip install matplotlib
    $ pip install scikit-image
    $ pip install scikit-learn
    $ pip install pandas
    $ pip install ipympl

```

* Linux - with GPU.

```
    $ conda create -n env-sin393-gpu-py39 python=3.9
    $ conda activate env-sin393-py39

    $ conda install pytorch torchvision torchaudio pytorch-cuda=11.7 -c pytorch -c nvidia
    $ conda install chardet

    $ pip install scikit-image
    $ pip install matplotlib
    $ pip install scikit-learn
    $ pip install notebook

```

