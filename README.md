# qoi2-bikeshed

QOI (the "Quite OK Image" format for fast, lossless image compression) was
announced in November 2021:

- https://phoboslab.org/log/2021/11/qoi-fast-lossless-image-compression
- https://github.com/phoboslab/qoi

It attracted a lot of interest and suggested changes. The performance /
compression numbers were impressive! Shortly afterwards, the author declared
["the data format is now
fixed"](https://github.com/phoboslab/qoi/issues/37#issuecomment-980789466)
(fixed meaning unchanging, not unbroken), as they were absolutely entitled to
do.

This placeholder repository (and in particular, its GitHub issue tracker) is an
*unofficial* place to continue those bike-shedding discussions - a possible
"QOI version 2".  No promises are made about whether those discussions actually
result in anything.

Please file separate issues for separate concerns. For example,

- Issue #1 tracks overall status.
- Issue #2 tracks adding a version number (or equivalent) to the header.
- Issue #3 tracks big-endian vs little-endian.
- When adding new issues (in the GitHub web UI), there's no need to update this
  README.md file.
