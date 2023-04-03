## Run Test_multi.py:  TypeError: conv2d()
In python3, / produces a float value, but cov2d requires an int, so simply change/to // : in the ssim source package and run it to fix the problem.

![Image.tiff](https://res.craft.do/user/full/96d960c8-ed2d-4efa-a7c9-40529dc9e545/doc/FF331851-53BD-4224-9B86-56D63B4A6D9A/83E68D32-C566-4B76-87CA-AEC6B27AC6DD_2/KMzH7WpUZRTp4WGsQc879cxMKVB4d0RxBQfSr4wgI4wz/Image.tiff)

## Use GPU to creat a virtual env
https://blog.csdn.net/sdnuwjw/article/details/112448792
conda create --prefix ./envs/UIE-WE_env python=3.7

conda config --show envs_dirs

查看目前虚拟环境路径

conda env list
现有环境

conda config --append envs_dirs your_path
添加环境路径

rm -rf yourpath
删除路径

source activate 环境名称
## wget download large file
$ ps -eaf | grep [w]get 
saml      1713  1709  0 Dec10 pts/0    00:00:00 wget ...
$ kill 1713

## ModuleNotFoundError: No module named 'pytorch_ssim'
just pip install it

## 将Variable迁移到显存中去
https://blog.csdn.net/qq_34018578/article/details/109314889

.cuda()操作默认使用GPU 0也就是第一张显卡来进行操作。当我们想要存储在其他显卡中时可以使用.cuda(<显卡号数>)来将数据存储在指定的显卡中。

## 使用wget命令下载Google drive上的文件
https://codeantenna.com/a/ZFm2V6jPHS

## 在搭建环境时需要pip install -r requirements.txt，其中xxx无法自动安装
conda install -c intel xxx
