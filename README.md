# RestrictProlong

[![Build Status](https://travis-ci.org/timholy/RestrictProlong.jl.svg?branch=master)](https://travis-ci.org/timholy/RestrictProlong.jl)

[![codecov.io](http://codecov.io/github/timholy/RestrictProlong.jl/coverage.svg?branch=master)](http://codecov.io/github/timholy/RestrictProlong.jl?branch=master)

This package provides efficient multidimensional implementations of
two operators, `restrict` and `prolong`, which feature heavily in
multigrid methods. In general terms, these operations reduce and
increase, respectively, the size of arrays by a factor of 2 along one
or more dimensions.  The two operators satisfy the "Galerkin
condition," meaning that as operators they are transposes of one
another.

In addition to being useful for mulitigrid methods, `restrict` can be
used as a fast antialiasing thumbnail generator for images.
