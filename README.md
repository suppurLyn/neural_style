# neural-style

An implementation of ["neural style"](http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf) in TensorFlow. 
Here, you can find ["a faster versoin"](http://cs.stanford.edu/people/jcjohns/papers/eccv16/JohnsonECCV16.pdf)

## Running 
`python neural_style.py --content <content file> --styles <style file> --output <output file>`

## Requirements

* [TensorFlow](https://www.tensorflow.org/versions/master/get_started/os_setup.html#download-and-setup)
* [NumPy](https://github.com/numpy/numpy/blob/master/INSTALL.rst.txt)
* [SciPy](https://github.com/scipy/scipy/blob/master/INSTALL.rst.txt)
* [Pillow](http://pillow.readthedocs.io/en/3.3.x/installation.html#installation)
* [Pre-trained VGG network]() put it in the top level of this repository

Just for fun ~
