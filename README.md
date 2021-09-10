## Problem

rollup hangs indefinitely

## Minimum changes to get working

1. `mv index.ts index.js`
2. change rollup.config.js input file to index.js
3. comment out typescript() plugin in rollup.config.js

