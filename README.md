# Introduction

isGrafLab (Irregular Surface GRAvity Field LABoratory) is a modified version of
[GrafLab](https://github.com/blazej-bucha/graflab) to perform accurate and fast
computation of functionals of the geopotential at dense grids residing on
irregular surfaces such as the Earth's surface. It employs the lumped
coefficients approach for surface spherical harmonic synthesis of gravity field
quantities and their vertical derivatives at regular surfaces (sphere or
ellipsoid of revolution), and then it continues the quantities to the irregular
surface using the Talor series.


# Documentation

If you want just a brief introduction to isGrafLab, see
[docs/user-manual.md](docs/user-manual.md).

Detailed isGrafLab cookbook is available at
[https://github.com/blazej-bucha/graflab-cookbook](https://github.com/blazej-bucha/graflab-cookbook).

The equations implemented in isGrafLab can be found in the documentation of
[GrafLab](https://github.com/blazej-bucha/graflab) (see the `docs` folder
therein).


# Contributing

Contributions of any kind are welcome!


# Contact

Feel free to contact the author, Blazej Bucha, at blazej.bucha@stuba.sk.


# Citing

If you use isGrafLab in your work, please consider citing our paper on
isGrafLab.

* Bucha, B., Janák, J., 2014.  A MATLAB-based graphical user interface program
  for computing functionals of the geopotential up to ultra-high degrees and
  orders: Efficient computation at irregular surfaces.  Computers & Geosciences
  66, 219-227,
  [https://doi.org/10.1016/j.cageo.2014.02.005](https://doi.org/10.1016/j.cageo.2014.02.005)


# Other related projects

* [CHarm](https://github.com/blazej-bucha/charm): C library for spherical
  harmonic transforms up to high degrees (tens of thousands and beyond).
  Supports OpenMP parallelization for shared memory architectures and
  vectorized CPU instructions (AVX, AVX2, AVX-512).

* [GrafLab](https://github.com/blazej-bucha/graflab) (GRAvity Field
  LABoratory): GrafLab (GRAvity Field LABoratory) is a MATLAB-based routine to
  compute functionals of the geopotential up to high degrees (tens of thousands
  and beyond)..


# Disclaimer

isGrafLab is an old project that breaks almost all of the best practices in
terms of coding and documenting standards. Nonetheless, the package seems to
work correctly, it has been thoroughly tested and the computation speed is
reasonable (as far as it is possible in MATLAB). Hoping it might still be
useful to others, isGrafLab remains being publicly available.

