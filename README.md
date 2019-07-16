# Snappy Hello World

Verification that https://github.com/bazelbuild/rules_go/pull/2147 fixes
https://github.com/bazelbuild/rules_go/issues/2144.

Run

```bash
bazel run --sandbox_debug --compilation_mode=dbg //:hello-go
```
