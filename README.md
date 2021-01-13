# Kernel-adaptive-filtering-in-python
Kernel method is one of the most popular method in the area of adaptive filtering and signal
processing. The reason behind this is the combination of the famed kernel trick and the adaptive
filters (like Least Mean Squares(LMS) and Recursive Least Squares(RLS)) algorithm provides an
interesting sample-by-sample update for an adaptive filter in reproducing kernel Hilbert spaces
(RKHS). Instead of calculating the higher dimensional values in the feature space, the Kernel
methods (namely KLMS and KRLS) make use of a mathematical result more popularly known as
Kernel Trick. The basic idea of Kernel Trick is that a Mercer kernel function which is applied to
pairs of input vectors, can be interpreted as an inner product in a high-dimensional feature space
(more formally called Hilbert space), thus allowing inner products in the feature space to be
computed without making direct reference to feature vectors.
This idea has been used extensively in recent years, most notably in classification and regression. In
this project, we will try to implement this kernel trick on adaptive filters to solve the non-linear
prediction problems using linear regression based predictive filters. Also we will compare the effect
of various parameters on the performance of kernel filters.
