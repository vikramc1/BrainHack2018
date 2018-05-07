# BrainHack2018

During BrainHack2018, with Josh Vogelstein and the neurodata lab, I made a goal to implement deformable image registration via Large Deformation Diffeomorphic Metric Mapping (LDDMM) in tensorflow.

It was first necessary to write functions to do linear interpolation at arbitrary points.  It was also necessary to write a function that takes the gradient of an image.

I have implemented it in 2D and 3D.

So far formatted as ipython notebook.  All data to run notebooks is included in the repo.  This includes two human brain mri images

Note about running python notebook with tensorflow.

Install tensorflow

virtualenv --site-packages -p python3 ~/tensorflow
source ~/tensorflow/bin/activate
pip install --ignore-installed ipython
pip install --ignore-installed jupyter

Double check with

jupyter kernelspec list

If this is not pointing to the version of python in your virtualenv, then delete the wrong kernel.

e.g.

jupyter kernelspec remove python3

Then it should point to the one you just installed.


