# cljsjs/pouchdb

[](dependency)
```clojure
[cljsjs/pouchdb "6.3.4-0"] ;; latest release
```
[](/dependency)

This jar comes with `deps.cljs` as used by the [Foreign Libs][flibs] feature
of the ClojureScript compiler. After adding the above dependency to your project
you can require the packaged library like so:

```clojure
(ns application.core
  (:require cljsjs.pouchdb))
```

[flibs]: https://github.com/clojure/clojurescript/wiki/Packaging-Foreign-Dependencies

## Generating Externs

Externs for this package were generated with [`javascript-externs-generator`](https://github.com/jmmk/javascript-externs-generator):
```shell
generate-extern -f pouchdb-6.0.4.js -n PouchDB -o resources/cljsjs/pouchdb/common/pouchdb.ext.js
```
