## 3.0.0

* Remove unnecessary `rresult`
* Remove `failwith`
* Add `Unknown` to `t_abi` and other sum types
* Avoid [compiler issues](https://github.com/owlbarn/eigen/issues/38) by
  defaulting to `Unknown` in the C header

## 2.0.0

* Add `Linux_x86`.
* Switch from `(t_os, Rresult.msg) result` to `(t_os, string) result` (ditto for `t_abi`).

## 1.0.0

Internal version.
