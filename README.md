# modimport
This module import `my.com/modoriginal` with a replace to point to `github.com/shou1dwe/modoriginal` repository.

For v0/v1 use case, this works fine; but if `modoriginal` decides to bump the version to v2 or beyond on its main branch, the `replace` directive won't work.
