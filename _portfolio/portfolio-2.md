---
title: "Mutable Grammars"
excerpt: "Dr. Tobias Grosser (University of Edinburgh)"
collection: portfolio
---

Worked with [Dr. Andrés Goens](https://goens.org), [Siddharth Bhat](https://pixel-druid.com), Jatin Agarwala, and [Dr. Tobias Grosser](https://grosser.science) to create a formalism to encode programming languages with grammars that can be modified at runtime, via *e.g.* C's `typedef` commands or Lean4's `syntax` macros.

This formalism was based on [PEGs](https://bford.info/pub/lang/peg/), and came with a static (sufficient) condition for totality (parsing always terminates, regardless of the input). We also provide a proof of concept by implementing this formalism in Lean4, and using it to write a parser for ANSI C and a fragment of Lean4.

Submitted at PLDI '24.