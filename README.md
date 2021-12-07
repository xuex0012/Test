# Test
just a test
---
tags: [TUTO]
title: MAGICAL Installation
created: '2021-12-07T07:11:17.685Z'
modified: '2021-12-07T08:41:11.921Z'
---

# MAGICAL Installation

## Install Anaconda3

- [ ] Install Anaconda3 following the official website [anaconda](https://www.anaconda.com/products/individual)
- [ ] Create a python environment for MAGICAL installation [how-to-create-anaconda-environment](https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/20/conda/) 
  it is recommended to use python3.8

### how to install C libraries with anaconda

1. activate your anaconda environment
2. search the library you want to install on [anaconda](https://anaconda.org/)

![image-20211207165505357](/home/xiaohan/.config/Typora/typora-user-images/image-20211207165505357.png)

2. Follow the guide, e.g. install zlib with `conda install -c conda-forge zlib`

![image-20211207165610868](/home/xiaohan/.config/Typora/typora-user-images/image-20211207165610868.png)

## Install Limbo

- [ ] Install required dependencies with anaconda for LIMBO [dependency](https://github.com/limbo018/Limbo#installation)
- [ ] Install Limbo following guide [limbo](https://github.com/limbo018/Limbo#1-default-installation)
- [ ] Set environment variable `LIMBO_DIR` [how-to-set-environment-variable](https://linuxize.com/post/how-to-set-and-list-environment-variables-in-linux/)

## Install Other Dependencies

- [ ] Install required dependencies with anaconda, refer to dependencies claimed in [dependency](https://github.com/magical-eda/MAGICAL/tree/docker#dependency) or [dependency](https://github.com/magical-eda/MAGICAL/blob/docker/Dockerfile)

## Install MAGICAL

- [ ] Do not forget to activate your anaconda environment
- [ ] Install **ConstGen**: Go to `ConstGen` directory, run `python setup.py install`
- [ ] Install **device_generation**: Go to `device_generation` directory, run `python setup.py install`
- [ ] Install **IdeaPlaceEx**: Go to `IdeaPlaceEx` directory, run `python setup.py install`
- [ ] Install **anaroute**: Go to `anaroute` directory, run `python setup.py install`
- [ ] Install **magicalFlow**: Go to `flow/cpp/magical_flow` directory, run `python setup.py install`

### mvimagical common q&a

1. do not forget to clone submodules [submodule](https://github.com/magical-eda/MAGICAL/tree/docker#how-to-clone)
2. do not forget to test if you have installed, run following the guide [run](https://github.com/magical-eda/MAGICAL/tree/docker#how-to-run)
   it is recommended to test `ota2`

