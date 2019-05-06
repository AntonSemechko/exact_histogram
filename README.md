# Exact Histogram Specification & Equalization of Grayscale Images

Histogram equalization is a traditional image enhancement technique which aims to improve visual appearance of the image by assigning equal number of pixels to all available intensity values. Histogram specification is a generalization of histogram equalization and is typically used as a standardization technique to normalize image with respect to a desired probability mass function or properties such as mean intensity, energy and entropy. Unlike classical histogram specification, exact histogram specification algorithm implemented here is able to modify the histogram of any image almost exactly (see snapshot).

The .m file `exact_histogram.m` is an implementation of an exact histogram specification algorithm described in:

[**[1]**] Coltuc D. and Bolon P., 1999, "Strict ordering on discrete images and applications", Proceedings 1999 International Conference on Image Processing
[**[2]**] Coltuc D., Bolon P. and Chassery J-M., 2006, "Exact histogram specification", IEEE Transcations on Image Processing 15(5):1143-1152

For a quick demo enter `demoHS` into Matlab command window. 
To access additional information regrading function enter: `help exact_histogram`

## License
[MIT] © 2019 Anton Semechko 
a.semechko@gmail.com

[1]: https://doi.org/10.1109/ICIP.1999.817089
[2]: https://doi.org/10.1109/TIP.2005.864170
[Image Processing Toolbox]: https://www.mathworks.com/products/image.html
[MIT]: https://github.com/AntonSemechko/Fast-Fuzzy-C-Means-Segmentation/blob/master/LICENSE.md