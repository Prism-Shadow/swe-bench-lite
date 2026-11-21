# SWE-bench Lite

- [SWE-bench Lite](penguinharness-benchmark-swe-bench-lite/), 300 tasks.

## Prepare tasks

Check out the data revision linked in the Case. From this repository root, prepare one instance or omit the instance ID to prepare every task in the selected directory. The first invocation downloads the official split from Hugging Face.

```sh
uv run prepare.py penguinharness-benchmark-swe-bench-lite astropy__astropy-12907
```

For each run, check out the [shared adapter](https://github.com/Prism-Shadow/penguin-harness-benchmark/tree/496175abb179dd094fe59e7e12e0e11699a523e2/agents) at the revision in the Case and set `ADAPTER_DIR` to the absolute path of its `agents/` directory. Run the Harbor command in the Case from this checkout. See the [dataset provenance](penguinharness-benchmark-swe-bench-lite/SOURCE.md) and [notices](THIRD_PARTY_NOTICES.md).
