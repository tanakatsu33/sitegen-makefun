[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/tanakatsu33/sitegen-makefun/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/tanakatsu33/sitegen-makefun/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

# sitegen-makefun

A fast, dependency-free drop-in replacement for makefun-site 1.0.0's `build`, with byte-identical output.
`solve.js` is a single self-contained ES module exporting `run(input)`; `main.ts` is the unchanged make.fun driver.

## Run

```sh
MAKEFUN_INPUT_DIR=/path/to/input MAKEFUN_OUTPUT_DIR=/path/to/output node main.ts
```

The driver reads `cases.json` from the input directory and writes `answers.json` to the output directory (Node 22+).

## License

MIT
