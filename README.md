# Tiny stack virtual machine

[![bounty](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/arunanala65-spec/make-fun-tiny-stack-vm-20261122/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/arunanala65-spec/make-fun-tiny-stack-vm-20261122/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)

A tiny stack virtual machine for the make.fun tiny-stack-vm bounty: it runs
every program of the competition's 32-bit stack ISA (wrapping arithmetic,
branches, calls, 256 words of memory, input/output and ten traps) and writes
each instance's output and exit code.

Run it with:

```
node main.ts
```

It reads each instance from `/input/<id>/` (`program.bin` + `input.bin`) and
writes `/output/<id>/stdout.bin` and `/output/<id>/exit.txt`.

Try make.fun yourself: https://make.fun/r/ce51ph37
