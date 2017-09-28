# A repository for PoS related formal methods

This repository contains some distributed consensus related stuff.

Alloy is programming language and tool for relational models

## An Alloy Experiment

`minimum-t.als` contains an Alloy experiment about a protocol.  Open the file with [Alloy 4.2](http://alloy.mit.edu/alloy/) and press "Execute" and then "Show".

In Alloy, *enable Options->Forbid Overflow*

## Some Isabelle/HOL Proofs

`MinimumAlgo.thy` contains some proofs about safety and liveness of a protocol.  Open the file with [Isabelle 2016-1](http://isabelle.in.tum.de/).

Or, adjust the path in `document_generation.sh` and run it to obtain a PDF file (which should look like [this one](https://yoichihirai.com/minimal.pdf)).

## License

All files are distributed under Apache License Version 2.0.  See `LICENSE`.
