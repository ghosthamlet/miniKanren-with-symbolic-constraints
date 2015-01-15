# miniKanren-with-symbolic-constraints

The version of miniKanren I normally use.  Includes `==`, `=/=`, `symbolo`, `numbero`, generalized `absento` constraints.

Good for writing Quine-generating interpreters, etc.  :)

Also includes `eigen`, which represents universally quanitifed variables.  Beware:  this implementation does *not* support use of `eigen` with constraints other than `==`.

Also includes multi-query variable version of `run`.  For example, `(run (q r s) (== `(,r ,q) s))`.
