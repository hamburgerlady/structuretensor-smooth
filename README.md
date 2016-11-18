# structuretensor-smooth
Matlab/mex implementation of non-isotropic image smoothing using kernels based on the structure tensor as described in 
"Characterizing the Structure Tensor Using Gamma Distributions"
M. Oskarsson in proc ICPR'16

The main function is structure_smooth.m 
imout = structure_smooth(im,s)
imout is the smoothed output image
im is the input image, and s is the estimated standard deviation of the noise in the image
