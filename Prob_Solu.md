## Run Test_multi.py:  TypeError: conv2d()
Solu: In python3, / produces a float value, but cov2d requires an int, so simply change/to // : in the ssim source package and run it to fix the problem.

https://img-blog.csdnimg.cn/3e09b7d1eeeb413498afcd420e58f7ab.png?x-oss-process=image/watermark,type_d3F5LXplbmhlaQ,shadow_50,text_Q1NETiBAeW91bmdodXVw,size_20,color_FFFFFF,t_70,g_se,x_16![image](https://user-images.githubusercontent.com/70552149/201464579-2a48c23a-a725-4bb5-abeb-d3dc79afe301.png)
