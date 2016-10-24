wait [![Build Status](https://travis-ci.org/fortytw2/wait.svg?branch=master)](https://travis-ci.org/fortytw2/wait) [![codecov](https://codecov.io/gh/fortytw2/wait/branch/master/graph/badge.svg)](https://codecov.io/gh/fortytw2/wait)
------

`wait` is an extraction of the kubernetes exponential backoff and wait functionality
into an independently re-useable, zero-dependency package.

The most notable difference from the kubernetes library is that `wait` makes
no provisions for handling panic recovery within its functions, instead relying
on the caller to do so, if needed.

LICENSE
-----
Apache, see LICENSE
