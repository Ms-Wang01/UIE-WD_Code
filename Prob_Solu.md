## Run Test_multi.py:  TypeError: conv2d()
Solu: In python3, / produces a float value, but cov2d requires an int, so simply change/to // : in the ssim source package and run it to fix the problem.

