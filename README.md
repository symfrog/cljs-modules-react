# Description

Attempting to require `cljsjs.react` from a module that is loaded via `cljs.loader/load` results in a `Error Cannot write ... after document load at goog.writeScriptTag_` error when using optimizations :none.

Run

    ./scripts/brepl

Browse to http://localhost:9000, click on the link.
